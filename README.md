# AzerothCore Challenge Modes v2
** v2 Revised Additions by https://github.com/AzoraNova ** 
Original project by https://github.com/ZhengPeiRu21 

		

		
This module adds the following challenge modes:

 - ** Hardcore Challenge ** - Players who die are permanently ghosts and can never be revived.
 - ** Semi-Hardcore Challenge ** - Players who die lose all worn equipment and carried gold.
 - ** Self Crafted Challenge ** - Players can only wear equipment that they have crafted.
 - ** Item Quality Challenge ** - Players can only wear equipment that is of Normal or Poor quality
 - ** Half XP Gain Challenge ** - Players receive 0.5x the normal amount of XP.
 - ** Very Low XP Challenge ** - Players receive 0.25x the normal amount of XP.
 - ** Quest Only XP Challenge ** - Players can receive XP only from quests
 - ** Iron Man Mode Challenge ** - Enforces the Iron Man Ruleset harder then Hardcore Challenge  
 ** All Modes get a prize set in Config ** 


  ** DEATH KNIGHTS ** - Can only do these Challenges 
  - Hardcore Challenge
  - Semi-Hardcore Challenge
  - Half XP Gain Challenge
  - Very Low XP Challenge
  - Quest Only XP Challenge
  
  
Challenges can be activated per-character by interacting with the Shrine of Challenge (eagle statue) added near the graveyard of each starting area.
Challenges can only be enabled on characters at level 1 (or level 55 for Death Knights).


Rewards for reaching level thresholds for each challenge can be added using the Config file, and can include:
- Items
- Titles
- Talent Points
- Increased XP Rate
* Some Preset items are set for level 80 in config


Please note that this module uses Player Settings to store enabled challenges, so please ensure EnablePlayerSettings is set to 1 in your worldserver.conf.


-- Revised Additions --

** Whats new in AzerothCore Challenge Module v2 **

   Core Changes:
   * All Challenges are Duel locked to players of the same Challenge
   * Added in checks to confirm player must be level 1 or 55 if a death knight 
   * Players can only do one Challenge per player
   * Checks players for cheat items on Login and on start of Challenge 
   * Changed how death checks and Ghost mode is done in Hardcore/Iron Man 
   * All over server get alert message when player start's Challenge (or killed in Hardcore/Iron Man)      
   * DuelRequest checks added to Challenge players
   * DuelRequest can only be done if player is in same Challenge no level cap on it 
   * Changes made to detect a PVP death over a PVE one and shows a message of death
   * Made custom message function to be Raid Like color Message (to player only)
   * Made Custom messages that are random on Challenger Death/Resurrect
   * All Players who die now get Resurrection Sickness if in a Challenge
   * Alot code to make it work :)
  
 
  
   Hardcore Changes: (One life only)
   * Login Message let's players know they are in a Challenge
   * After death player can stay in Ghost form but not revive
   * Changes made to detect a PVP death over a PVE one and shows a message of death
   * Resurrect will kick player to login
   * Battleground check added to block use of Battleground
   * Death messages show to all now



   Semi-Hardcore Changes:
   * Login Message let's players know they are in a Challenge
   * Changes made to how player equipped items are lost in death with message  
   * Battleground check added to block use of Battleground
   * Resurrection Sickness after death
   * Items equipped are lost and loss of all funds on death   


   Self Crafted Changes:
   * Login Message let's players know they are in a Challenge
   * Player gear is checked on Login - cheating Checks items destroyed if found
   * Resurrection Sickness after death


   Item Quality Changes:
   * Login Message let's players know they are in a Challenge
   * Player gear is checked on Login - cheating Checks items destroyed if found
   * Resurrection Sickness after death   


   Half XP Gain Changes:
   * Noraml Game mode other then Half XP and prize at end
   * Login Message let's players know they are in a Challenge
   * Resurrection Sickness after death  
 
 
   Very Low XP Changes: Mostly same just less XP
   * Noraml Game mode other then low XP and prize at end
   * Login Message let's players know they are in a Challenge
   * Resurrection Sickness after death   
 
 
   Quest Only XP Changes:
   * Can only get XP from Quest and prize at end
   * Login Message let's players know they are in a Challenge
   * Resurrection Sickness after death   
 

   Iron Man Changes:
   * Player gear is checked on Login - cheating Checks items destroyed if found
   * Login Message let's players know they are in a Challenge
   * After death player can stay in Ghost form but not revive
   * Changes made to detect a PVP death over a PVE one and shows a message of death
   * Resurrect will kick player to login
   * Battleground check added to block use of Battleground
   * Honor check added to block Honor points 
   * Reputation checks added to block Reputation Gain   
   * Death messages show to all now

 




Enjoy the Revised Additions I put together and Remember
“Open source is about collaborating; not competing”


If want to you can buy me a coffee here:
https://buymeacoffee.com/azoranova - AzoraNova 

