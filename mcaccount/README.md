# mcaccount Command
This is a revised version of the old mcaccount command found on the DBM raw data server.

I made a lot of changes to this including: Checking if account is even possible to exist before sending
the request to mojang, as well as a check after sending to mojang to not crash bot, thanks to General Wrex.

Usage: [p]mcaccount (username)
This will display the following stats: Name Changes, UUID, NameMC Link, and their skin inside a nice embed message.

Note: Probably requires DBM Beta and Mods.