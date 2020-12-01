# Advanced Ticket System
Created By: TheMonDon#1721
Requires latest DBM Actions and latest [Mods](https://github.com/dbm-network/mods) as of **November 30, 2020.**
This project is abandoned and will be revived for commissions only.

Credits:  
Ticket Log Idea: Blue Label#0001

# Description
This is a large/advaned ticket system which is in its beta phases. I believe everything is working but I am not 100% sure. Please report any problems to me on discord: TheMonDon#1721

# How do I enable it?
To get the basic system up and running run the command `supportSetup`, if it's already set up it will tell you.

# Known Bugs
- Global system (not per server) - Bug to me, but you may want that.
- If there is already channels with the same name, it will break.
- Active/Inactive doesn't check for a real ticket.
- Display Names with emojis in them break a lot of things.

# Versioning

**2.2.1**
- I have abandoned this as I have a better system on my own bot and this system has a lot of flaws that I realized while trying to fix it. I am open to comissions if you want a better ticket system for your bot.

**2.2.0**
- Bumped the DiscordJS.version check from 11.5.1 to 12.2.0
- Fixed a lot of the bugs since the last major update of DBM and DiscordJS broke a lot. (Definately has bugs still)

**2.1.0**
- Added check if ticket is setup before every command
- Fixed all issued with `reactSetup`!
- Add checks for permissions to setup `supportSetup` and `reactSetup`
- Changed all perms from `GUILD_OWNER` to `MANAGE_GUILD`. Requested and better!

**2.0.0**
- Added reaction role! :: download the event inside the events folder and the new `reactSetup` command to get started with it. Remember, it needs general Wrexes on-cached-reaction thing! **BETA**
- add (Increased message deletion time from 5 to 10 seconds)
- close (Increased message deletion time from 5 to 10 seconds)
- forceclose (Increased message deletion time from 5 to 10 seconds and updated file check to match new ticket log!)
- new (changed plain ID to "Author ID: [id]" and added topic to log file)
- reactSetup (NEW!) (Setup the reaction role menu under the current ticket system.) **BETA**
- remove (Increased message deletion time from 5 to 10 seconds)
- supportSetup (Increased message deletion time from 5 to 10 seconds, changed guild owner wording, added confirmation message.)
- NewTixReact (EVENT!) (Reaction checker for the reaction menu! Heavy beta but should work) **HEAVY BETA**

**1.1.1**
- Updated `supportSetup` command to the latest mods.

**1.1.0**
- Inactive (Fixed role being broken, added file info)
- Active (Fixed role being broken, added file info)
- ReqStaff (Request current channel log for any ticket. Requires Support Team Role!)

**1.0.0**
- New (create ticket command)
- Add (add user to ticket. Must be ticket creator!)
- Remove (remove user to ticket. Must be ticket creator!)
- Close (Closes ticket after 5 minutes of inactivity. Must be ticket creator! Sends log to creator.)
- ForceClose (Closes ticket imediately. Requires Support Team Role! Sends log to creator.)
- Active (Moves ticket to active category)
- Inactive (Moves ticket to inactive category)
- ^Ticket Log^ Logs everything to txt file said inside ticket.
- supportsetup (Creates the role and channels needed)
- req (Request current channel log. Must be ticket creator!)
