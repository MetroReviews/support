### **Step 0 Rules**

All rules under https://github.com/meew0/discord-bot-best-practices apply, Once again, these rules will change depending on the bot. Use judgement here.

### **Basics**

0. Your bot must be public, online and invitable during and throughout testing and must continue to work after initial review as well.

1. It is perfectly OK to submit bots and servers that are in competition with bot lists (such as API/manager bots of other bot lists with their permission) as long as permission is explicitly granted and the bot serves a actual function.

2. Your bot may not be a fork or instance of another bot without substantial modifications and prior permission from the owner of the bot you have forked/made an instance of.

3. Your bot should handle errors in a user-friendly way. A way of reporting errors is a nice extra tidbit to have though not strictly required. Giving tracebacks is allowed however discouraged if it does not leak sensitive information such as bot tokens or private information on a user.

4. Your bot must respect the Discord API and rate-limits. This also means that your bot should not spam messages or be a 'rainbow role' bot.

5. Your bot must follow the Discord ToS and guidelines. This also includes no invite rewards (as in giving rewards for just joining another server), no nuking etc.

6. Custom bots based of/dependent on/running an instance of another bot such as bot-makers not allowed by discord, BotGhost, MEE6 Premium, Wick VIP is prohibited unless it has unique features that you have added to it and can be configured on other servers by users.

7. For frameworks such as redbot, you must have at least 3 custom-made cogs (or the equivalent for other frameworks). You must give credits to any framework you are using. BDFD/BDScript/other bot makers are not allowed on RBC lists unless it is also allowed by Discord and your bot is high-quality and has features

8. Generator bots are not allowed whatsoever on RBC lists

9. Bots may not impersonate other bots

10. The term 'loli' and other terms referring to the sexualization of young children is strictly probihited

### **Commands**

1. Your bot must have a obvious point of entry, This could be a help command or just slash commands. 

2. If your bot has level messages or welcome messages, it must be optional and disableable

3. Your bot should not DM users when it join unless it needs to DM the owner important or sensitive information (such as Wick's rescue key)

4. Your bot should not DM users when they join a server unless a server manager chooses to enable such a feature. Bots that do need to DM users such as verification bots may be exempt from this rule on a case by case basis

5. All commands of a bot should check user and their own permissions before doing any action. For example, your bot should not kick users unless the user and the bot has the Kick Members permission. Commands may not be admin locked and NSFW commands must be locked to NSFW channels

6. Commands must have a purpose (no filler commands). Filler commands are ignored and will make your bot low quality. An example of filler commands/commands with no purpose is a bot with 20 purge commands or commands which are repeated in different ways or serve the same purpose

7. Bots should have at least 5-7 working commands and at least 80% of commands shown in its help command working. If your bot has a really unique feature however, this rule may be reconsidered for your bot.

8. Sensitive commands (such as eval) should be locked to bot owners only. RBC is not responsible for the code you run or for any arbitary code execution/privilege escalation on your bot however we do care if this affects servers your bot is in.

9. Bots with common prefixes (`!`, `?`, `.`, `;`) should either have a customizable prefix (if it has Message Content Intents), use mentions or use slash commands. If your bot does not use slash commands, it must have an easy way to find its prefix. Some good places for this are on bot mentions and bot status

### **User Safety**

1. Bots should not mass DM or be malicious in any way such as mass nuke, scam bots, free nitro bots. 

2. Your bot must not have a copyrighted avatar or username. All assets used in your bot must be either owned by you or with permission from the copyright owner. **Your bot must, in short, abide to third-party rights**

3. Abusing Discord (mass creating or deleting channels, mass DM/spam/nuke bots) is strictly prohibited and doing so will get you and/or your bot banned from all RBC lists.

4. Your bot may not be hosted on Glitch/Repl Free Plan and use a software to ping your project. This is also against Repl/Glitch ToS.
Your bot must be online during testing

5. **Your bot must not reward users for voting for another bot**

6. **Your bot may not contain any seizure-inducing content**

7. All bots that provide vote reminders or a `/dm` command **must** provide a way to disable it. All `/dm` commands must say who DM'd the user and must provide a way to disable it

### **Common Etiquette**

1. DMing or otherwise demanding staff to ask for your bot to be approved/reviewed is strictly prohibited. Your bot will be denied or banned if you do so. **However, if it is taking over one week to approve your bot, then you can/should ask on the BRC server**

2. You must not attempt to use RBC lists to distribute malware (such as XSS attacks, DDOS, rootkits, spyware etc). This will lead to your bot being banned from all RBC lists.

3. You can always appeal a ban or resubmit your bot if the bot list you have added your bot to has support for resubmissions. Your bot list should, along with a link to this page, state whether or not they support this..
