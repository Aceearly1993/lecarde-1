## Description
A portion of source code of the fan-game Castlevania: The Lecarde Chronicles (1) made by Migami Games. Due to a HDD failure, the original source have been lost. This repo is an atempt to preserve, fix and improve this game.

Unfortunately, the recovery process ended up corrupting all non-English characters, many transparency effects and more. So, if you know any of the following languages and is interested in helping us out by fixing and re-translating this project, feel free to contact us, we are in need of:
- French fix
- Spanish fix
- German fix
- Somebody who're good at reverse engineering datas
- Somebody who're both very good at using **Multimedia Fusion 2 Developer** (The version before the engine is updated into Clickteam Fusion 2.5) and a good French speaker


## Disclaimer
This project can be considered like a yonger brother of the LC2 project that I (Aceearly1993) was actively involved: (https://github.com/katriellucas/lecarde-2) so most things are also appled here:
We contacted Migami Games and got approval to keep this repository up.  

The release of Lecarde Chronicles (1) got permited by Konami, the game and its assets are freeware and **_SHOULD NOT_** be sold, this also includes the source code. Any modifications you do have also to be free. Castlevania is an intelectual property owned by Konami, please support the company by buying their official releases.


## Usage
To get the base source code, go to "Releases", choose either one of the two "v0.0.0" tags or the "event-code" tag and find the packed files. 

The one labled "v0.0.0-compressed" is the fresh dump of core files in LC1's .exe, archived for preservation purpose.
Only the "ctlc data d" is the main deal but the contents from other 3 small .exe in the original game pack are also archived in case if there's anything missing.

The one labled "v0.0.0-resaved" is an alternate backup of the .mfa, resaved through Multimedia Fusion 2 Developer and preserved for archive purpose.

The one labled "event-code" is the new event-code only .mfa which preserved only event and behavior codes for better stability and visibility (The unpacked .mfa is not very stable in the engine and tend to crash)


Here's a simple instruction about using the .mfa: 

- Unlike LC2 (https://github.com/katriellucas/lecarde-2), LC1's structures are not that compatible with Clickteam Fusion 2.5. Preferably, it should be opened on **Multimedia Fusion 2 developer** versions of the engine (The version before the engine is updated into Clickteam Fusion 2.5).
- You'll need to install every extensions and runtimes possible at that time in order to open the .mfa without crashes.
- A large portion of the graphics were corrupted due to reverse engineering and as a result every single scene might have to be rebuilt from scratch. But luckily 70% of the event codes were preserved in a new event-code only mfa. It's recommended using the new mfa as a basis if any potential MMF2 developer want to tackle this task because the unpacked mfa has issues caused by unpacking corruption.
- If any potential MMF2 Developer successfully grappled the clue of LC1 recover, please swap out some of the free music sample from sample sites and some of the effects resembles capcom sound effects, because the vanilla game had been targeted by DMCA as copyright infringement material for some unspeakable reasons the group/individual claimed the DMCA refused to show up and explain.
- By saying "not that compatible with Clickteam Fusion 2.5" it doesn't mean the resaved mfa is dead impossible to open in CTF2.5. Although the chance is super rare and is not guaranteed. If any potential MMF/CTF2.5 developer has more than 16G of RAM on their machines, they could _try_ opening the mfa directly through CTF2.5.

The last one labled "CTLC1-assets" is all the graphic and sound assets necessary when somebody grappled the clue of recovering the game (most of the "frames" are broken)
NOTE: sound files may contain copyright infringement materials because the game was caught by a DMCA request in 2018. Need further investigation to define which one belongs to them and then changed them to something else. 
