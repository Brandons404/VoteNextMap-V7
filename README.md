![image](https://user-images.githubusercontent.com/43156510/186551454-a581b99f-c04f-4ad4-b764-dba0de149b01.png)
![image](https://user-images.githubusercontent.com/43156510/186552101-cf190b0b-6921-4150-be24-534ccbd4930e.png)
![image](https://user-images.githubusercontent.com/43156510/186552139-8947c3e8-61ed-4f26-aea0-9a0e2edf000f.png)
![image](https://user-images.githubusercontent.com/43156510/186552493-c49b6d29-e37c-4253-a317-0dda00bb2a43.png)



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

