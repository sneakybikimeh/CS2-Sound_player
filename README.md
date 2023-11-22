# CS2's Sound_player
This set of configs facilitate listening to every game sounds available in Counter-Strike 2.


# Installation
1. Open the archive and extract the contents of the cfg folder into the following path folder :
\...\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\sound_player\

3. Launch the game, boot up a practice server where you can turn on sv_cheats 1 and type in the console the following command: "exec sound_player\sound_player.cfg".
   
4. Your console should display a message saying : "SOUND_PLAYER loaded succesfully ! :)"; otherwise you must have a path issue and the file did not load correctly.

5. Close the console and press MOUSE1 to start cycling between the sounds, press MOUSE2 to stop it.


# Usage
- play_sound is the main command to use.
- play_sound_skip is the same but it cuts off previous sound.
- stopsound will cut off any sound currently played.
- Everytime you use the play_sound keybind, it will play the current sound in stack, then store the next one in memory.
- If you want to skip to a specific sound, type playsound_[number] into the console, the keybind play_sound will keep it in memory.
- The list of all the sounds with their index is available at "...\cfg\sound_player\sound_list.cfg".
- If you want to reset default mousebinds, type resetmouse in console

- The only file you should ever modify (if you know what you're doing) : "...\cfg\sound_player\sound_player.cfg", otherwise you will probably break the script !
- I recommend restarting the game after using this script to avoid any lags, sinces it loads up almost 40k aliases into your game !
