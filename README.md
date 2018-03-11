# Egg-Eco
This is an Egg for Pterodactyl. It provides support for hosting an Eco server.

## Using
In Pterodactyl, click on *Import Egg* at the page *Nests*.

Also you'll have to disable throttling in the daemons config `/srv/daemon/config` as the gameserver creates a lot of messages while generating maps. Also you need to restart wings.
Alternatively you could upload your own map before starting the server.

## Info
The Egg uses a custom docker container uploaded by me to the docker hub. The mono docker container shipped with Pterodactyl  makes the server crash as libraries are missing.

