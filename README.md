<h1>FNAF 1 Minecraft Clone</h1>

Requires Spigot/PaperMC, <b>Skript</b> and <b>Citizens</b>.
Tested with Skript 2.6.4 and Citizens 2.0.27-SNAPSHOT.
No extra Skript add-ons or server plugins required.
WorldEdit recommended to repeatedly duplicate your FNAF map.
FNAF world built in Minecraft 1.16.5, older server software will require manually recreating the map.
FNAF 1 map created by SilverDagger. All other aspects created/developed by awgybop1.
Built over the course of 20 hours during Christmas 2023, with additional development over 4-5 days for bug testing.

Game comes with world already setup, allowing for 15 consecutive FNAF games at once.
Simply drag and drop the Skript (FNAF.sk) and the world (FNAF Folder) into your server's appropriate directories.
(/plugins/Skript/scripts/) for FNAF and (/) for the world.
You can freely change the map, but as of now you must make the changes directly to the Skript variables.
<i>The recommended way is to enable Skript parsing in chat via your Skript config.yml, and using Skript <b>\set {var} to ""</b> logic in the chat.</i>
An easier way of modifying the game's behavior without modifying the script will be added in a future version.

Skins are also manually set in the script, based on player IGNs found on www.namemc.com, and as such are likely to break/change over time.
A better solution to storing skins will be added in the future.

Camera black-outs technically exist, but are not enabled due to their annoying nature within the game. This can be changed in the future.

AI Behavior has been replicated as accurately as I can get it, with the AI level ranging from 0-20 and increasing for the NPCs based on the Night and Current Time.
Foxy/Freddy acknowledge when they're being watched on camera (any camera for Foxy), and will not move, just like in the original game.
Foxy has the stages just like FNAF 1, and will run to the player's office if he gets triggered while cameras are closed and is in the final stage.
If Foxy runs and the door is closed, he will steal some of the player's power, just like the original game.
If the player runs out of power, the game will play the same sequence as FNAF 1, with a random Freddy jumpscare unless the clock strikes 6AM.
All six nights are implemented, and the AI levels for the NPCs correspond to the real game.
The power system also exists, allowing for turning on lights, closing doors, etc to work as expected.
The camera system works similar to the original, although the way cameras are toggled has room for improvement.

Sound effects have been implemented, but may not fully reflect the actual game. A resource pack may be included in the future to fully recreate the sounds used in FNAF 1.
