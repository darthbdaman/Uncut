The Strip Open Readme
=====================
v1.4

By MoBurma
Original mod by Schizofriendlia

Overview
========

The Strip Open is an attempt to restore the Vegas Strip worldspace in Fallout: New Vegas to what was the developer's original intent; namely a large, visually spectacular open area. The Strip as found in the retail game is not the original plan for the area, and the checkpoint gates that make the area so clumsy to navigate are sadly a technical compromise - to quote Obsidian lead designer J.E Sawyer: "Memory problems caused crashing in both The Strip and Freeside, so they had to be split up". As you might expect, for these very reasons this mod is more demanding than the vanilla game, so users with lower end machines should tread with caution. The Strip Open should however run comfortably on most modern computers.

This mod is not an attempt to remodel or revamp the strip or to add new locations. There are many other mods with this goal, and users are encouraged to explore other options if that is their desire. The primary goal of The Strip Open is simply to recreate Obsidian's original vision for the strip, and to ensure the core game still has complete functionality despite these substantial changes. 

With this latest release I will boldly state that I believe the above aim is now achieved in this mod. Enjoy New Vegas as it was always intended to be.


What's New 
==========

v 1.4
-----

Revamped Tops Promoter characters so their dialogue/behaviours make sense, and to unlock previously inaccessible lines of dialogue:

- Fixed the first Tops Promoter's dialogue conditions so he can actually talk about Billy Knight now.

- Restored the cut second Tops Promoter and fixed his dialogue. He can be found watching the girls outside Gomorrah.

- Randomised the Promoter's topics. You can now hear their dialogue for BOTH the acts that either NPC promotes now. You can also now hear the spiel about the second of each one's acts if you'd gotten the first one before, which would make it impossible to hear those lines in the vanilla game. 

- Changed Tops Promoter Behaviour. They are now disabled until the player has recruited their respective acts to promote. They will also now actively engage the player in conversation to promote their acts. This will happen once a day when you enter into their triggers unless you tell them to go away and then they will stop doing this. This seems to be more inline with how they were originally intended to work in the game.

- The first promoter will now always make a comment to the player when you pass their trigger once a day. This is just a sayto line so shouldn't be too obnoxious. The second promoter however, will do the same, but will start a full conversation once a day if the player triggers it. To stop this behaviour, just say to him "stop bugging me". This will reset when you get his second act on board, and you must tell him to stop bugging you again.

- Restored an unused line of dialogue from one of the MPs during the drunks sequence.

- Rebuilt LOD for the Strip worldspace. This means the removed gates will no longer appear at a distance.

- Removed Monorail station upgraded securitron stuff, and moved it to my Outside Bets mod where it seemed a better fit.

- Rejigged Securitron AI packages. They will now patrol different sections of the strip instead of just standing around.

Installation
============

Simply extract all files from this archive to your FalloutNV/Data/ directory. click the "Data Files" option from the game's loader and tick the box next to both NVStripOpen.esm and StripOpenMain.esp.
Ensure that the file NVStripOpen.esm is higher in the load order than StripOpenMain.esp, e.g.

NVStripOpen.esm
StripOpenMain.esp

For best results, simply use the Fallout Mod Manager (FOMM) package installer.

If upgrading from a previous version, you MUST delete StripOpenNPCs.esp from your falloutnv/data directory.

IMPORTANT
---------
Although you can install and enjoy this mod at any point in the game, it is HIGHLY recommended you do so only with new games/games where you haven't yet reached the strip. Although you will be able to fully complete the game and any Strip related quests if you install the mod halfway through a game in progress and in which the strip has already been visited, you will likely experience minor glitches such as scripted scenes not playing back correctly/at all if you do so.


Known Issues/Bugs
=================

- The NCR drunks in the initial scripted scene may occasionally spin around on the spot and behave erratically. This is hard to fix and is due to them not adjusting to new waypoints well when doing their drunk animation.

- If you use non-vanilla map markers (e.g. lucky 38 marker mod) as your sole transport into the strip you will not see scripted sequences. Most of these sequences are tied to triggers in the area next to the Freeside gates or the station, so try and leave/enter by these routes every now and then if you want to see the scripted scenes.

Reporting Bugs
--------------
 
Please post bugs in the Strip Open discussion topic on the Nexus forums. Please note that little attention will be spent on fixing bugs that occur from using the mod halfway through a game underway, or from upgrading from a previous version of The Strip Open. You should ideally use this mod only on a new game.


Version History
===============

Note
----

