# TargetAssist

## TargetAssist by Kronos

Targeting and Alias package
- Allows you to set multiple modes for your alias so you can quickly switch between.
- Allows you to create two targets that your alias can focus on.

Target Assist by Kronos
Allows for user to create alias modes and targets
targetassist - for list of commands
tmcreate - create a new mode
tmdelete - delete a mode
tmset - sets a modes alias for CURRENT mode (tmset 1 c magic missile)
tm - change mode (tm mage)
tmshow - show modes, targets, and save directory
tt - set a target (tt Kronos)
Use 1-9 to attack your set target 1. Type 1, 2 3, etc
Use 11-99 to attack your set target 2. Type 11, 22, 33, etc

*Installation
In muddlet open Package Manager and read this package.
No dependancies.
It will work with CPC for those using multiplay.



#SimpleTrade (1/19/25)
------------------------
Trade value scripts that will track Under Ocean trading as well as land trading.<br/>

Install: Use Mudlet Package Manager to Import SimpleTrade.mpackage<br/>

Commands:<br/>
simpletrade - help file if you forget all else, remember this <br/>
valstart covered - will get values for covered on land posts<br/>
valstart snail UO - will get values for snail underocean posts<br/>
valstart covered UO - will get values for UO, but covered wagons UO may not work out<br/>
valstart - alone does nothing "Thou must be confused."<br/>
showtp - will open a window that shows values<br/>
hidetp - hides the window, you can also unlock window and exit<br/>
(you can value trains, mules, covered, etc..)



# MedMudlet  (INTEGRATED IN Kymbahls's MedUI Package)

**** Med Mudlet UI ****
-----------------------
This folder contains a package with all of my packages built into a single package.

Use Mudlet Package Manager to Import (IN THIS ORDER):
1. MDK
2. EMCOChat
3. MedMudletUI

- You may need to type: lua resetProfile()
   > This will get packages to find dependacies and fix any errors that may have happened. 
- A green window gets loaded from the EMCOChat as an example that you should close.
- The map/chat windows can be moved if you right click and unlock them. 
- MMCP needs more scripts to be added to work. I haven't added it into my libraries yet.

1. Med Mudlet UI
   https://github.com/berood001/MedMudlet/blob/main/MedMudletUI_v1_0_April2024/MedMudletUI.mpackage
2. MDK
   https://github.com/berood001/MedMudlet/blob/main/MedTabbedChat/MDK.mpackage
3. EMCOChat
   https://github.com/berood001/MedMudlet/blob/main/MedTabbedChat/EMCOChat.mpackage


**** Medievia Tabbed Chat **** (INTEGRATED IN Kymbahls's MedUI Package)
-------------------------------

You need to download and import 3 packages using Mudlet Package Manager.

1. MedieviaTabbedChat
   https://github.com/berood001/MedMudlet/blob/main/MedTabbedChat/MedTabbedChat.mpackage
2. MDK
   https://github.com/berood001/MedMudlet/blob/main/MedTabbedChat/MDK.mpackage
3. EMCOChat
   https://github.com/berood001/MedMudlet/blob/main/MedTabbedChat/EMCOChat.mpackage
   
Chat windows are in adjustable containers that can be unlocked and moved around.
If something gets messed up.. it happens sometimes when moving around containers.
use "lua resetProfile()" normally fixes things.


**** Medievia Buffs N Bars **** (INTEGRATED IN Kymbahls's MedUI Package)(OUTDATED WITH GMCP ADDITION)
--------------------------------
https://github.com/berood001/MedMudlet/blob/main/MedBuffsNBars/MedBuffsNBars.mpackage
Version 1.2
- Tracks status bars to include HP/Mana/MV/BR.
- Has a buff tracker with icons to track your current buffs.
- Missing plague, curse, striking, mal
- Phan Images buff may drop while an image is still up. The game output is a bit wonky trying to track images that are destroyed.

Note:
You can sync buffs by using "SC" or "SC A". A script will clear all buffs in tracker and add them again. Useful if you disconnect while a buff falls off and you reconnect.

Future:
- Going to add alias to allow players to move the buff tracker and gauges where they want.
- Going to attempt to add timers that will highlight buffs that are fading. Somewhat difficult since different level spells have different timers. It will probably just work for heros at first.

If you see issues send Mudmail to Kronos, or ping on Discord.


