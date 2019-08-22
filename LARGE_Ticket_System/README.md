# Advanced Ticket System
Credits:  
Ticket Log Idea: Blue Label#0001

Created By: TheMonDon#1721
Requires DBM Beta and latest [Mods](https://github.com/Discord-Bot-Maker-Mods/DBM-Mods/tree/master) as of **July 28th, 2019!**

# Description
This is a large/advaned ticket system which is in its beta phases. I believe everything is working but I am not 100% sure. Please report any problems to me on discord: TheMonDon#1721

# What is ...?
Description coming soon...

# How do I enable it?
To get the basic system up and running run the command `supportSetup`, if it's already set up it will tell you.

# If you have any suggestions or things to change, let me know!

# Known Bugs
No known bugs currently.

# Versioning

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
