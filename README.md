# Vote next map

A lightweight javascript plugin that adds a map list command, and map voting with votes that expire.

## Installing

Simply download the zip file, pull the folder inside of it out, and put it into your config/mods folder.
(A server restart is required to update mods/plugins on your server.)

## Usage

`/maps` will show a list of (custom) maps on the server

`/nextmap <map number>` will vote for specified map

After the first player votes, a 3 minute timer is started. After the timer runs out, the votes for each map are counted and the map with the most votes will be selected next.

If there is a tie in votes, it will pick randomly from the winners.

