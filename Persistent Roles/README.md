# Persistent Member Roles (Per Server)
These are two events member join and member leave to save the member roles when they leave and rejoin the server.
This was requested by NathanDontGotDis#1783 in DBM Network.

It will save the users roles into a file under ./roles/(SERVER_ID)/(MEMBER_ID).txt
It will delete the file after they rejoin the server.

9/5/2019: Added pr **COMMAND** this will enable/disable the system per server, very simple.

Note: Requires DBM Beta and Mods.