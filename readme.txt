//***********************************************************
// Call of Duty 4 - RSM Modification                       //
//***********************************************************
// author   : ZeRoY                                        //
// website  : http://forums.raidersmerciless.com/index.php //
// mod      : RSM                                          //
// version  : 1.7                                          //
// update   : August 2008                                  //
//***********************************************************

Features
--------

v1.7

- Now has 84 Ranks
- CTF, CTFB and HTF now supported (from AWE4)
- Classic snipers now get sniper models
- New Killcams
- Stukas strike replace Airstrike
- New Bomb model/shaders for SD & SAB
- New Grenade model (MK2)
- Blood splatter
- Long Range rifles options
- Ambient Mortars
- Anti-run / PRM tactical options (Hardcore only)
- Taunts for Allies (from COD2)
- Knife Half-damage fixed for Hardcore
- Raise time for GER43 Adjusted
- Minor syntax fixed in Intel/Weapons
- Minor bug fixes

v1.6 and previous

- Linux support
- Prestige Mode
- Anti Bunny/Bomb Dive
- Health Regen fixed
- Mosin ADS anim redone (again!)
- Hip accuracy as vCOD for Bolt-action
- Added fix for Hardpoints ticker (reverts to stock if > 10 player a side)
- Dvar added for 50% Damage on Melee (Knife)
- Force Auto-Assign
- Bullet Holes on HUD added
- Add Server to Fav
- rm_pistol Dvar now disables Pistol button in Menu

- 11 Classic Rifles from Call Of Duty 2 added:

* Karabiner 98 + Scoped Version
* Gewehr 43 + Scoped Version
* M1 Garand
* M1903 Springfield
* Mosin-Nagant + Scoped Version
* Lee Enfield + Scoped Version
* Tokarev SVT40

- Rifles seperated in classes which can be turned on/off
- Spawn Protection (from AWE4)
- Healthbar (from AWE4)
- Health regeneration option (Old AWE)
- Customizable Hardpoints Streak
- Some HUD elements can be turned off
- Modded HardPoints messages
- Modded Welcome message (from AWE4)
- Modded Menus/Music
- Rotation messages

For more information check the included riflemod.cfg file

This mod was tested ok on all Stock Gametype (1.7) + CTF, CTFB and HTF (from AWE4) on all Stock Maps (including newer mappack).


Installation for Server Administrators
--------------------------------------

- Place the following files in "Call of Duty 4 - Modern Warfare\mods\rsm" folder (create rsm folder first!)

mod.ff
z_riflemod.iwd

- To launch server modify your iw3mp.exe to the following (windows):

"C:\Call of duty 4 - Modern Warfare\iw3mp.exe" +set dedicated 2 +set fs_game mods/rsm +set net_ip x.x.x.x +set net_port xxxxx +exec server.cfg +map_rotate

Where x.x.x.x is Public IP of your server and net_port xxxxx is desired port for server (usually 28960)

Installation for Clients
------------------------

None, find a server running RSM, connect and Enjoy!

Known issues/notes:
-------------------

The COD2 Rifles in this mod are using stock COD4 anims and are therefor not as good as they could be, i know, the M1 Reload sucks big time :(
Also the weapon's damage was set for this release but isnt definitive.
If you wish to mod the weapon's file here is the table showing the rifles and corresponding cod4 weapon:

M16A4	==> M1 Garand
AK47	==> Karabiner 98
M4	==> Enfield
G3	==> Gewehr 43
G36C	==> SVT40
M14	==> Mosin Bolt

mp5	==> M1903 Springfield
skorpion==> Karabiner 98 Scoped
Mini-uzy==> G43 Scoped
ak74u	==> Moisin Scoped
p90	==> Enfield Scoped

Also provided are 2 sets of 'Skins' for all the rifles, all were created by CutterWolf.

--> Should you wish to use them you will have to replace the files from inside the z_riflemod.iwd (overwrite)

Dvars
-----

see inside riflemod.cfg for RSM Specifics and antirun.cfg for the PRM specifics;
also included:

gametypes.cfg
maprotation.cfg
disableattach.cfg

!!! The last file, disableattach.cfg must be included and the attachments untouched unless you need pistols on loadout!!!

Credits
-------

ZeRoY, RGN DevTeam including Tally, PST{Joker}, Peluski, Marc (Wildcard), T3chnor, Kill3r, Wanna Ganoush + AWE creators, Infinity Ward.

Thanks to |SMART|Sprinter, Rabbit, Novemberdobby, Crazyankles, CutterWolf, Tiller & Coleman for the help in testing and more!

Permissions
-----------

All original and composed textures or assets in this modification remain property of
the sources respective owners.

//********************************************************************************************************
