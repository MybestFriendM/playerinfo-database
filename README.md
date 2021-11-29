# SteamID & IP Database
Saves the SteamID and IP address of a player into a SQL database as soon as they join the server, alongside a timestamp. Ideal to keep tracking of how many unique users a gameserver has in a certain time span.

> Only tested in Counter-Strike: Global Offensive servers with a MySQL server.

# Usage
- Create a MySQL database.
- Add the database information in "steamid-ip" into your configuration file (addons/sourcemod/configs/databases.cfg).
- Upload steamids.smx into your gameserver.
