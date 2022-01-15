# SWAT ELITE FORCE: FIRST RESPONDERS #

SEF First Responders is coming along with the idea of a realistic and cinematic gameplay modification of Swat Elite Force. 
SEF 7.0 by Eezstreet is the base mod in which my mod starts , the only possible way to play Swat 4 nowadays. 
My idea is to expand the concept and explore boundaries of the visual assets and tactical gameplay.
New 3d models for weapons , equipment and environment combined with realistic sounds , weapon handling , slower pace gameplay and AI tweaks to make Swat 4 feel more "heavy" and "dangerous" than any other Swat 4 experience you had before.

Make sure to sure to join "SEF: First Responders" server on Discord for feedbacks, bug reports and coop game making!
https://discord.gg/Vu4r7sv7uF


# FEATURE LIST: #

#### V0.66 ####

ADDED:

	GAMEPLAY:
			- Lean/Walk System , ability to lean and walk.... finally an hystoric moment for Swat4 modding!  
				New and old lean system are working together for a complete... lean experience! 
				Q and E - new lean/walk system 
				CTRL + Q and CTRL + E - old lean 
			- Partial Open Door System , holding CTRL and Mouse Wheel Up/Down wil swing the door partially, making possible to shoot or throw a grenade.
			
			- NEW TAC-AID: Maglite Torch! Using the light makes evidence glowing to allow player a faster search of them. Even AI can use this feature when got ordered to secure evidence!
					J to equip torch 
					Toggle Flashlight to highlight evidence
			- Disable Penalty Messages option for SP (in game settings options) and MP (forced to all players in Advanced server settings )
			- Fleeing suspects are considered threat if running with a gun within 15 mts from a player 
			- Restored Weapon Zoom (disabled by default). 
	AI:
			- Suspects and officers can punch their enemies at very close range! 
			- Suspects AI morale overhaul , now 15% more intiale morale.They can also "fake" dropping all weapons and decide to attack you with a chance based on skill level.
	
	GRAPHICS:
			- NEW OFFICERS TEXTURES (Thanks to AceVentura) !
			- new body armors (from vanilla) , Level II armor and Kevlar (no sleeves). 
			- new headgear ( boonie hat , ballistic glasses )
			- New Minimal HUD (optional) 
			- Dynamic shell textures on Breaching SG an Benelli M4 depending on shell type.
			- New "Shake Camera" added when get shot or near a C2 blast. 
			- Camera shake when player has been hit and close to a C2 explosion.
			- New "reduced" Ninebang effects
	SOUNDS:
			- NEW WEAPONS SOUNDS OVERHAUL! ( Thanks to Multi ! )
	 
FIXED:
	- Stuttering and weight bugs in MP : removed old SEF system in change of a new simplified system with better net performances.
	- Suspects can remove wedges only within 35 mts from players.
	- Trapped doors are signaled by AI only there are traps in the map.
	- MP heavy mesh texture bug

#### V0.65 ####

ADDED
- Manual Low Ready system 
- removed penalty for suspects escaped
- Added "Pull Door" command to let player pull the door (thx Scape/S4 for the script)
- Separated Flashlight and NVG keybinds 
- AI Officers now can use NVG instead of flashlights 
- New keybinds to control NVG light
- Enemy suspects can now remove wedges (50% chance) and barricade just after.
- Enemies can use flashlights (chance depending on enemy skill)
- Enemy pickup weapon restored (thank you EFdee)
- Check Lock can possibly return the presence of a trap... but can be a false statement! 
  Also AI officers now report possible traps when checking the lock but... they can be wrong! 
- SP/COOP Career overhaul: unlock system redone for a better career experience.
  
REMOVED
- Optiwand now cant mirror under the door

FIXED
- MP5A4 Holo ADS point fixed
- Adjusted some weights here and there

#### V0.61 ####

