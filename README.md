## <b>NUM ENTER - Shows Keybindings and Clears Console </b>
my steam profile is https://steamcommunity.com/id/SlothCrazy/ to comment a bug or just say hi

The 48 <b> BINDS ARE ON LINE 2946</b> if you want to check or change any of them -near the bottom

## What is PRACallmaps Config
PRACallmaps is a Convenient "All Aspects of CSGO Practice"
- Teleport to selected nade map/type/side/linup/position
- Common similar command's bound and Cycle through.
- Throw Recorded Nade Path - Vscript - www.youtube.com/watch?v=B9hB2gICopw
- type map position callouts in console to teleport/cycle nades for that position/affected by
- Crosshair Color Changer, all 255 255 255 color combinations with <b> 5 Saveable Presets <b> -data loss





# Binds
### Keybindings and Commands list
- kp_enter	- Shows Keybindings and Clears Console
- kp_plus	- Shows All Give Commands/Arguments
- kp_minus	- Shows Nap Selection Console Commands

### Nade Position/Lineup binds
- Rshift     - Choose your Loaded Map
- Rctrl      - Current Map |Optionals|
- uparrow    - Terrorist Nades: Smoke, Molotov, Flash
- downarrow  - Counter Terrorist Nades: Smoke, Molotov, Flash
- leftarrow  - Next Nade Lineups
- rightarrow - Previous Nade Lineups
- NUM insert - Secondary Position for Current Lineup-

### Bot
- Insert     - Places Bot at Crosshair
- Delete     - Kicks All Bots
- Home	     - All Bots Crouch
- End	     - All Bots Mimic You
- PGUP	     - Adds Bot on Terrorist Side
- PGDOWN     - Adds Bot on Counter Terrorist Side

### Crosshair Color Changer
- 7		  - Choose Crosshair Color Preset 1-5
- HOLD 8	  - hold to select/change |RED|,   While Holding use |- =| Cycle Red Tents
- HOLD 9	  - hold to select/change |BLUE|,  While Holding use |- =| Cycle Blue Tents
- HOLD 0	  - hold to select/change |GREEN|, While Holding use |- =| Cycle Green Tents
- "-"		  - Darken  Color/Tent with Multiple Presses, While Holding Color
- "="		  - Lighten Color/Tent with Multiple Presses, While Holding Color
<b>Release "hold" to Select Color<b>

- Backspace	  - clears console

### LIMITERS +
- Y	     - Shows Bomb Radius and Plant Positions
- U	     - Become a GOD, GODS, Buddah, Vampire Damage
- I 	     - Infinite Ammo or Botomless Clip
- O	     - Render Distance and wall Collision Points
- P	     - HOLD Space to Bunny Hop
- [	     - Visualize Near Misses and bullet Hits
- ]	     - Show Bullet Impact Data
- \ 	     - Remove Weapons and Objects on Map

### NADE
- H	     - Removes Airborn Grenades and Reset Sounds
- J	     - Disable Drawing of Particles
- K	     - Gives all Grenades to player
- L	     - Visualize Grenade Trajectory
- ;	     - Throws Recorded Nade Path

### TELEPORT
- N	     - Show or Teleport to Spawn Positions
- M	     - Teleport to Logged Positions
- ,	     - Log Position 1
- . 	     - Log Position 2
- /	     - Casts a line at Crosshair

### EXTRA
- Tab	     - Buy Menu Outside of Spawn
- Capslock   - Jump Throws Primed Nades
- F	     - Clears Decals and Inspect Weapon
- '	     - Reset Game, Commands, Alias
- ENTER   - Open Team Chat

### FLY
- alt	     - Noclip no Collision Flying
- Ralt	     - Increase Game Speed


## HOW TO SETUP: Fast
1. Put PRACallmaps.cfg into C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg
2. Play CSGO, Choose Prefered Map, PRACTICE WITH BOTS
3. Once Map Loads, Open Console "~" Enter "exec PRACallmaps"