As of Version 1.0 this mod is now developed by MoBurma (moburma80 on Nexus forums). All versions previous to this were developed by Schizofriendlia (TheQuickness on Nexus forums), and the bulk of the work is indeed his. The Strip Open is also based on work by Tarrant who created the original NVStripOpen.esm this mod is based on.

Older Versions
--------------

v 1.3

- Further aesthetic improvements. The area around the Ultraluxe and Vault 21 has been revamped with the former out of bounds rubble piles removed and some cars added to the derelict parking lot. New navmesh created for the above.

- The end Tops casino front door now works properly, and the guard rail is disabled.

- Stupid problem with the station vendor finally fixed. Unfortunately this might cause you to have two vendors if you've been using the mod previously.

- The monorail station securitrons will now upgrade to MKII. This will only happen, however, if you've yet to see the Securitron upgrade sequence. Otherwise they will be stuck as MKI still.

v 1.2

- Moved NPC markers so people no longer fade in/out in the middle of the street. The effect is still visible if you know where to look, but it should be much less obvious and less immersion breaking now.

- 4 new "fluff" NPCs added to the area around the Ultraluxe to make that area seem more lively. Might result in a slight performance drop.

- Cleaned up some ugly looking terrain, specifically the misaligned road piece near Gomorrah and the floating palm trees and litter by the Ultraluxe.

v 1.01

- Bugfix release to fix gamestopping bug on Yes Man questline. 


v1.0:

With this release all core game functionality within the strip should be complete. 

- All Scripted special event sequences (e.g. girls in fountain, Brahmin loose on strip) now play to completion.

- Added logic to scripted events that share actors so only one plays at a time.

- Enhanced some of the scripted sequences to use the new space. Now the NCR drunks actually walk all the way to the monorail station to get home, and the escaped Brahmin runs the length of the strip and into the embassy area to hide it fading out. 

- The Station Vendor should be present and never disappear/teleport about the place anymore.

- The Tops Promoter likewise should be present and stay put.

- Walter and Ethel Phebus should now walk over to the station benches and sit down.


Alpha.v8:
Used new NPCs in in the persistent middle area of the Strip, and now uses the original NPCs in the North/South areas
Moved the middle zone triggers to disable them for the time being
Players will no longer see an entire area of NPCs spawn in front of them

Alpha.v7:
Added a separate group of "fluff" NPCs which teleport between the North and South areas
Removed the NPCs in the middle area from the scripts that previously teleported them North and South
(This should make the transition between areas less noticeable but may cause lag)
These NPCs are not added to all of the Scripts and so will not stumble drunk.
Some scripted scenes may overpopulate the North or South areas.
(Again, let me know if/when you experience heavy lag with this)

Alpha.v6:
Fixes issues v5 caused with the Securitron upgrade demonstration.

Alpha.v5:
Added a noticeable amount of NPCs (5-7) to the center area of the Strip between the Tops, LVB Station, and the Ulta-Luxe. For the moment they are only sand-boxed (idle movement, sitting, smoking, walking in small circles, etc.) because they are for testing purposes.

Alpha.v4:
Fixed issues with Securitrons. They should populate the area correctly now. I hope.

Note: The triggers are smaller between areas of the strip now. I shrink them when testing things and just remembered that I didn't enlarge them again. Will appear to cause problems if you don't like running on the actual street.

Alpha.v3:
Fixes a few minor problems that were causing a few of the scripted scenes to not appear properly.
Removed the moveTo tags associated with Securitrons during combat. They should no longer teleport at seemingly random times while moving through the Strip.
Securitrons now should be spread out more appropriately through the Strip. There should be 8 total, 4-5 of them should move as you do.
Fixed a few overlooked scripts that would cause quest NPCs to disappear as the player moved to the North or South areas of the Strip.

Alpha.v2:
Fixes the South Area activator so that players actually will trigger the NPCs to be moved correctly.

Alpha.v1
Using Tarrant's The Strip Open - Modder's Resource I made as few changes as possible to get it in a workable state.

Modified and tacked the gate scripts onto cubic activators
- This moves the NPCs around as you move through the Strip to populate the areas as they (almost) normally would be.
Enabled a few quest NPCs like Billy Knight
- This is in an effort to make sure it is in fact usable, even if my triggered scripts don't work correctly for some reason.
Moved a few things that didn't look quite correct
- Most notably the wrecked bus to the left when you enter the Strip area

Credits
=======

Original mod by Schizofriendlia
Version 1.0 By MoBurma
Based on Strip Open Modder's resource by Tarrant

Licence
=======

This file is provided as is and the author holds no responsibility for anything that may come to happen from using this file.

You may use this mod as a basis for derivative works, but it is enouraged you give credit and ask permission first.