# Game Patches, Fixes and Configs
This personal repository is meant to store all configs and patches for games I really love and am still playing or would like to return to at some point.

These settings were tested on PC:
* **OS:** Windows 10 Pro (64-bit)
* **Motherboard:** Gigabyte Z590 AORUS ELITE ATX LGA 1200
* **CPU:** Intel Core i7-11700KF 3.6 GHz (5.0 GHz Max)
* **CPU Cooler:** Cooler Master Masterliquid ML240L V2 RGB
* **GPU:** MSI GeForce RTX 2060 6 GB VENTUS
* **RAM:** Corsair Vengeance 32 GB DDR4-3600 MHz (2x16 GB)
* **Case:** NZXT H510 Flow
* **PSU:** Corsair RM850x 850W Gold+ Full Modular
* **Storage:**
	* **OS:** WD Blue 500 GB NVMe M.2 (SSD)
	* **Files:** Seagate Barracuda 2 TB 7200 RPM (HDD)

| Table of Contents 										|
|-----------------------------------------------------------|
| [1. Folder names](#folder-names) 							|
| [2. Patches and Sourceports](#patches-and-sourceports) 	|
| [3. Mods](#mods) 											|
| [4. Bots](#bots) 											|
| [5. Steam launch parameters](#steam-launch-parameters)	|

## Folder names
Each root folder represents the name of the engine, and inside each one is a folder with the name of the game made with said engine. Most of the files are configuration and keybinds, but sometimes they can include actual patches.

There's also certain folders that contain complex names with brackets. Whatever files are inside of them, you must place them in the correct path inside of your computer.

**EXAMPLE:**
* idTech
	* DOOM (2016)
		* [%USERPROFILE%] [Saved Games] [id Software] [DOOM] [base]

The above example would correspond to Windows Explorer's path: `%USERPROFILE%/Saved Games/id Software/DOOM/base` for DOOM (2016)'s config files.

**One last thing:** some files could not be added to the repository due to file size, so I'll be linking them below.

## Patches and Sourceports
Please note that the majority of these patches are meant to be used with Steam.

* Duke Nukem 3D & Shadow Warrior Classic
	* [EDuke32 + VoidSW Sourceport](https://www.eduke32.com/) (If using VoidSW for Shadow Warrior Classic Redux, replace `sw.exe` with `voidsw.exe`)
<br/><br/>

* Blood
	* [NBlood Sourceport](https://github.com/nukeykt/NBlood/) (Replace `anuket_x64.exe` with `nblood.exe`)
<br/><br/>

* Shadow Warrior Classic
	* [Raze Sourceport](https://raze.zdoom.org/about) (Replace `sw.exe.exe` with `raze.exe`)
<br/><br/>

* Painkiller: Black Edition
	* [Ultimate Community Patch RC3](https://drive.google.com/drive/u/0/folders/1cGoS4fiQLHw3v-EVVFcIoEDOb27SQgu6) - If that link doesn't work, try [this one](https://steamcommunity.com/sharedfiles/filedetails/?id=1789104850)
<br/><br/>

* Quake
	* [Ironwail Sourceport](https://github.com/andrei-drexler/ironwail) (Replace `glquake.exe` with `ironwail.exe`)
		* NOTE: To make music work with Ironwail, simply go into the game's/mod's folder and create a new folder named "music". Place all .ogg files inside
	<br/><br/>

* Quake II
	* [Yamagi Quake II Sourceport](https://www.yamagi.org/quake2/) (Replace `quake2.exe` with `yquake2.exe`)
	* [Quake 2 + Mission Packs Soundtrack](https://drive.google.com/drive/folders/124YaufMF45MBgl0kUOmikpEb2ZNPWISG?usp=share_link)
	<br/><br/>

* Quake 4
	* [Quake 4 Tweaker](https://community.pcgamingwiki.com/files/file/1009-quake-4-tweaker/)
	<br/><br/>

* Return to Castle Wolfenstein
	* [iortcw Sourceport](https://github.com/iortcw/iortcw)
	<br/><br/>

* Half-Life
	* [Xash3D FWGS Sourceport](https://github.com/FWGS/xash3d-fwgs/) (Replace `hl.exe` with `xash.exe`)
	<br/><br/>

* Half-Life 2
	* [QoL Improvements](https://drive.google.com/drive/u/0/folders/1QIhGnVIUntIBv5rkHvFDgDTcuYnwyowK)
<br/><br/>

* Titanfall 2
	* [Northstar Client](https://northstar.tf/)

* Unreal Gold
	* [OldUnreal's Patch 227j](https://www.oldunreal.com/downloads/unreal/oldunreal-patches-for-unreal-latest-ver.j/)
<br/><br/>

* Unreal Tournament
	* [Direct3D 10 Renderer](http://kentie.net/article/d3d10drv/)
	* [OldUnreal's Patch 469c](https://github.com/OldUnreal/UnrealTournamentPatches/releases/tag/v469c)
	* [foxWSFix99](https://github.com/alexstrout/foxWSFix-UT99)
<br/><br/>

* Unreal Tournament 2004
	* [UT2004 Community Patch](https://www.moddb.com/games/unreal-tournament-2004/downloads/ut2004-community-patch-2023)
	* [Direct3D 8 to Direct3D 9 Wrapper](https://github.com/crosire/d3d8to9) (Place inside of the `System` folder)
<br/><br/>

* Daikatana
	* [Unofficial 1.3 Patch](https://bitbucket.org/daikatana13/daikatana/wiki/Downloads)

## Mods
These are some mods that I really enjoy and figured I might link them here.

* **Assetto Corsa**
	* [Content Manager](https://assettocorsa.club/content-manager.html)
	* [Sidekick Extended](https://www.nutrimatic.cc/assetto-corsa/sidekick-extended/)
	* [RedBull X2010](https://assettocorsa.club/mods/auto/redbull-x2010.html)
	* [Formula RSS 2013 V8](https://racesimstudio.sellfy.store/p/formula-rss-2013/)
		* [Formula RSS 2013 V8 Community Skin Pack](https://www.racedepartment.com/downloads/formula-rss-2013-v8-f1-2013-community-skinpack.48911/)
	* [Formula Hybrid 2021](https://racesimstudio.sellfy.store/p/formula-hybrid-2021/)
		* [Formula Hybrid 2021 Community Skin Pack](https://www.racedepartment.com/downloads/formula-hybrid-2021-f1-2021-community-skin-pack.41263/)
	* [Formula Hybrid 2022](https://racesimstudio.sellfy.store/p/fh22/)
		* [Formula Hybrid 2022 Community Skin Pack](https://www.racedepartment.com/downloads/formula-hybrid-2022-f1-2022-community-skin-pack.56922/)
	* [RSS GT-M Pack](https://racesimstudio.sellfy.store/p/rss-gtm-pack/)
	* [Nyanborghini Purracan Skin](https://www.racedepartment.com/downloads/nyanborghini-purracan.28258/)
	* [Sepang International Circuit](https://assettocorsa.club/mods/tracks/sepang-international-circuit.html)
	* [Suzuka International Circuit](https://assettocorsa.club/mods/tracks/suzuka-international-circuit.html)
	<br/><br/>

* **Blood**
	* [Death Wish](https://www.moddb.com/mods/death-wish-for-blood)
	* [Voxels Pack](https://github.com/fgsfds/Blood-Voxel-Pack)
	<br/><br/>

* **Quake**
	* [Alkaline](https://www.quaddicted.com/reviews/alkaline.html)
		* [1.1 Patch](https://www.quaddicted.com/reviews/alkaline1.1.html)
	* [Dimension of the Past](https://www.quaddicted.com/reviews/dopa.html)
	* [Dwell - Episode One & Two](https://www.moddb.com/mods/dwell)
	* [Slayer's Testament](https://www.moddb.com/mods/slayers-testament)
	* [Copper](http://lunaran.com/copper/)
	* [Underdark Overbright](https://www.quaddicted.com/reviews/udob_v1_1.html)
	<br/><br/>

* **Half-Life:**
	* [Azure Sheep](https://www.moddb.com/mods/azure-sheep)
	* [Brutal Half-Life](https://www.moddb.com/mods/brutal-half-life)
	* [Half-Life: Black Ops](https://www.moddb.com/mods/black-ops)
	* [Half-Life: Delta](https://www.moddb.com/mods/half-life-delta)
	* [Half-Life: Field Intensity](https://www.moddb.com/mods/field-intensity)
	* [Half-Life: MMod](https://store.steampowered.com/app/1761270/HalfLife_MMod/)
	* [They Hunger](https://www.runthinkshootlive.com/posts/they-hunger/)
	* [Residual Point + Residual Life](https://www.runthinkshootlive.com/posts/residual-life/)
	* [Gunman Chronicles](https://www.moddb.com/games/gunman-chronicles)
	* [Sweet Half-Life](https://www.moddb.com/mods/sweet-half-life)
	* [Poke646](https://www.moddb.com/mods/poke646-anniversary-edition)
	* [Signal Lost](https://www.moddb.com/mods/signal-lost)
	* [USS Darkstar](https://www.runthinkshootlive.com/posts/uss-darkstar/)
	<br/><br/>

* **Return to Castle Wolfenstein**
	* [RealRTCW](https://store.steampowered.com/app/1379630/RealRTCW/)

* **Unreal Gold**
	* [The One](https://www.oldunreal.com/phpBB3/viewtopic.php?p=101445#p101445)

## Bots
There are 5 bots for **GoldSrc** engine games:
* CSBot 1.50 (for Counter-Strike 1.6)
* [FoxBot](https://github.com/APGRoboCop/foxbot) (for Team Fortress Classic)
* [Parabot](https://github.com/nekonomicon/Parabot/) (for Half-Life and Deathmatch Classic)
* [Sturmbot](https://sturmbot.org) (for Day of Defeat)
* [Ricobot](https://gamebanana.com/mods/373334) (for Ricochet)

**Dependencies**
* [Metamod](http://metamod.org)

To install them, simply extract their contents into Half-Life's folder in your Steam directory.

**DISCLAIMER:** Please note that when using Parabot, some of Half-Life's scripted seequences may be broken. Before installing it, make sure to do a backup of your `liblist.gam` file inside of `<Your Steam Directory/steamapps/common/Half-Life/valve`. To uninstall Parabot, simply replace the `liblist.gam` file with the one you just backed up.

There are 2 bots for **idTech** engine games:
* [Rogue Bot](https://github.com/Jason2Brownlee/QuakeBotArchive/blob/main/bin/rbot.zip) (for Quake)
* [Gladiator Bot](https://mrelusive.com/oldprojects/gladiator/download.shtml.htm) (for Quake 2)

To install them, simply extract their contents into Quake's/Quake 2's folder in your Steam directory.

## Steam launch parameters
To use these: right click the game > Properties > Launch Options

- **AMID EVIL**
```
-nosplash -USEALLAVAILABLECORES -heapsize 2097152
```
<br/>

- **BioShock**
```
-nointro
```
<br/>

- **DOOM**
```
+set com_skipIntroVideo 1 +set r_skipFog 1 -USEALLAVAILABLECORES -heapsize 2097152 -sm4
```
<br/>

- **Half-Life** (and general GoldSrc Engine games)
```
-noforcemaccel -noforcemparms -noforcemspd -nojoy -width [MONITOR WIDTH] -height [MONITOR HEIGHT] -nomsaa -nofbo +gl_vsync 0 +fps_max [MONITOR REFRESH RATE] +fps_override 1 +rate 20000 +cl_cmdrate 106 +cl_updaterate 101
```
If using Xash3D FWGS, add `-console` to enable the console

If playing Opposing Force, make sure `fps_max` is equal or lower than 120. Anything higher will break rope physics

<br/>

- **Half-Life 2** (and general Source Engine games)
```
-novid -nojoy -w [MONITOR WIDTH] -h [MONITOR HEIGHT] +fps_max [MONITOR REFRESH RATE] -high +mat_motion_blur_percent_of_screen_max 0 +mat_postprocess_enable 0
```
<br/>

- **Quake**
```
+g_showintromovie 0
```
If using Ironwail, add these commands: `-fitz -sndspeed 44100 -heapsize 1024000`

<br/>

- **Return to Castle Wolfenstein** (using iortcw)
```
+seta r_mode -2 -console
```
<br/>

- **Wolfenstein The New Order**
```
+set com_skipIntroVideo 1 +set com_allowConsole 1 +cvaradd r_skipPostProcess 1 +cvaradd r_skipFog 1 +cvaradd r_skipFlares 1 +cvaradd r_skipSunFlares 1 +cvaradd r_skipGodRays 1
```
