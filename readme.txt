Tested on Nitrado PS4 game server version v1.09.153412 

Changes from default
- Increased amount of loot spawns per building for military/police/firefighter buildings
- Cars spawn with all items attached
- All items spawn at 100% capacity / health
- Weapons will always spawn with attachments -  attachments have been changed from default (Kobra sights/NVG sights/300rnd drum mags/60rnd coupled mags/etc)
- NVGHeadstraps will spawn with a pair of goggles attached
- Assault helmet will spawn with visor attached
- Field backpacks will spawn with a loadout inside (clothes/boots/nvg/etc)
- Vests will spawn with grenades inside them
- Plate carrier spawns with holster & pouches equiped
- Sawed off shotguns will spawn at garrages -  working on getting fuel cans also
- Police stations will spawn more weapon types
- Fire stations will spawn more weapon types
- Player spawns moved to military bases / outside police stations
- Added custom loot to water pumps an fuel stations
- Added more interesting loot to zombies & military containers (mags/guns/holsters/etc)
- Further increased loot spawning at military buildings, and helicopter crashes
- Increased number of helicopter crashes & added C130 crash type

Install instructions:
- I highly recommend installing FileZilla and Notepad++ before modding DayZ servers.
- Don't listen to all the youtubers who tell you to use the Nitrado web file browser - it's really easy to make mistakes, and it's slow and frustrating.
- My install steps include wiping all of the game files - you will lose all progression, but it will instantly give you a boosted server, without waiting for the loot economy to stabalise.
- This is optional but highly recommended.

1. Install FileZilla, and connect to your server using the details provided under 'FTP Credentials' on the Nitrado server dashboard.
2. Clone /download this repositoy onto your computer
3. On FileZilla, browse to the location on your PC (left side) where you have saved the files
4. On the right side (server) browse to /dayzps_missions/dayzOffline.chernarusplus
5. Select all the XML files/folders on your PC, including the db and env folder, and drag them onto the server. Select Overwrite all in this queue and OK. 
6. Check the modified dates have been updated on all the files and the subfolders on the server side. It doesn't matter if you copy this readme.txt too - it won't hurt anything.
7. Browse back to the Nitrado dashboard and select "reinstall" on the left. You will lose all game progress doing this, but it's the best way to get the mod running from the get go. 
8. Once you have told the server to reinstall, go back to the "general settings" page. Keep refreshing, once the hostname changes to nitrado.net gameserver, scroll down and deselect "Reset Mission-xml to default", and save - it WILL be ticked at some point during install, you MUST untick/save it.
9. Once the install has completed the game will boot up with the boosted files and spawn the loot etc you are hoping for. 
- If you have a save progression you really want to keep, you do not have to do the "reinstall" (steps 7-9), you can simply just reboot the server. I haven't done a lot of testing this way, it will likely take quite a while for the newer items to start appearing.

If when you load into the game you spawn at a "vanilla" location, it hasn't worked properly. You may have missed the "untick" during the reinstall? Repeat steps 4-9.
Zombies should also have "boosted loot", and weapons should be easy to find at military bases. Jackets/vests/bags/etc should contain loot.
This has only been tested on the version listed above. If the game gets updated you may need to do some merging. It shouldn't be different for Xbox Vs PS4.

Boosted loot/custom guns/PVE test server copy my config github.com/t0yshop

It would be nice for you to give me credit if you intend on using this as part of a tutorial / guide, but feel free to use on your public servers for free.