#SimpleTrade (1/19/25)
------------------------
Trade value scripts that will track Under Ocean trading as well as land trading.
Install: Use Mudlet Package Manager to Import SimpleTrade.mpackage
Commands:
simpletrade - help file if you forget all else, remember this
valstart covered - will get values for covered on land posts
valstart snail UO - will get values for snail underocean posts
valstart covered UO - will get values for UO, but covered wagons UO may not work out
valstart - alone does nothing "Thou must be confused."
showtp - will open a window that shows values
hidetp - hides the window, you can also unlock window and exit


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


