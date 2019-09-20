# Advanced Logging System
Based off DogV2's log system.
Made by: TheMonDon

# Description
This is an advanced logging system that checks multiple things and sends it to your defined channel.

Note: Requires DBM Beta and [Mods](https://github.com/Discord-Bot-Maker-Mods/DBM-Mods/tree/beta).
**NOTE: Requires node module quick.db!**

# What is logged?
Currently the following things are logged:
* Channel Created
* Channel-Deleted
* Channel-Updated
* Member-Join
* Member-Leave
* Message-Deleted
* Role-Created
* Role-Updated
* Role-Deleted
* Voice-Channel-Created
* Voice-Channel-Deleted
* Emoji-Created
* Emoji-Deleted

# How do I enable it?
You have to set your log channel and toggle the modules you want enabled.  
1. [p]setlogchannel #logchannel  
2. [p]togglelog all  

You can also do [p]togglelog (individual types) to disable certain "modules" like [p]togglelog emoji-deleted.  

# Versions

> **2.1.1 (BETA!)**
- Fixed logtoggle not working.

> **2.1 (BETA!!)**
- Fixed incorrect permissions
- Fixed file not being created and throwing error
- Changed all ADMINISTRATOR permissions to MANAGE_GUILD
- Cleaned up code
- Please report any bugs.

> **2.0 (BETA!!)**
- Everything from 1.0+
- Uses quick.db rather than DBM storage.
- Mostly if not all run script! (less actions)
- Please report any bugs.

> **1.0.1 (minor update 8/6/2019)**
- Role-Created (Event) :: Removed unecessary stuff
- Role-Deleted (Event) :: Removed unecessary stuff  
(Likely final update to V1!)

> **1.0 (includes everything updated prior)**

- SetLogChannel (command) :: Sets the logging channel.
- LogSystem (command) :: Gives you information about the system.
- ToggleAll (command) :: Toggles all systems.
- LogToggle (command) :: Toggle individual systems.
- Channel-Created (Event) :: Logs when a channel is created.
- Channel-Deleted (Event) :: Logs when a channel is deleted.
- Channel-Updated (Event) :: Logs when a channel is updated.
- Member-Join (Event) :: Logs when a member joins.
- Member-Leave (Event) :: Logs when a member leaves.
- Message-Deleted (Event) :: Logs when a message is deleted.
- Message-Edited  (Event) :: Logs when a message is edited.
- Role-Created (Event) :: Logs when a role is created.
- Role-Deleted (Event) :: Logs when a  role is deleted.
- Role-Updated (Event) :: Logs when a role is updated.
- V-Channel-Created (Event) :: Logs when a voice channel is created.
- V-Channel-Deleted (Event) :: Logs when a voice channel is deleted.
- Emoji-Created (Event) :: Logs when an emoji is created.
- Emoji-Deleted (Event) :: Logs when an emoji is deleted.

# If you have any suggestions or things to change, let me know!

# Known Bugs (afaik these aren't fixable!)
1. If a message is sent prior to bot being online, and message is edited, message edit is not logged.
2. If a message is sent prior to bot being online, and message is deleted, message deletetion is not logged.