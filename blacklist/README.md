# BlackListDBM
Blacklist command for Discord Bot Maker

The main command and the blacklist_test command are required.
**Put the run script from blacklist_test before all other commands! Make SURE to select do not call next action and evaluate text directly!!!**

The third command, blacklisted is for users to check wether or not theyre blacklisted.

Command usage: [p]blacklist <add | remove | check> @user> [reason]
- The reason is only needed on add, it has checks to make sure you put a reason.
- It has checks to make sure you don't add/remove someone already on/off the blacklist.

Command usage: [p]blacklisted (@user)
- This command is for users, used by itself tells them if theyre blacklisted or if used with an @user tells them if another user is blacklisted.

Note: Probably requires DBM Beta and Mods.