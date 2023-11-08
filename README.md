

## Description
A portion of source code of the fan-game Castlevania: The Lecarde Chronicles (1) made by Migami Games. Due to a HDD failure, the original source have been lost. This repo is an atempt to preserve, fix and improve this game.

Unfortunately, the recovery process ended up corrupting hazard mechanics, graphic order and more. So, if you know any of the following languages and is interested in helping us out by fixing this project, feel free to contact us, we are in need of:
- Somebody who're both very good at using Clickteam Fusion and a good French speaker (preferably)
- Somebody who're good at using Clickteam Fusion


Upon successfully recovered 99% of event codes through the help of Mig, the project's state is strong enough to let everyone capable to mess around CTF coding to notice and help us.


## Disclaimer
This project can be considered like a younger brother of the LC2 project that I (Aceearly1993) was actively involved: (https://github.com/katriellucas/lecarde-2) so most things are also applied here:

We contacted Migami Games and got approval to keep this repository up.  

The release of Lecarde Chronicles (1) got permited by Konami, the game and its assets are freeware and **_SHOULD NOT_** be sold, this also includes the source code. Any modifications you do have also to be free. Castlevania is an intelectual property owned by Konami, please support the company by buying their official releases.


## Usage
To get the base source code, go to "Releases", choose the tags with newer date. Access the. mfa in the release to get the file.
The "Binary" contains the generate .exe file.

Also provided in main lobby are save files just in case if any tester wants to cut the process short and go directly to the places that bugs will happen in original version (spiked ball hazard in: science hall parts 1, 2, 3; Katharina's quarter part 3), they may want themselves to be placed at: C:/User/(User name) (hidden folder)/Appdata/Roaming/MMFApplications
(extract the save file zip first.)


#### The Issue We Need Additional Helps #### 

- Add in-game GUI and functions to freely edit controller input in the game (like in reworked LC2)

- Several music clips and sound effect clips are needed to be replaced in order to get around copyright infringement risks. This case needs additional helps from composers/sound effect creators.
  
- An overlap of Global values is noticed in control remap GUI reworking process (which uses LC2 rework control remap event) and will lead to unable to remember controller button mapping storage. If anybody has solutions to ease this bug please help us.
 


### Update History ###

 #### [0.4.0] - 2023/11/8 #### 

`FIXED` - An oversight in original that an event trigger is not cleaned up in story cutscene, which will cause multiple languages to overlap in the same text display region.  
`CHANGED` - Rework of control remap GUI. Now the game uses the same standards as Lecarde Chronicles 2 reworked edition's control remap GUI; Controller and keyboard remapping is now supported.  
`CHANGED` - graphics of control config screen to fit the new control remap screen.  


 #### [0.3.1] - 2023/11/6 #### 

`ADDED` - More default keyboard mapping template to fulfill more situations and preferences until a better key remap GUI got solved in the future.  
`ADDED` - A simple background to make the control config screen not look empty.  
`CHANGED` - Main menu: Hotkey changes due to added default keyboard mapping template:  
- F7: Force keyboard play.  
- Hold F7 then Space: Change default keyboard mapping template.  
- Backspace: Restore joypad play.
  
`CHANGED` - Ruins 1: Nerf the spawner of medusa head enemies so that it's slightly more fair than in original when doing whip only runs.  
`CHANGED` - From now on, the game's cutscenes happened in before and after opening stages, can be skipped.  
`CHANGED` - From now on, the game's input can read Enter key as valid inputs when selecting all options in title menu in order to reduce confusions.  


 #### [0.3.0] - 2023/11/2 #### 
 
`FIXED` - A bug where the background of hunting ground part 2 boss will be missing in later versions of Fusion's frame editor.  
`FIXED` - A bug in original where the hit detection of chained spiked ball hazards will go awry and produce invisible hit detection in some OSes.  
`FIXED` - A bug in original where in inner yard 1, one zombie enemy will briefly appear a few frames before he really should.  
`FIXED` - Lock the Alterable value C of trigger object to 2 in order to make the key presses only count as valid at "main screen visual" region.   
`CHANGED` - Hotkey to trigger an easter egg screen to reduce confusions.  
`CHANGED` - One Simplified Chinese embedded text.  
`CHANGED` - Inner yard 2: Minor adjust of one specific hazard to make it not as extreme as in original.  
`CHANGED` - Inner yard 2: Nerf the spawner of eyeballs so that it's less luck demanding to go across one specific hazard than in original.  
`CHANGED` - Ruins 2: Nerf the spawner of spirit enemies so that it's slightly more fair than in original when doing whip only runs.  
`CHANGED` - Skeleton gunman: Adjusted skeleton gunman's animation so that it's slightly less luck demanding to wipe it out without taking damage than in original.  
`CHANGED` - Drops in a candle so that it will always grant a healing item instead of sometimes dropped a large heart instead.   


 #### [0.2.0] - 2023/9/25 #### 


`RELEASE` - Initial soft launch to get baseline modern compatibility in place.  
`ADDED` - Simplified Chinese text.  
`ADDED` - Most of Simplified Chinese specific graphics.  
`FIXED` - An attempt to fix a bug in original by set the game's window to always focus.  
`CHANGED` - When the game is booting, the game will default to windowed mode instead of Fullscreen.  
`CHANGED` - The game's window can now be resized for better availability to video game streamers.  
`CHANGED` - Default Hotkeys:  
-    Instant Game Over - From "Backspace" to "F7"  
-    Soft reset - From "F2" to "Ctrl+F2"  
-    Quit Game - Removed the function to instantly quit the game by pressing "Esc" (too annoying)   
         The game's quit hotkey will now be Alt+F4 like most common games and programs.  
-    Pause - From "Space" to "Esc" (there's considerable amount of people that will use Space for jump)  

`CHANGED` - Reworked UI to follow the change of hotkeys.  


 #### [0.1.0] - 2023/9/17 #### 

`START`  - Project's start/resume.  



 ### Special Thanks ###

- Katriel (https://github.com/katriellucas) - Project lead of Lecarde Chronicles 2 Reworked edition and major helping hand
- palmymkgames - Technical support
- Migami Games - The great author of original game; source document provider
- Kostya (https://github.com/1987kostya1) - Technical support



... and all the people in game credits.