## HOW TO SETUP: Detailed
1. Open PRACallmaps.cfg
![](images/Step.1.png)
##
2. Copy PRACallmaps.cfg Text
![](images/Step.2.gif)
##
3. Create New File Named PRACallmaps.cfg
![](images/Step.3.gif)
##
4. Past copied text into -PRACallmaps.cfg
![](images/Step.4.gif)
##
5. Past Folder Location into folder explorer adress bar then Press - ENTER. Then Past PRACallmaps.cfg file into cfg Folder
> C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg
![](images/Step.5.gif)
##
6. Open CSGO, Enable Developer Console, Choose Map
![](images/Step.6.gif)
##
7. Once Map Loads Choose Team, Open Console with ` Tilda, Type exec PRACallmaps
![](images/Step.7.gif)


## Patch Notes
### 6.4.21
- reduced ammout of lines about 600
- added show keybinding list with their commands 
- added dust 2 molotov a site double box from long
- added commands, mp_drop_grenade_enable 1, mp_anyone_can_pickup_c4 1, mp_items_prohibited 0, mp_weapons_allow_heavyassaultsuit 1,
- moved  Plant Positions command, previously on key (N) to (y)
- fixed bot delete bind
- updated give commands
- update Map List Header -auto updates
- added Game Types, Game Modes, Skirmish Modes to Map List
- updated bot place to use both pgup/pgdn and - =
- updated Invulnerablties Health Rotation
- fixed Grenade Trajectory Timer, Dash, Thickness
- removed Grenade Trajectory Dash backspace option
- added snd_restart to (') -easier sound fix
- updated Reset Game, Convars, Commands, Alias
- updated Show or Teleport to Spawn Positions to be map specific -not only dust 2
- updated dust 2 ct/t spawn point angles
- added spacing in commands -easier to understand
### 2.21.20
- added Dust2 CT Flashes -FlashASitefromNinja, FlashASitefromNinja2
- added CT Molotov -MolitovCatwalkfromMidDoor
- added alias groups -Ramp, Goose, ASite, Suicide, TopMid, Catwalk, Short, Ninja, TRamp, OutsideTuns, UpperTuns, LowerTuns, Xbox, MidDoor, CTSpawn
###2.20.20
- added alias Groups -TSpawn, OutsideLong, LongDoor, Pit, ACar, Elevator
- Fixed Selecting Dust2 auto Spawned you at Nade Locations
- Fixed TSmoke24 Mistyped Alias Causing Game to Crash
### 2.19.20
- changed FashShortfromLong lineup/alias names to -FashShortfromLongDoor
- tested all Dust2 Nades and Alias Groups -Various Fixes -all works Properly
- Updated Aliases and Alias Groups to work with new Lineups
- changed Dust2 Lineup Aliases to make it easier to add onto Alias Groups
### 2.18.20
- added 2 Dust2 T Smoke -OneWayShortLedge
- Removed some aliases that were over the 31 character limit -alias MolotovUnderRightWindowfromCTMid DCTML05
- Updated Dust2 Nade Aliases Door,Doors , UnderWindow,BackSite , CatWalk,Cat
- added DefendBSite Alias to Dust2 Grouped Aliases  -Select dust2 map, type DefendBSite in Console
- added DefendASite Alias to Dust2 Grouped Aliases  -Select dust2 map, type DefendASite in Console
- added 1 Dust2 CT Molotov
- fixed dust2 flash now properly showing lineup then position
### 2.17.20
- added TakeBSite Alias to Dust2 Grouped Aliased -Select dust2 map, type TakeBSite in Console
- added TakeASite Alias to Dust2 Grouped Aliases -Select dust2 map, type TakeASite in Console
- UPDATED 2 Dust2 T Molotov 
- organized and Optimized all dust2 nade code
- added dust2 Smokes into One Way  alias -OneWay -Select dust2 map, type OneWay in console, leftarrow rightarrow to cycle 1-9
- fixed dust2 T Smokes to properly Cycle
- added Dust2 Smokes into Jump Binds alias - JumpBind -Select dust2 map, type JumpBinds in console, leftarrow rightarrow to cycle 1-6
- edited dust2 smoke code to allow custom grouped alias
- fixed dust2 alias to now trigger when dust2 map is selected instead of working after cycling all nades
### 2.16.20
- added Multiple aliases for each Dust2 Smokes ie. SmokeLongDoorfromElevator, SLDFE, DCTSL01 -all the same
- organized and Optimized Dust2 T Smoke Code
- organized and Optimized Dust2 CT Smoke Code
- added 11 Dust2 T Nades - 3 Dust2 CT Nades
### 2.15.20
- organized Dust2 Nades Code to make it easier to add nades
- added 6 More Nades to Cache T Smokes
- made it Easier to Add Binds to Cache T Smokes
### 2.14.20
- Found 6 Z window Smokes Cache
- Fixed All T Smokes Cache Smokes
- Fixed Dust2 Smoke Name
- Fixed Show Scores and Toggle buy anywhere to show single word alias
- updated Reset Game Alias to match new Binds
### 2.13.20
- Updated Keybingings alias to New Binds
- Fixed Show All Give Commands -cleaner look -shows Commands at Top
### 2.12.20
- moved Code around to fit bind list ie. infinite ammo code is next to invulnerablty code
- changed Binds Around to Better Fit their Catagory 
- added Spawn Point Teleportations onto N extra Operions with - = keys
- fixed Bullet Impact Color Timer Penetration Extra Options can now set a timer without prenetration data forced on
- added Noclip Acceleration and More Fly Speed to Extra Options with - = keys
- added Vampire Damage Extra Options with - = keys
### 2.10.20
- fixed Infinite ammo alias IAC to properly Disable Commands
- edited code to make it easier to change binds -all commands bound to single word alias
- added Reset All Alias onto Reset Game, Commands, Alias bind (')
- added Extra Options onto Grenade Trajectory Thickness with - = keys and Dash  with - = keys + Backspace Toggle
- fixed crosshair color changer to stop showing error if selecting a preset that has not been saved yet
### 2.9.20
- added Extra Options onto Remove Airborn Grenade H key -Stop or Reset Sound
- added Vampire Damage into Invulnerablties Cycle Extra Options with - = keys
- added Disable Death Drops to extra options of Remove Dropped Weapons and Reset Hp \ Alias
- added bind resets to Game Restart ' alias
- fixed removel airborn molotov sound bug by flushing sound on removal
- added Noclip Echo to Stop Blocking Map Position Text
- fixed Wallhack and Collision Points Bind to Properly Reset after each Rotation
- added Reset All Commands Back to default to the ' alias
### 2.8.20
- alt then Spacebar Will Reset Backspace to hide Developer PIP text
- Added Extra Options to Noclip Speed with - = keys
### 2.7.20
- Server Ips in Console are now Hidden (except when you type 'status')
- TIMESCALE - Added Extra Options onto Time Scale, - = keys to change Time Scale of held Ralt key, release Ralt Default Speed
- TIMESCALE - press Backspace to Save/Toggle Current Time Scale option change saved option with - =
- Fixed Buy Anywhere Toggle Bind
### 2.6.20
- Added Extra Options Onto Bullet Impact Color and Penetration with - = keys
- Added Extra Options Onto Wallhacks and Collision Point keybind with - = keys
- Added Extra Options Onto Infinite Ammo with - = keys
- updated Noclip to Have Spacebar Hold Your in Air Position -spacebar will still jump normally when landed
- fixed show keybindings button caused by : symbol in echo command
### 2.5.20
- added extra options onto Grenade Trajectory with - = keys
- added another type of infinite ammo into cycle
-Fixed Grenade Trajectory Timer
### 2.4.20
- Added Map Selection Commands in Categories and Alphebetical lists to the Num Minus key
### 2.3.20
- Updated Echo Binds to Be More Detailed and easier to understand for newer Players
- Overall Qualtiy of life Changes, Visally see More Detail in Developer PIP Text and What Command Cycle your ON
- added many new command cycles
- combined Wallhack and wall Clipping/Collision Points Commands into 1 Key
### 2.2.20
- fixed crosshair color changer so you wont have to make crosshaircolor1-5.log files on first use
- added invulnerablty health cycles
- added BACKSPACE command cycle. stop developer PIP text, clear console
- added bullet impacts cycle with extra impact data and timers

### 1.30.20
- added ability to drop knife
- added new bind NUM PLUS -shows all give commands in neat categories
- made it easier to copy give commands

### 11.10.19
- added Crosshair Color Changer on 7,8,9,0 with supporting -,= keys
- added  HOW TO USE: Crosshair Color Changer
- cleaned up some code

### 11.4.19
- added HOW TO USE: Nade Positions/Linup
- removed "nvm"/next view model bind
- changed keybinds to fix conflicting binds and put them in similar sections i.e. god mode next to bottomless clip
- put more frequently used binds to more easily reached keys

### 7.22.19
- added patch notes
- added 1 more dust2 flash for t and ct fctmbw -flash ct mid from B window
- fixed up dust2 smoke and flash code for easier understanding -no more starting at 0

## 
### LIST OF MAYBES
- how to edit/add, code, video? how to use config video?  general tutorial?
- list of pro settings?
- Move extra extra options (backspace) to Y? y easier to reach backsapce next to extra option - =
- save custom commands as preset
- extra option to team chat bind -all chat
- set hotkey / as teleport Presets -possible without exec?
- Crosshair List -why memorize nade Linups when the crosshair will tell you?
- make callout minigame for new players

##
### LIST OF TODO'S
- Nuke -0%, Overpass -0%, New Cache -0%, Vertigo -0%, Cobblestone -0%, Ancient -0%.
- Headphone sound test
- set bind to start and save nade presets
- bomb damage testing
- organize Nade code Dust2 100%, Mirage 0%, Cache 15%, train 0%, inferno 0%, nuke 0%, overpass 0%, vertigo 0%, cobblestone 0%
- Add Spawn Positions to All Maps

- Positional callout aliases
- bind rctrl to choose Select between |Affect Position|-|From Position|-|To Position| of current nade position alias
- Simple aliases for all used Command Cycles? ie. type GrenadeTrajectoryTimer

##
###LIST OF USED COMMANDS
  
### A
- alias
- ammo_grenade_limit_total 5
- 
### B
- bind
- bot_add_ct
- bot_add_t
- bot_chatter off
- bot_crouch 0
- bot_kick all
- bot_kick ct
- bot_kick t
- bot_mimic 0
- bot_mimic_yaw_offset 0
- bot_show_battlefront 0
- bot_stop 1
- buddha
### C
- cast_ray
- cl_crosshaircolor_b
- cl_crosshaircolor_g
- cl_crosshaircolor_r
- cl_hideserverip 1
- cl_showpos 0
- cl_soundscape_flush
- clear
- con_filter_enable 2
- con_filter_text_out
- con_logfile cfg/ .log
- 
### D
- developer 1
- 
### E
- echo
- ent_fire
- exec
- execifexists
- 
### F
- 
### G
- game_mode
- game_type
- god
- gods
- 
### H
- host_timescale 1
- 
### I
- 
### J
- 
### K
- 
### L
- lookatweapon
- 
### M
- Mat_fillrate 0
- map_showbombradius 
- map_showspawnpoints 0
- maps *
- messagemode
- messagemode2
- mp_anyone_can_pickup_c4 1
- mp_autokick 0
- mp_buytime 9999
- mp_damage_vampiric_amount 0
- mp_death_drop_c4
- mp_death_drop_defuser
- mp_death_drop_grenade
- mp_death_drop_gun
- mp_drop_grenade_enable 1
- mp_drop_knife_enable 1
- mp_freezetime 0
- mp_ignore_round_win_conditions 1
- mp_items_prohibited 0
- mp_limitteams 0
- mp_maxmoney 60000
- mp_playercashawards 0
- mp_respawn_on_death_ct 1
- mp_respawn_on_death_t 1
- mp_restartgame
- mp_roundtime_defuse 60
- mp_startmoney 60000
- mp_warmup_end
- mp_weapons_allow_heavyassaultsuit
- 
### N
- noclip
-
### O
- 
### P
-
### Q
- 
### R
- r_cleardecals
- r_drawclipbrushes 0
- r_drawothermodels 1
- r_drawparticles 1
- reset_expo
- reset_gameconvars
- 
### S
- say
- setang
- setpos_exact
- showscores
- showtriggers_toggle
- snd_restart
- sv_autobunnyhopping 1
- sv_cheats 1
- sv_grenade_trajectory
- sv_grenade_trajectory_dash
- sv_grenade_trajectory_thickness
- sv_grenade_trajectory_time
- sv_infinite_ammo 0
- sv_noclipaccelerate
- sv_noclipspeed 5
- sv_showbullethits 0
- sv_showimpacts 0
- sv_showimpacts_penetration 0
- sv_showimpacts_time 3
- 
### T
- 
### U
- 
### V
- vcollide_wireframe 0
- 
### W
- weapon_recoil_scale 2
- 
### X
- 
### Y
- 
### Z
- 
  
