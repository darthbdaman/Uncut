New Vegas Uncut : Outside Bets
==============================
v1.4

By MoBurma


Overview
========

Outside Bets is the latest in the New Vegas Uncut series of mods. The primary aims of the mod are to restore and collate minor pieces of cut content that would be too small to demand their own seperate mods, to restore all the NPCs removed by Obsidian's patching process, and to fix a few minor bugs that prevent content in the vanilla game from working correctly.
 This mod restores a number of cut scenes and scenarios that were left unfinished in the game code. These include sequences involving Mr House and the Lucky 38, Camp forlorn Hope, the 188 Trading Post, and more. Since the original retail version of the game, successive official patches to fix bugs have also removed a large number of unimportant NPCs primarily to keep console saved game and memory issues to a minimum. Pc players have far less restrictions on these counts, so this mod takes advantage of more powerful hardware to deliver a more interesting game experience based on what was once in the game but since removed. For a full list of things that have been restored, check the version history.

Selected mod Features of interest:

Lucky 38/Mr House
-----------------

Restored - Mr House will now taunt/attempt to reason with the player during their attack on his control room, or if the player has destroyed the Fort Securitrons and enters the Lucky 38.

Restored - Victor will now confront the player in the Lucky 38 if the fort Securitrons are destroyed for one final duel.

Restored - The player will now be warned to stay away from Mr House's secret room terminal.

Restored - Upon his death, Mr House's obituary message will be broadcast in the Strip, explaining how everyone knows he is dead.


Camp Forlorn Hope/Nelson
------------------------

Restored - Random battles now once again take place in the no-man's land between camps.

Restored - Maimed and booby-trapped NCR troopers can now once again be found in the no-man's land between camps.

Restored - a huge number of NPCs that were disabled in both camps. Attacking either side will now be more difficult.

Restored - Post attack events. If 'We Are Legion' is successfully completed, The Legion storm the camp and kill anyone left, and dump the bodies in a mass grave in the graveyard. After two days it will then be infested by Cazadores. Nelson will now actually be occupied by NCR troops if they take the location back.


Camp McCarran
-------------

Restored - Camp McCarran now has a unique sentry bot that patrols the perimeter.

Restored - Huge number of disabled NCR guards on the walls.

Restored - Obstacle course troopers and drill sergeant

New feature - There were leftover push up markers clearly intended for NCR troops. They are now used by new troops and a new drill sergeant.

El Dorado Substation
---------------------

Restored - Completing this stage of the Yes Man or House main quests will now lead to a previously deleted scene where the player watches the Lucky 38's lights turning on now the reactor is restarted.

Misc
----

Restored - MANY (we're talking triple figures) disabled NPCs and enemies restored.

Fixed - Securitron dialogue now plays correctly, unlocking the missing 2/3rds of their dialogue that could never be played before due to various condition errors and the absence of the "random" function on their lines.


What's New 
==========

V1.4
----

- Restored Cass' Whiskey Rose perk barks. She will now make a comment when the player drinks whiskey in her presence as was originally intended.

- Fixed combat barks for Omertas, Fiends, Boomers, Followers of the Apocalypse, Super Mutants.

- Fixed up a few companion combat barks that weren't randomised

- Mr House's "introduce yourself" dialogue will no longer play if the player has failed House's questline.

- Restored lots of disabled Boomers in the mess hall at Nellis.

- Restored an unused Boulder City Worker. He has a single unique dialogue line.

- Moved Meyers speech to take place closer to Primm. This should be less disorientating and hopefully more compatible with mods that add more enemies to the game.

- Fixed bug where the objective to follow the Securitron to watch the Lucky 38 relight would not be marked as completed on the Yes Man questline.

- Gave cut note to Black Mountain NCR trooper.

- Restored all NPCs watching the President's speech at Hoover dam.

Installation
============

Simply extract all files from this archive to your FalloutNV/Data/ directory. click the "Data Files" option from the game's loader and tick the box next to outsidebets.esp


Known Issues/Bugs
=================

- The 'Trooper gloves' add on for the ADAM mod will cause the maimed troopers in Camp Forlorn Hope's no man's land to have freaky floating hands. It's therefore recommended not to use it with this mod.

- Some of the restored NPCs will NOT be visible if you have already been to the area in an existing game. I've tried to tie re-enabled NPCs to markers to guarantee they appear, but this isn't always possible.

- Some of the mercenaries at the 188 trading post may be wearing the wrong armour. This is a weird vanilla game bug where the game doesn't like having multiple characters wearing certain identical pieces of armour and forces one of the wearers to have something else. I might change what they are wearing later to get around this.

- The maimed troopers can sometimes get up if they get involved in the random battles at Forlorn Hope.

- 188 beggar may have the wrong body skin tone compared to the face. This is an old vanilla game bug but I don't really want to make this mod an .esm which would fix it. There's another way of fixing it by fiddling with your .ini files if you're that bothered. Just pretend the dudes' got that thing Michael Jackson had (no, not a sick affinity for little kids).

- If you are using the current release of Freeside Open (0.5) or older, then Emily Ortal's new greeting will fail the dialogue check once she is back in the Mormon Fort. This will be fixed in the next version of that mod.

- If you use a weather altering mod that causes cloudy/low visiblity conditions then you may not be able to see the Lucky 38 during the restarting the reactor scene.


Reporting Bugs
--------------
 
Please post bugs in the Outside Bets topic on the Nexus forums. 

Version History
===============

v1.3
----

- Restored several cut Arcade dialogue lines: There is a new line if he is in your party during 'The Moon Comes Over the Tower', as well as two new lines if you listen to ED-E's logs in his presence (these also change depending if you know about his background or not).

- Fixed faction combat barks. Much like the Securitrons these were botched so that only a fraction of them actually worked. The Legion in particular will now say a lot more stuff in combat.

- Retroactive fixes. Some of the stuff restored by this mod would be missed if the player had already gone past the point where certain variables were set. On installation there is now a new script that sets these variables if you've gone past the point in the game where they should have been set (e.g. knowing about Arcade's past).

