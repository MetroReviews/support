### **These rules only apply for list owners/devs who are a member of Metro Review**

This document will aim to describe the exact schema and APIs provided by MR and the exact APIs and functionality your list must provide to MR.

### **Legacy Name**

The project originally used to be called Bot Reviewer Consortium but the name was changed due to issues. As such some places may still refer to it as Bot Reviewer Consortium or BRC for short.

### **Tech Stack**

Below is the tech stack used internally for the API

- Python
- Piccolo ORM/Piccolo Admin
- FastAPI
- PostgreSQL 14

### **API schema**

See https://metrobots.xyz/docs

### **Adding support for your list**

**Mandatory Requirements**

The below must be inplemented to be properly supported on BRC

1. Whenever someone posts a bot to your list, send a POST to ``/bots`` as per https://metrobots.xyz/docs#/default/post_bots_bots_post
2. Whenever a bot is claimed, unclaimed, approved, or denied, you will get a POST to your lists webhook URL (configured in our GC) as per the below:

- All the bot fields as per https://github.com/MetroReviews/backend/blob/main/brc/tables.py#L55
- ``reviewer`` (snowflake) -> The person who reviewed the bot
- ``reason`` (string) -> The reason or feedback for the approve, deny or unclaim. In a claim, this will always be `STUB_REASON` and should be ignored.

The request will contain your lists secret key in ``Authorization`` header.
