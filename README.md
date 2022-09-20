### See a list of maps
![image](https://user-images.githubusercontent.com/43156510/186551454-a581b99f-c04f-4ad4-b764-dba0de149b01.png)

### Vote for a map
![image](https://user-images.githubusercontent.com/43156510/186552101-cf190b0b-6921-4150-be24-534ccbd4930e.png)

### When another player votes
![image](https://user-images.githubusercontent.com/43156510/186552912-f18fa36d-88d8-42ba-a91c-07285fa12425.png)

### When voting is complete
![image](https://user-images.githubusercontent.com/43156510/186552493-c49b6d29-e37c-4253-a317-0dda00bb2a43.png)

### When there is a tie
![image](https://user-images.githubusercontent.com/43156510/186553310-cde29a6d-1234-4be4-8c30-e721b12bbdb0.png)




# Vote next map

A lightweight javascript plugin that adds a map list command, and map voting with votes that expire.

## Installing

Simply download the zip file, pull the folder inside of it out, and put it into your config/mods folder.
(A server restart is required to update mods/plugins on your server.)

# Usage

## Client Commands
`/maps` will show a list of (custom) maps on the server

`/nextmap <map number>` will vote for specified map

## Server Commands
`votechangesmap <true/false>` will set whether a vote changes the map after. *This saves between server restarts*

After the first player votes, a 3 minute timer is started. After the timer runs out, the votes for each map are counted and the map with the most votes will be selected next.

If there is a tie in votes, it will pick randomly from the winners.

