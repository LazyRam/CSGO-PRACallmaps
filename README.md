## <b>NUM ENTER - Shows Keybindings and Clears Console </b>
my steam profile is https://steamcommunity.com/id/Kiprae/ to comment a bug or just say hi

The 35 <b> BINDS ARE ON LINE 2103</b> if you want to check or change any of them -near the bottom


# Binds
### Keybindings and Commands list
- kp_enter	- shows keybindings and clears console
- kp_plus	- shows all give commands/arguments
- kp_minus	- shows map selection console commands

### Nade Position/Lineup binds
- Rshift     - Choose your Loaded Map
- Rctrl      - Choose Current Map optionals
- uparrow    - Terrorist Nades: Smoke, Molotov, Flash
- downarrow  - Counter Terrorist Nades: Smoke, Molotov, Flash
- leftarrow  - Next Nade Lineups
- rightarrow - Previous Nade Lineups
- NUM insert - Secondary Position for Current Lineup-

### Bot
- Insert     - places bot at crosshair
- Delete     - kicks all bots
- Home	     - makes bot crouch
- End	     - bot mimics you
- PGUP	     - adds t bot
- PGDOWN     - adds ct bot

### Crosshair Color Changer
- 7		  - Choose Crosshair Color Preset 1-5
- HOLD 8	  - hold to select/change red,   release to save tent to Chosen Preset
- HOLD 9	  - hold to select/change blue,  release to save tent to Chosen Preset
- HOLD 0	  - hold to select/change green, release to save tent to Chosen Preset
- "-"		  - darken curret color/tent
- "="		  - lighen current color/tent
- Backspace	  - clears console

### limiter
- Y	     - grenade trajectory timers
- U	     - the player become invulnerable
- I 	     - infinite ammo
- O	     - see players through walls
- P	     - auto bunny hopping
- [	     - shows bullet hits
- ]	     - shows impacts
- \ 	     - draws player/nade, wall clippings

### nade
- H	     - removes airborn grenades
- J	     - throws recorded nade path, need vscript
- K	     - gives all grenades
- L	     - outlines where bomb can be planted
- ;	     - draw line/ray
- ' 	     - stops developer text in upper left corner

### log
- N	     - disable particles i.e. smoke
- M	     - teleport to logged positions/hold for second position
- ,	     - log position 1
- . 	     - log position 2
- /	     - nothing yet

### extra
- Tab	     - toggles Buy anywhere
- F	     - inspects weapon and clears blood/bullet holes
- Capslock   - Jump Throw Nade

### speed
- alt	     - fly/noclip
- Ralt	     - increase game speed 10x


## HOW TO SETUP: Fast
1. Put PRACallmaps.cfg into C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg
2. Play CSGO, Choose Prefered Map, PRACTICE WITH BOTS
3. Open Console "~" Enter "exec PRACallmaps"

## HOW TO SETUP: Detailed
1. Download PRACallmaps.cfg
	OR
1. Past PRACallmaps.cfg text into File and Name it PRACallmaps.cfg
2. Past PRACallmaps.cfg file into CSGO's config folder located @
	- ---> C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg
3. Open CSGO and Enable Developer Console in Settings Located @
 	- ---> "Settings menu" -Gear, "Game" -Section 5 from the top, "Enable Developer Console (~)" YES
4. Choose Prefered Map  Press your Developer Console Key (~) tilda, Type "map de_dust2" Enter -list of maps are below
		- -FIX: if Developer Console (~) does not open "alt+tab" out then "alt+tab" back in, try (~)tilda again
	- OR
-	click "Play CSGO" -top left play icon, click on Prefered map "Dust II" Once it is Highlighted
-	click on "OFFICAL MATCHMAKING" -rectangle, Then "PRACTICE WITH BOTS", Hit "GO" -bottom right
5. Load/Exec the PRACallmaps.cfg Config file
-	Once Map Loades, Open Developer Colsole with Key (~) tilda, Type "exec PRACallmaps", hit ENTER
-		-can choose team then "exec PRACallmaps" if you want
## Patch Notes

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
- disabled "nvm"/next view model bind
- changed keybinds to fix conflicting binds and put them in similar sections i.e. god mode next to bottomless clip
- put more frequently used binds to more easily reached keys

### 7.22.19
- added patch notes
- added 1 more dust2 flash for t and ct fctmbw -flash ct mid from B window
- fixed up dust2 smoke and flash code for easier understanding -no more starting at 0

## 
### LIST OF MAYBES
- bind backspace to clear crosshair preset .log file? even possible with console only? or maybe just clear console
- set bind to start and save nade presets
- Smoke Z from big truck old cache
- extra help button? leads to a how to edit the code video?	 how to use config video?  general tutorial?
- rctrl - jump boost positions, nades to take a/b, callouts, god tier nades, jump bind nades, one way smokes?
- bot that jump, walk, run crouch past/peak set locations on each map?
- list of pro settings?
##
### LIST OF TODO'S
- Overpass, nuke, Vertigo, new cache, cobblestone
- optimize, to much code could break cfg when new map linups added
- set O bind to cycle diffrent types of wall hack commands 
- add map name commands NUM MINUS
- fix and addon to echo bind num_ enter j,num_plus,num_minus, \, rctrl
