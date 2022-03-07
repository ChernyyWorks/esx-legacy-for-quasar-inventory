Hi there !
It's my first post on github, and I'm releasing a free edited base with esx-legacy 1.5 compatible and made for Quasar Inventory.


How can I install it ?

--> Download :
- download this repository, latest fivem artifact and also download [inventory] assets from keymaster.fivem.net

--> Setup :
- config the server.cfg file, install the artifact, drop the inventory asset somewhere in /resources .
- start xampp and create your database(utf8_general_ci), import legacy.sql and then inventory sql.
- Config anything else you would like to change.

--> Run it:
- try to run the server, be patient the first time and check if there are any errors..
- and enjoy ! :)

--------------------------------------
What changed from esx-legacy ?

->> Voice and Database :
- esx_voice replaced by pma-voice.
- oxmysql updated to 2.1.1. (if you use quasar-smartphone, you won't need to update it.)

->> es_extended :
- disabled inventory, moved to licence and paycheck changed.
- some client and server function edited.
- Duplicate commands have been removed, and the others were edited to work with inventory.

->> esx_statut :
- Literaly drag and dropped from quasar's github to my resources file. (https://github.com/quasar-scripts/esx_status)

->> esx_basicneeds :
- same for basicneeds, refer to his version for more informations. (https://github.com/quasar-scripts/esx_basicneeds)

->> esx_ambulancejob :
- removeItemsAfterRPDeath has been edited to be compatible with qs-core. (only works if you setted it on in the job config)

->> esx_policejob :
- OpenBodySearchMenu function has beed edited too. you can open an inventory in the menu instead of using native 'steal' option.

->> esx_property :
- OpenRoomInventoryMenu function has been edited, now you can open

(If you want, you can type 'Quasar' in vscode and you will find all modifications.)

--------------------------------------
That's all ! basically nothing more than what Quasar recommended to modify on his documentation.
This edit of es_extended is nothing than a little nudge to help you to launch your first server with the inventory.
As mentioned before I'm not selling anything ! I only wanted to share my personal pre-base because I received a few messages on discord of people having troubles with the installation of 1.5 esx-legacy and I wanted to help them by sharing these files. Hope you enjoy !

If you want to know more about the esx framework on fivem, this is the github :
- https://github.com/esx-framework

If you want to purchase Quasar Inventory or just want to know more about it :
- Inventory https://quasar-store.com/package/4770732
- Preview https://www.youtube.com/watch?v=PsqMPUhJHMg


Thanks for reading :)

