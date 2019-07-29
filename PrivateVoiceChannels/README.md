# Private Voice Channels

This has been requested a few times in the network and I decided to make it.

# How it works:
First you set it up with the command `privVoiceCreate` to create the category and join to create voice channel.
Then when a user joins the "Join to Create" a new channel is made with their displayName and "-private".
They then get moved to their new voice channel.
When all the users leave the voice channel the voice channel is then automatically deleted.

# Other info
The channel isn't actually "private" as anyone can join, but in the future if this is requested I can look into a command to add users.

Note: Requires DBM Beta and the latest version of mods as of July 28th, 2019.

# Extra Note:
If you receive the error "channelType.toUpperCase is not a function" this is caused by the create channel actions being updated to support discord.js 11.5.1+ and no longer work right on discord.js 11.3 that's installed by default. 
Do `npm i discord.js` to solve this, it should install 11.5.1 as of now. Do `!info cmd` and `!info` npm in #bot-commands for more info.