- Moved Monorail station securitron stuff over from my Strip Open mod. The Securitrons in the Monorail will now upgrade to MKII along with the other Securitrons in the game now.

Primm overhaul. Big changes have been to this location to restore cut content and make it more interesting/coherent:

- Restored Lieutenant Hayes' conversation with McGee. The first line of this conversation is actually missing in the game files, but it works well enough. 

- Restored NCR and Powder Ganger deputies. Also changed their patrol routes to use the unused ones set up in town. Why would ex-powder gangers be patrolling inside the NCR base? I left some of the NCR deputies on their vanilla game patrol routes, as one of the ways the player can convince the NCR to help is to point out that protecting the road would have other benefits for the NCR. It therefore makes sense that they don't dedicate their entire force to actually helping Primm. This also adds to the characterisation of the NCR as well meaning but not necessarily "good" - the town have to pay extra taxes yet gets screwed on the actual level of protection!

- Fixed up Sheriff state values. There are two values for this, one that sets which sheriff has taken over, and another that sets whether or not a sheriff is in charge. It's clear that someone got confused which was which, as the NCR in charge value is never set, but its value is often used in the sheriff state value, meaning lots of people cannot/wrongly comment on which faction has actually taken over Primm. Based some of this on Paul_NZ's "Primm Rumours Fix" mod.

- Gave Primm Residents new AI packages. Packages were set up to make them walk around the town during the day, but were never used. They are now actually used, along with some new ones I created so they randomly walk about outside/in their individual houses, and also go to sleep in their own houses.

- Removed Dead sheriff and his wife's corpses when the town is taken over for all outcomes. Previously they were only cleaned up if Primm slim took over, even though he'd probably be the candidate least bothered by there being dead people in his "house".

- The Ex-NCR troop corpses will now be disabled if you re-enter the casino after they are dead. 

- Setup the corpse of the dead courier Daniel Wyand to disappear once the player has removed the note from his corpse and completed 'My Kind of Town' (they go to the effort of shipping troops in from miles away and yet no one thinks of burying this poor guy?).

- Added some gamblers to the Vicky and Vance once order is restored to Primm. 

- There were some dead Primm residents setup but unused. I put them in front of the Vicky and Vance on the blood stains there to further emphasise the danger the townspeople are in. Their corpses will disappear once the Ex-NCR troops are dealt with and the town prospers again.

Some gameplay changes ported from a file sent to me by Ancestralghost:

- Great Khan Melissa will now leave the Quarry and return to Redrock Canyon as she tells you she will. 

- The random Legionaries assaulting Camp Forlorn Hope will now drop ears on death.


v1.2
----

- Restored cut scene on the Yes Man and Mr. House questlines when the player reactivates the Lucky 38's reactor. After activating the El Dorado substation terminal, you will now be directed to follow the nearby securitron to watch the Lucky 38 light up.

- Restored Nelson dead NCR troops.

- Restored Nelson extra Legion soldiers.

- New events at Nelson - If Nelson is recaptured by the NCR, there will now be NCR soldiers occupying it. Once this has happened, the guard tower soldiers will also be replaced with Rangers at the appropriate time in the game's story.

- Restored Vulpes Enculta's extra dialogue that couldn't be seen due to impossible dialogue conditions. Also restored some of Gabban's lines that were similarly botched.

- Conditionalised the McCarran push up troopers. They will now not appear during the entirety of the quest 'I Put A Spell On You' in order to avoid getting in the way of certain important NPCs during that quest.

- Disabled Turret in Mr House secret room until the room is breached to work around aggro radius problems.

- Restored intended Emily Ortal functionality. She will now return to Freeside Mormon Fort once the Lucky 38 is bugged, with a couple of new lines of dialogue. She will also now only be disabled if the player has not completed the quest 'The Moon Comes Over The Tower' after killing Mr House (previously she was ALWAYS disabled once/if he died). Finally, she will now sandbox after bothering the player twice about bugging the Lucky 38, including going to sleep in the Vault 21 hotel where she claims to be staying (yet never goes anywhere near in the vanilla game).

