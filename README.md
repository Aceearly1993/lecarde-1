# The LC1 Rework Project

![LC1-5](https://github.com/user-attachments/assets/0c161026-4dbf-4b6a-a6e1-87d28fd586ac)

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
![LC1-6](https://github.com/user-attachments/assets/f0da08ce-e9c0-4009-937f-f9b3b1514282)



to get the reworked game builds, go to "Releases", choose the latest "v*. *. *-alpha" tag and find the .exe files in the "Game Binary" zipped file. The .exe file is the generated executable, while the .mfa file in "Source Code" zipped file fis the (recovered) Clickteam Fusion project file necessary to generate the .exe (note in this game's case, it requires some extensions from Clickteam Fusion 2.5 Developer builds to be opened).

Also provided in main lobby are save files just in case if any tester wants to cut the process short and go directly to the places that bugs will happen in original version (spiked ball hazard in: science hall parts 1, 2, 3; Katharina's quarter part 3), they may want themselves to be placed at: C:/User/(User name) (hidden folder)/Appdata/Roaming/MMFApplications
(extract the save file zip first.)


#### System compatibility warning #### 

The game is only verified to be working as intended on windows revisions up until Windows 10 20H2 revision. 
Beyond that revison it's out of my control and nor will there be any hope of making compatibilities specifically for the unintended system (at least from me).

#### Read this if you encountered random crash exit when pausing #### 
![LC1-4](https://github.com/user-attachments/assets/90c17c62-666e-4adc-ac57-4be34611e825)

It may or may not have something to do with system compatibility, but make sure you have all the font installed which the game demanded:

Arial Unicode MS (DX11)  
Baskerville Old Face (DX9)  
MS UI Gothic  
Tahoma  
Old English Text MT (DX9)  
Californian FB  (DX9)  
新宋体 (DX9)  
黑体 (DX9)  

If some of the fonts did not get installed in you computer, the game will be unable to find them and thus cause problems.

#### NEW Hotkey Functions #### 

Due to the limitation of original GUI, some new functions cannot be directly embedded in the GUI...
- Toggle anti-alias on/off: F5/F6

#### About "LC2_KeyBinding.ini" #### 
![LC1-1](https://github.com/user-attachments/assets/403ecb99-56fb-4758-bc94-584eef6083a9)

A reworked version of the keyboard control created by DragonX24. 
This file must be placed in the same directory the game locates if you downloaded the game and moved the game files to a fresh new location.

  
#### Special Note for Controllers - Read this if your controllers are not working #### 

The original game is infamous for the compatibility issue for PS4/Xbox controllers if your computers are unlucky so it left the controller preference blank. 
Here's a valid workaround to this issue if you encountered it like us:

In Control Panel→ Devices and printers, find PS4 controller (usually labeled as "Wireless Controller"), 
right click "Wireless Controller" label to find controller setting, then click "advance..." to go into advance setting of "Wireless Controller", 
and be sure the "Wireless Controller" is checked as the preference.

The same could be applied to Xbox Controllers by repeating the setup above while your desired Xbox controller is plugged in.

If your controller is NS type we cannot guarantee if it works 100% (too much problems with the game's bottom structure) but we provided baseline support and NS type controller label anyway.



#### Read this if antivirus softwares flagged the game as Malware #### 

![LC1-2](https://github.com/user-attachments/assets/d0555db0-aa11-4a89-bd55-f248d3bd753c)


It's something about Clickteam's engine itself. Antivirus softwares don't seem to be too kind towards some Games used Clickteam's engine. 
If the problem that the antivirus softwares flagged the game as malware occurs, either turn off the antivirus software in question, or add the game to its white list. 
Also avoid directly sharing the zips or folder(s) which contain the exe file unless really necessary because some net drive safety calculation like Google's, don't seem to be too happy with the game.


#### Read this if your screen capture program did not work in Reworked LC1 #### 
Some capture programs will have compatibility issue with reworked LC1 on Windows 10 (for example, Ocam). This is because the compatibility issue of some revisions of Windows 10's Direct X9 mode. If you want safe screen recording methods, more mainstream programs (like OBS) will work.


#### Read this if you encountered framerate problem in fullscreen mode #### 
It's something about your setting of VSync under Direct X 9 mode. If your only graphic card is a Nvidia GTX graphic card, toggle VSync in your Nvidia control panel to "fast" or "on" if you encountered
frame rate problem in fullscreen mode.




### Update History ###

 #### [0.6.4] - 2025/10/14 #### 

`CHANGED` - Due to modern demands, have to change the post-hit flash effect on some very large enemies to something else that's not strong white, 
in order to reduce visual confusions, make flash-sensitive people to be able to get into the game easier.
Apologize if this breaks the consistency of style in the vanilla game. (Aceearly1993)  
`CHANGED` - Config: Due to requests, a cursor object had been added so that it's possible to navigate available key remap options like any other normal game, 
eliminated potential confusions on remap keys. (Aceearly1993)  
`FIXED` - A bug after 0.6.1 if controller is unplugged mid-game and proceed with keyboard input, then plugged the controller again, 
the controller will then be no longer be activated. (Aceearly1993)  


 #### [0.6.3] - 2025/9/18 #### 
 
`ADDED` - Config: Implemented on/off toggle for V-Sync and anti-alias. (Aceearly1993)  
`ADDED` - Config: A simple global volume control added. (Aceearly1993)  
`CHANGED` - Adjusted the timing of when the game can accept a secret code in order to prevent key overlapping on keyboard caused by inclusion of free keyboard mapping.  (Aceearly1993)  
`CHANGED` - Repurposed a secret code so that it can also offer another function in addition to instant access boss rush from a fresh save file.  (Aceearly1993)  
`CHANGED` - Adjusted events at the text introduction screen before the prologue stage and game over screen to fit the secret code.  (Aceearly1993)  
`FIXED` -  Inner Yard 2: A bug which a spider mid boss will drop a wrong whip upgrade upon a re-visit in extreme situation.   (Aceearly1993)  
`FIXED` -  Incorrect sound channel volume for most sound effects.   (Aceearly1993)  
`FIXED` -  A bug introduced after swapping the controller plugin which will cause Efrain to move much earlier than the vanilla game's logic should 
on some force-stop scenes if pressing Xbox D-pad.  (Aceearly1993)  


 #### [0.6.2] - 2025/4/12 #### 

`ADDED` - System Config: Now you can adjust windowed mode size and toggle full screen/windowed mode without having to tangle with LC2_KeyBinding.ini.  (Aceearly1993)  
`ADDED` - Slightly updated some notes on Readme file (Simplified Chinese).  (Aceearly1993)  
`FIXED` -  A bug which xbox d-pad is capable to move much earlier than the game's logic should when first introducing an area.  (Aceearly1993)  
`ADDED` - A variation of shopkeeper dialogue to make the conversation not too abrupt.  (Aceearly1993)  

Language variation of the dialogue in question:

English - Jeffrey Montoya  
French - Chernabogue  
Spanish - Jorge Fuentes  
German - Exorion Hagen  
Simplified Chinese - Aceearly1993 

`FIXED` -  Item pickup: in the pickup recognization system, when [multiple heart pickups of the same type/Variable were in the same spot and you touch 2 or more of them at once], 
the game will properly recognize each of them instead of only recognize once.  (Aceearly1993)  



 #### [0.6.1] - 2025/3/3 #### 

`CHANGED` - Basic Info so the info says "Reworked Edition" to better differ this version from vanilla.     (Aceearly1993)  
`CHANGED` - Katharina's quarter 3: Unrandomized movement timing of a Bone Dragon at the dark section near the exit of the stage, considering this dark section's difficulty.    (Aceearly1993)  
`CHANGED` - Re-organized control event as an attempt to fix a incompatible case of Xbox controller's D-pad.   (Aceearly1993)  
`FIXED` -  A bug which will cause the game to crash exit if unplug and replug the controller, then reset the game.  (Aceearly1993)  
`EXPERIMENT` - Changed Skeleton Gunman's behavior so that his bullet will now be a physical object instead of the bullet instantly reaches you as soon as he fires his gun.   
This change will have side effects so that the properties of his bullets will no longer be identical to vanilla.   (Aceearly1993)  
`ADDED` - (Very slight) Differences to Skeleton Gunman's bullet speed based on chosen difficulty.  (Aceearly1993)  
`ADDED` - Troubleshooting section if you encountered sudden crash exits for wrong reasons.  (Aceearly1993)  
`FIXED` -  An attempt to fix a irregular, bug-like phenomenon which the knockback animation will be incorrect if try to step on stairs 
while very close to an airbone enemy who's sticking to the air.  (Aceearly1993)  


 #### [0.6.0] - 2024/12/28 #### 

`ADDED` - A basic stationery rest stance if stay stationery for too long (beta).     (Aceearly1993)  
`ADDED` - Two more regulations in global event as an attempt to fix a bug that you'll occasionally lose collision to a platform if you flip down from a stair when the platform in question is right below the stair. (Not guarantee if the fix will work on every situation. Will revert the change if affected more in the structure of stair movement badly.)     (Aceearly1993)  
`CHANGED` - Properties for mirrors in Mirror boss fight in an attempt to fix a softlock bug, where Mirror boss may stuck in place and unable to be defeated after breaking a mirror he's supposed to enter, and you're forced to make Efrain suiside and retry in the next extra life. (Not guarantee if the fix will work. Will revert the change if affected more in the structure of Mirror boss badly.)    (Aceearly1993)  
`CHANGED` - Very slightly adjusted proportion and position of additional UI in a secret screen for better visual presentation.    (Aceearly1993)  
`HOTFIX` - Old Castle - Ruins 3: Very slightly adjusted height of a ceiling as an attempt to eliminate a reported cheap death capable to randomly happen when maximum jump height getting randomly raised by 1 pixel.  (Aceearly1993)  



 #### [0.5.9] - 2024/12/4 #### 

`FIXED` - Some typos in English language.   (Felipefpl)  
`FIXED` - Text object size in one instance at Spanish language (D3D11).    (Aceearly1993)  
`ADDED` - Ported a collision detection object from LC2 to reduce the possibility of a [stair climb collision correction] bug.      (Aceearly1993)  
`CHANGED` - Very slightly adjusted length of an initialization time at disclaimer screen to let player out of confusion in very extreme conditions.     (Aceearly1993)  
`CHANGED` - Stair movement: Now you're less likely to fail when attempting to jump onto stairs than how it was in vanilla.     (Aceearly1993)  
`CHANGED` - Because the [stair climb collision correction] fixes, an out of bound at Moonlight Hall part 2 will no longer work under human's button mashing speed.     (Aceearly1993)  



 #### [0.5.8] - 2024/9/14 #### 

`ADDED` - Availability of changing and saving controller labels (XBOX/D-input/PS).    (Aceearly1993)  
`ADDED` - Availability of mapping function keys to joypad's 11th and 12th buttons.    (Aceearly1993)  
`ADDED` - Disclaimer screen from LC2 demo versions.    (Aceearly1993)  
`ADDED` - Keyboard confirm/exit prompt label in a secret screen.    (Aceearly1993)  
`CHANGED` - The term "DEFAULT CONTROLS" to "CONTROLS" in control setting screen.     (Aceearly1993)  
`CHANGED` - "CONTROLS" event group into fully global event.     (Aceearly1993)  
`FIXED` - A bug which will cause text messages being clipped out of text box in certain endings.  (Aceearly1993)  


 #### [0.5.7] - 2024/8/8 #### 

`CHANGED` - Eliminated the strange design choice that system hotkeys had used up "Space" keys; More user friendly for Players whose personal preferences are getting used to assign jump to "Space" key.    (Aceearly1993)  
`CHANGED` - UI logic to fit the tweaks of Control Config function in title menu and system config screens.    (Aceearly1993)  


 #### [0.5.6] - 2024/6/13 #### 

`HOTFIX` - An attempt to fix a bug generated by controller plugin swap that will cause softlocks when touching the boss orb through jumping. (Aceearly1993)  
`FIXED` - A vanilla bug which will cause softlocks upon knocked to area transition through dying.  (Aceearly1993)  


 #### [0.5.5] - 2024/6/6 #### 

`HOTFIX` - An attempt to fix a bug at mirror boss fight in top floor.  (Aceearly1993)  
`HOTFIX` - An attempt to fix a bug on black panther enemy where corpse object of black panther may stack in loops in rare circumstances. (Aceearly1993)  
`HOTFIX` - Reported sound issues.  (Aceearly1993)  


 #### [0.5.4] - 2024/5/31 #### 

`ADDED` - Boss Practice as a function accessible through a secret screen.    (Aceearly1993)  
`CHANGED` - Logic of cursor speed in music room function so that it's easier to navigate.  (Aceearly1993)  
`HOTFIX` - A bug generated by controller plugin swap that will cause softlocks if hold downward, forward, special movement keys at the same time long enough when touching the boss orb through slide moves.  (Aceearly1993)  


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

`FIXED` - A bug (?) that caused efrain to automatically die when performing air float out of available camera zone. (Aceearly1993)  
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
- Jeffrey Montoya, Chernabogue, Jorge Fuentes - New dialogue's language variation
- Orx_ , 铃川千雪 , AngelKawaru , 浅野川 , 玛娜雷纳德 , lunatixxx - Test plays/bug hunters


... and all the people in game credits.


