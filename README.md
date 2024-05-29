

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
o get the reworked game builds, go to "Releases", choose the latest "v*. *. *-alpha" tag and find the .exe files in the "Game Binary" zipped file. The .exe file is the generated executable, while the .mfa file in "Source Code" zipped file fis the (recovered) Clickteam Fusion project file necessary to generate the .exe (note in this game's case, it requires some extensions from Clickteam Fusion 2.5 Developer builds to be opened).

Also provided in main lobby are save files just in case if any tester wants to cut the process short and go directly to the places that bugs will happen in original version (spiked ball hazard in: science hall parts 1, 2, 3; Katharina's quarter part 3), they may want themselves to be placed at: C:/User/(User name) (hidden folder)/Appdata/Roaming/MMFApplications
(extract the save file zip first.)

#### NEW Hotkey Functions #### 

Due to the limitation of original GUI, some new functions cannot be directly embedded in the GUI...
- Toggle anti-alias on/off: F5/F6
  

#### Read this if antivirus softwares flagged the game as Malware #### 
It's something about Clickteam's engine itself. Antivirus softwares don't seem to be too kind towards some Games used Clickteam's engine. 
If the problem that the antivirus softwares flagged the game as malware occurs, either turn off the antivirus software in question, or add the game to its white list. 
Also avoid directly sharing the zips or folder(s) which contain the exe file unless really necessary because some net drive safety calculation like Google's, don't seem to be too happy with the game.


#### Read this if your screen capture program did not work in Reworked LC1 #### 
Some capture programs will have compatibility issue with reworked LC1 on Windows 10 (for example, Ocam). This is because the compatibility issue of some revisions of Windows 10's Direct X9 mode. If you want safe screen recording methods, more mainstream programs (like OBS) will work.


#### Read this if you encountered framerate problem in fullscreen mode #### 
It's something about your setting of VSync under Direct X 9 mode. If your only graphic card is a Nvidia GTX graphic card, toggle VSync in your Nvidia control panel to "fast" or "on" if you encountered
frame rate problem in fullscreen mode.




### Update History ###

 #### [0.5.3] - 2024/5/28 #### 

`ADDED` - Function to remember the value of currently equipped sub weapon into save file.    (Aceearly1993)  
`HOTFIX` - Inner yard 2: An attempt to rule out a softlock bug by changing one regulation to an object.    (Aceearly1993)  
`HOTFIX` - Inner yard 2: An attempt to rule out a softlock bug by adjusting positions of several platforms.    (Aceearly1993)  
`HOTFIX` - Inner yard 3: An attempt to rule out a softlock bug by moving the position of an object that will trigger 
the event to back to map screen upon defeated the stage boss of Inner yard and return to the location once again.    (Aceearly1993)  


 #### [0.5.2] - 2024/5/16 #### 

`ADDED` - System Config function in map screen.    (Aceearly1993)  
`CHANGED` - Extra life counter's calculation rule to fit the inclusion of System Config function.    (Aceearly1993)  
`CHANGED` - Map screen UI logic to fit the inclusion of System Config function.    (Aceearly1993)  
`CHANGED` - Adjusted the bonus lives offered by a secret command combination when it's executed in lower difficulty.   (Aceearly1993)  


 #### [0.5.1] - 2024/3/23 #### 

`FIXED` - A bug (?) that caused efrain to atumatically die when performing air float out of available camera zone. (Aceearly1993)  
`ADDED` - Simple navigations to music room function.  (Aceearly1993)  
`CHANGED` - Extra life counter now properly displayed up to 99 lives.   (Aceearly1993)  


 #### [0.5.0] - 2024/3/2 #### 

`FIXED` - An awkward moonwalking happened after main character movement plugin swaps. (Aceearly1993)  
`FIXED` - A bug which caused controller mapping to be reverted to default upon executing a reset/close to the game.  (DragonX24)  
`ADDED` - A hotkey set so that the game's anti-alias can be toggled on/off to fit the preference of more people.  (Aceearly1993)  
`ADDED` - Important UIs on start screen to make players not get lost quickly.  (Aceearly1993)  


 #### [0.4.9] - 2024/2/20 #### 

`ADDED` - A simple music room function. (Aceearly1993)  
`ADDED` - Port a secret command well hidden in original version to somewhere more useful. It may be helpful to someone who still couldn't beat the game.  (Aceearly1993)  
`ADDED` - Regulations in keyboard remap function so that the hardcoded system keys won't get accidently recognized as valid input in keyboard remap.  (Aceearly1993)  
`ADDED` - Regulations in keyboard remap function so that multiple keyboard keys won't get registered the same key function. (Aceearly1993)    
`FIXED` - A bug to text size after resizing the windows display scale to be higher than 100%.  (Aceearly1993)  


 #### [0.4.8] - 2024/1/29 #### 
 
`ADDED` - Direct X 11 support.  (Aceearly1993)  
`CHANGED` - Organized all text-related event in Global events region to fit Direct X 11.  (Aceearly1993)  
`CHANGED` - Formatting of video option application as an attempt to avoid antivirus program malfunction.  
The reformatted video option application is now "Castlevania The Lecarde Chronicles video system new.exe" 
to make differences to the original application without "new". (Aceearly1993)  


 #### [0.4.7] - 2024/1/4 #### 
 
`HOTFIX` - Condemned room part 3: A vanilla bug which will cause Efrain to lose track after falling from position high enough to cause camera desync.  (Aceearly1993)  
`HOTFIX` - Condemned room part 3: A bug caused by porting the game project to newer version of the engine, which will cause softlock that traps Efrain in a vertical passage.  (Aceearly1993)

 #### [0.4.6] - 2024/1/2 #### 

`FIXED` - A vanilla bug which will cause invincibility potion timer to be invisible after scene transition.  (Aceearly1993)  

 #### [0.4.5] - 2023/12/12 #### 

`FIXED` - A bug newly generated by plugin swaps which will cause Efrain to be stuck in a half crouch stance under rare circumstances. (Aceearly1993)  
`FIXED` - A vanilla bug which will cause Efrain to clip into the wall and may lost outside of bound by repeatedly 
turning around and crouching near the "air walls" blocked by camera event in some boss fights. (Aceearly1993)  
`CHANGED` - Load method of Sounds to improve loading time when changing scenes. (Aceearly1993 & Mig)  
`CHANGED` - Animation Speed of dying pose to make it more natural & on par with Chronicles of the Wolf. (Aceearly1993)  

 #### [0.4.4] - 2023/12/1 #### 

`FIXED` - Inconsistency of speed of Efrain's jumping frames.  (Aceearly1993)  
`CHANGED` - Increase vertical hit detection zone of Efrain's whip.  (Aceearly1993)  
`RETRIEVED` - Source material of original video mode option/launcher in the vanilla game. (Mig)  
The compatibility should be identical to original by now.  

`ADDED` - Simplified Chinese variant of original video mode option/launcher. (Aceearly1993)  
`ADDED` - Simplified Chinese variant of credit roll.  (Aceearly1993)  
`CHANGED` - Minor adjust to other languages in response of the addition of Simplified Chinese variants.  (Aceearly1993)  


 #### [0.4.3] - 2023/11/22 #### 

`FIXED` - Several missing texts in German localizations reported.   
`CHANGED` - Added additional commands as an attempt to rule out V-Sync problems.  
`FIXED` - Corrupted text characters in txt file archived in github page.  
`ADDED` - Simplified Chinese variant of an easter egg screen.  
`FIXED` - Position and proportion of several ending pictures.  


 #### [0.4.2] - 2023/11/14 #### 

`HOTFIX` - An attempt to fix an issue regarding controls after clicking out of window when an action frame is intact.  

 #### [0.4.1] - 2023/11/9 #### 

`HOTFIX` - An issue after swapping the contoller plugins that text box will incorrectly skips in Henri Sadis the priest's dialogue and one old adventurer's dialogue.  
`FIXED` - A bug caused remapped controller button layout not following new contoller plugins in some scenarios.  
`FIXED` - A mapchip object missing in entrance hall part 3 in reworked edition.  



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
- DragonX24 (https://www.projectdread.com/) - Principle of Lecarde Chronicles 2 reworked edition control remap
- Exorion Hagen - German text fixes
- Orx_ , 铃川千雪 , AngelKawaru , 浅野川 - Test plays


... and all the people in game credits.