- Set Legion Sniffer dogs to no longer respawn (this made no sense in the vanilla game).

- Fixed Camp McCarran push up trooper sometimes wandering about.



V1.1
----

- Enabled sleeping Forlorn Hope Troopers.

- Restored Forlorn Hope events: If We Are Legion is completed, then on the player next returning to the camp everyone will be dead and dumped in a mass grave in the graveyard (it's assumed after the Player weakened the camp by eliminating the leaders the legion counter attacked and massacred everyone). After a further two days the area will be invaded by Cazadores. This event will be prevented from happening if the player wipes out the Legion at Nelson as well.

- Added Camp McCarran Sergeants to NCR faction so everyone aggros if you kill them. 

- Fixed one of the Westside WhiteWash thug's position so he no longer plummets out of the air on spawn. 

- Added failsafe to Victor during final confrontation so that if the player kills him before his speech is done the other Securitrons will still start combat.

- Restored Lucky 38 warning message on breaking into Mr House's secret room. Massive thanks to RJHelms84 and the talented Pippa Winslow for voicing this.

- Fixed Elevator Victor not disappearing once Mr House is dead. 

- Fixed vanilla game oversight of Strip Victor not disappearing once the Fort securitrons are destroyed.

Lots of cool stuff thanks to Xporc of Fook fame, including:

- Restored dialogue for Jack at Nellis if Janet is killed.

- Restored Extra dialogue for Arcade explaining about his past.

- Re-enabled Hoover damn exhaust water.

- Restored LOTS (more than 50) more disabled NPCs and low level enemy spawns.

- Of particular note of the above, restored lots of enemies and disabled Nightkin ambushes at Black Mountain, as well as TONS of enemies at Camp Searchlight.

- Restored Motorrunner Donnie & Marie Wild Wasteland encounter.

v 1.0
-----

- First version. 

- Re-added 188 Trading post NPCs. Includes pessimistic and optimistic NCR citizens, mercenaries, brahmin and extra NCR troops. 

- Sorted out 188 sleep package and corresponding marker to make more sense and apply to more NPCs.

- Rejigged dialogue and set up a new dedicated destitute beggar at the 188. He will ask the player for caps, and upon receipt will not ask for more until a day has passed.

- Fixed 188 misplaced smoke trail on barrel.

- Sorted out 188 idle markers that caused NPCs to sink through the walls.

- Re-enabled cut Sharecropper farmers.

- Re-enabled cut Westside farmers.

- Restored cut scene with Westside thugs if you follow Hector into the water cistern during 'The White Wash'.

- Added new ai packages to disperse the above thugs if peacefully dealt with.

- Restored some Fort NPCs.

- Fixed Caesar's Legion slave dialogue.

- Re-enabled Camp McCarran NCR external tower snipers.

- Re-enabled Camp McCarran obstacle course soldiers.

- Fixed broken Drill sergeant dialogue for above.

- Added some soldiers to the previously unused Camp McCarran push up markers, as well as an extra drill sergeant.

- Re-Added Camp MCCarran Sentry bot.

- Re-enabled Aerotech park NPCs/Traders.

- Restored Bert Gunnarson's extra dialogue.

- Restored random battles in Forlorn Hope's no man's land and added cleanup code for dead troops.

- Restored dying NCR troopers in Forlorn Hope no man's land.

- Re-enabled NPCs around Camp Golf.

- Created missing lip sync files for Colonel Moore during her Presidential speech.

- Fixed Securitron dialogue so now Strip securitrons can say all the dialogue they are supposed to.

- Restored: On the player's first visit to the Lucky 38, Mr House will now ask the player to come over and talk if they explore his Penthouse without speaking to him.

- Restored: The Securitron near the terminal to Mr House's secret room now warns the player to step away if the terminal is approached.

- Restored Ceiling turret in Lucky 38 secret room.

- Restored: Mr House will now taunt/plead with the player once his secret room has been breached, or if the Courier has destroyed the Securitrons at the Fort and then attempts to enter the Lucky 38.

- Restored: Victor's final confrontation with the player if the Fort Securitrons are destroyed.

- Restored: Upon his death, tannoys in the Vegas Strip will now broadcast Mr. House's obituary message once daily for a week.

- The player will no longer automatically receive an obituary leaflet if Mr House dies. Instead they will have to get one from a Securitron as instructed.

- Redid cut Mr House dialogue so it is now in stereo thus audible anywhere, and now has the intercom/tannoy effect where intended. The only downside is the bitrate/quality is a little low due to having to work with the already low bitrate game files.



Credits
=======

Mod by MoBurma
Big thanks to Xporc for sharing his findings from FOOK.
Pippa Winslow as the voice of the Lucky 38 alarm.
Based on original code by Obsidian

Licence
=======

This file is provided as is and the author holds no responsibility for anything that may come to happen from using this file.

You may use this mod as a basis for derivative works, but it is enouraged you give credit and ask permission first.