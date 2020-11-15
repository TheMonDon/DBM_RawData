# BlackList
Blacklist command for Discord Bot Maker

The main command and the blacklist_test command part are required.
**Put the run script from blacklist_test before all other commands! Make SURE to select do not call next action and evaluate text directly!!!**

Command usage: [p]blacklist <add | remove | check> <user> <reason>
- The reason is only needed on add, and remove.
- It has checks to make sure you don't add/remove someone already on/off the blacklist.
- It uses quick.db now! Old systems will not work with the new one!