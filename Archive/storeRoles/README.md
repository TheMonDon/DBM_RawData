# Store all server roles into server variables (Per Server)
This is a single event that on startup will find all server roles and make them into server variables.
This was requested by NathanDontGotDis#1783 in DBM Network.

It creates a temporary file to save the server roles, so if you don't have file access this won't work.

# Known Bugs
- The server variables can not be seen inside DBM. This is not fixable and is how DBM is made.

Note: Probably requires DBM Beta and Mods.