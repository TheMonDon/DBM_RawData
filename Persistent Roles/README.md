# Persistent Member Roles (Per Server)
These are two events member join and member leave to save the member roles when they leave and rejoin the server.
This was requested by NathanDontGotDis#1783 in DBM Network.

It will save the users roles into a file under ./roles/(SERVER_ID)/(MEMBER_ID).txt
It will delete the file after they rejoin the server.

# Known Bugs
- If the user has too many roles the console gets spammed with "Error: Adding the role timed out." but eventually adds it. Could maybe fix with a small wait inbetween adding roles.

Note: Probably requires DBM Beta and Mods.