FIXED
- Scar H Aimpoint Suppressed  sound .
- G36K Holo Suppressed sound crash the server 
- Toolkit lockpick dont open/lock door after use 
- CS gas crash!!!!!!! 
- reverted Unauth. use of force penalty to SEF7 

ADDED
-new Ninebang explosion sound
- Ryker's Tasers sounds
- Run speed revised : now "No Armor" is SEF speed level , "Ceramic Armor" FR level , "Kevlar Armor" something in between the two. Basically now if you want speed carry less armor. Other speeds dont touched, i think they are good as they are!!!


#### V0.6 FEATURES ####

VISUAL & SOUNDS:
- Gas mask breathing loop sound
- New weapons realistic sounds replacements

NEW WEAPONS:
- adding new weapons and new variation to actual weapons 
    - Beretta 92FS
    - Benelli M4 + Eotech 552 Holographic sight
    - M4 CQB + Holo + Silencer 
    - UMP  Holo + Silencer 
    - Sig 552 ( SEF model ) + Aimpoint + Silencer 
    - MP5A4 Holo + Silencer 
    - G36K Holo + Silencer
    - new M16A1 model!
	- Nine Bangers Flashbang 
	
GAMEPLAY: 
- chambered round counted in magazine-based weapons
- Penalties: every injury on compliant or arrested hostage/suspects is an unauthorized use of force (-5).
- Penalties: Sniper can only shoot suspects that are threats
- Flashlight to be turned off when unequip
- Flashlight cone reduced to match realistic cone size
- reviewed all weight system with real weights (bulk tweaked a bit for some tac-aid )
- little review of tact aids slot so i can expand different new grenade depending on type : 
                           -slot 1 for bangs only
                           -slot 2 for gas only
                           -slot 3 for sting only
other slot free for other tac aids equipment.
- 20% higher chance to have a hostage/suspect compliant if issued a comply with flashlight on

### v0.5
 
#### MAJOR FEATURES ####

- New weapon models to replace the vanilla ones (M4 , G36, 1911 , Glock , Mp5 , Taser X2 , UMP , Rem M870,Benelli Nova, Benelli M4 etc .  + Silenced and Aimpoint Variants)
- Replaced and tweaked gunshots sounds to be more realistic
- new Mich helmet models with variations , Safariland holster model and motorola radio 
- AI now react more to gunshots sound and investigate with more probability , tweaked enemy architype
- Door static meshes overhaul with updated knobs models
- updated hands models 
- new HUD with removed crosshair aim indicators
- slowed Swat movement for a more tactical gameplay
- new player camera position to fix weapons clipping! 
- zoomFov to 90 to better gunplay vision
- many bad guys guns models updated with new 3d models
- Enemy Achitypes revised for realistic suspects weapons
- added - 5 penalty for tasing hostages in any condition (considering real life procedures)
- nerfed Optiwand: 
           - now can be heard by suspects and can trigger them to investigate 
              doors
           - reduced FOV , lcd resolution and speed of lens movement 
- melee nerfed: reduced time of sting for AI 
- lockpicking nerfed: now it takes 30 second to open/lock a door and the sound of it triggers AI investigation
- all comply shouts now trigger AI investigation
- GUI update for all new weapons and equipment


# GNU LICENSE #

Modified source code from SEF 7 has been provided within the downloaded pack in the file Source.rar .
All the other files are free to be seen with SwatED and text editors.

# KNOWN BUGS: # 

Known bugs:
- toolkit/pistol bug   ( possible fix added in v0.6 ) - made toolkit unequip manual after use
- shared flashbang stay in hands after unequip - SEF bug 


# THANKS # 

Eezstreet and all the gang that had contributed the SEF mod , the best of the best! 
Vetinari and nedd for the HUD reticle mod which has been "big bang moment" primary idea for starting this mod.
Scape for the tips on code! 
Mantas for the beautiful logos!
Panzer8, 4non , Mantas , Emil ,Scape for the massive trailer and showcase! 

All the supportive community that keeps me working and having fun on the mod!
