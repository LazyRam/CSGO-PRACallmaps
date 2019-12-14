# CSGO-PRACallmaps
CSGO Nade Position / Lineup Config. Easily Find and Remember Map Nade Lineup. | Rshift - Choose Map |  UPARROW - T nades: Smoke, Molotov, Flash | DOWNARROW - CT nades: Smoke, Molotov, Flash | LEFTARROW - Next Nade Lineups |  RIGHTARROW - Previous Nade Lineups |NUM insert - Secondary Position for Current Lineup |


//my steam profile is https://steamcommunity.com/id/Kiprae/ if you care to say hi
//the 34 binds are on line 2086 if you want to check or change any of them -near the bottom

	//HOW TO USE: Nade Position/Lineup binds
//Rshift - Choose Map
	//uparrow    - T nades: Smoke, Molotov, Flash
	//downarrow  - CT nades: Smoke, Molotov, Flash
	//leftarrow  - Next Nade Lineups
	//rightarrow - Previous Nade Lineups
		//NUM insert - Secondary Position for Current Lineup

	//HOW TO USE: Crosshair Color Changer
//7		 - Cycle Through Customizable Presets
//HOLD 8	  - select Red tent with -  = |Release to save to Selected Preset
//HOLD 9	  - select Blue tent with -  = |Release to save to Selected Preset
//HOLD 0	  - select Green tent with -  = |Release to save to Selected Preset
//______________________________________________________________________________

	//patch notes
	//7.22.19
//added patch notes
//added 1 more dust2 flash for t and ct fctmbw -flash ct mid from B window-
//fixed up dust2 smoke and flash code for easier understanding -no more starting at 0
	//11.4.19
//added HOW TO USE: Nade Positions/Linup
//disabled "nvm"/next view model bind
//changed keybinds to fix conflicting binds and put them in similar sections i.e. god mode next to bottomless clip
//put more frequently used binds to more easily reached keys
	//11.10.19
//added Crosshair Color Changer on 7,8,9,0 with supporting -,= keys
//added  HOW TO USE: Crosshair Color Changer
//cleaned up some code
//______________________________________________________________________________


sv_cheats 1
mp_freezetime 0
bot_kick all
mp_roundtime_defuse 60
mp_maxmoney 60000
mp_startmoney 60000
mp_warmup_end
mp_ignore_round_win_conditions 1
mp_autokick 0
mp_buytime 9999

bot_add_t;bot_add_t
bot_stop 1
bot_chatter off
mp_respawn_on_death_ct 1
mp_respawn_on_death_t 1
mp_playercashawards 0
bot_mimic_yaw_offset 0

con_filter_text_out execing
con_filter_text_out notification
con_filter_text_out removed
con_filter_text_out ambient
con_filter_text_out Steamworks
con_filter_text_out DispatchAsyncEvent

developer 1
con_enable 1
con_filter_enable 2

sv_grenade_trajectory 1
sv_infinite_ammo 1
sv_showimpacts 1
sv_showimpacts_time 4
sv_showbullethits 1
ammo_grenade_limit_total 5


 //1-14 T SMOKE dust2
alias  "echo_Dsxts"		"echo T Smoke |01-14| XBOX, from T Spawn --------------|Jump THROW|--"				//01
alias  "Dsxts2"			"setpos_exact -402.981110 -1051.968750 105.269623;setang 67.674751 -129.715668 0.000000"
alias  "Dsxts"		  	"setpos_exact -402.993744 -1051.968750 105.269394;setang -8.535801 87.821533 0.000000"
alias  "echo_Dsxtss"	"echo T Smoke |02-14| Xbox, from T Spawn SAFE ---------|JUMP THROW|--"				//02
alias  "Dsxtss2"		"setpos_exact -299.968750 -1163.987549 77.698128;setang 66.376541 -136.451508 0.000000"
alias  "Dsxtss"			"setpos_exact -299.968750 -1163.968750 77.698128;setang -11.890174 90.224937 0.000000"
alias  "echo_Dsxol"		"echo T Smoke |03-14| Xbox, from Outside long ---------|THROW|--"					//03
alias  "Dsxotl2"		"setpos_exact 228.514969 114.024605 5.305698;setang 89.000000 -178.798599 0.000000"
alias  "Dsxol"		  	"setpos_exact 228.514969 114.024605 5.305698;setang -40.877697 108.674026 0.000000"
alias  "echo_Dslcol"	"echo T Smoke |04-14| Long Corner, from Outside long --|THROW|--"					//04
alias  "Dslcol2"		"setpos_exact 222.663666 -87.972336 9.031250;setang 33.043289 168.905487 0.000000"
alias  "Dslcol"			"setpos_exact 222.663666 -87.972336 9.031250;setang -46.524742 48.198826 0.000000"
alias  "echo_Dsctsb"	"echo T Smoke |05-14| CT Spawn, from Blue -------------|JUMP THROW|--"				//05
alias  "Dsctsb2"		"setpos_exact 516.031250 984.173584 1.496542;setang 0.267655 -179.505447 0.000000"
alias  "Dsctsb"			"setpos_exact 516.031250 984.742310 1.507574;setang -55.687420 88.927963 0.000000"
alias  "echo_Dslel"		"echo T Smoke |06-14| Left Elevator, from Long --------|RUN THROW|--"				//06
alias  "Dslel2"			"setpos_exact 860.031250 790.031250 4.314236;setang 28.859867 -155.452072 0.000000"
alias  "Dslel"		  	"setpos_exact 860.031250 790.031250 4.314232;setang -23.790743 42.593624 0.000000"
alias  "echo_Dsrel"		"echo T Smoke |07-14| Right Elevator, from Long -------|RUN THROW|--"				//07
alias  "Dsrel2"			"setpos_exact 1042.274780 1009.672546 -0.847733;setang 89.000000 46.631081 0.000000"
alias  "Dsrel"		  	"setpos_exact 1041.773315 1008.441711 -0.843456;setang -29.597330 42.135872 0.000000"
alias  "echo_Dscts"   	"echo T Smoke |08-14| CT, from Short ------------------|THROW|--"					//08
alias  "Dscts2"			"setpos_exact 189.988220 1334.031250 1.083763;setang 14.210215 -71.510574 0.000000"
alias  "Dscts"		  	"setpos_exact 189.998154 1334.031250 1.083763;setang -15.604875 65.961411 0.000000"
alias  "echo_Dsctss"	"echo T Smoke |09-14| CT, from Short Stairs -----------|THROW|--"					//09
alias  "Dsctss2"		"setpos_exact 427.350922 1749.968750 4.283005;setang -14.417912 138.116058 0.000000"
alias  "Dsctss"			"setpos_exact 427.350922 1749.968750 4.283005;setang -77.585464 54.560299 0.000000"
alias  "echo_Dsctmlt"	"echo T Smoke |10-14| CT Mid, from Lower Tuns ---------|THROW|--"					//10
alias  "Dsctmlt2"	  	"setpos_exact -538.075195 1382.031250 -112.006920;setang 2.359303 -91.235764 0.000000"
alias  "Dsctmlt"		"setpos_exact -538.075195 1382.031250 -112.006920;setang -35.421783 54.107380 0.000000"
alias  "echo_Dsctmd"	"echo T Smoke |11-14| CT, from Mid Door----------------|THROW|--"					//11
alias  "Dsctmd2"	 	"setpos_exact -513.807861 1101.968750 -68.142235;setang 0.725969 88.754402 0.000000"
alias  "Dsctmd"	 		"setpos_exact -513.807861 1101.968750 -68.142235;setang -16.157276 77.820305 0.000000"
alias  "echo_Dsctbmd"	"echo T Smoke |12-14| CT Boost, from Mid Door ---------|CROUCH THROW|--"			//12
alias  "Dsctbmd2"	  	"setpos_exact -454.104675 1757.960693 -124.847725;setang 89.000000 74.332199 0.000000"
alias  "Dsctbmd"	 	"setpos_exact -454.104675 1757.960693 -124.847725;setang -11.298507 64.317223 0.000000"
alias  "echo_Dsbeut"	"echo T Smoke |13-14| B Entrance, from Upper Tuns -----|THROW|--"					//13
alias  "Dsbeut2"	 	"setpos_exact -1749.359741 1064.031250 34.054127;setang 1.245399 -85.050255 0.000000"
alias  "Dsbeut"			"setpos_exact -1749.359741 1064.031250 34.054127;setang -10.656306 118.748222 0.000000"
alias  "echo_Dswbt"		"echo T Smoke |14-14| Window, from B Tuns -------------|THROW|--"					//14
alias  "Dswbt2"			"setpos_exact -1942.031250 1793.396118 33.031250;setang 3.708734 2.565620 0.000000"
alias  "Dswbt"		  	"setpos_exact -1942.031250 1793.396118 33.031250;setang -15.939900 56.028114 0.000000"
//1-8 CT SMOKE dust2
alias  "echo_Dsse" 		"echo CT Smoke |01-08| Short Stairs, from Elevator ----|THROW|--"					//01
alias  "Dsse2"			"setpos_exact 1004.968750 2379.968750 27.467886;setang 4.292089 43.019222 0.000000"
alias  "Dsse"			"setpos_exact 1004.968750 2379.968750 27.467886;setang -10.069054 -151.094757 0.000000"
alias  "echo_Dsltct"	"echo CT Smoke |02-08| Lower Tuns, from CT Spawn ------|THROW|--"					//02
alias  "Dsltct2"		"setpos_exact -242.031250 2278.201660 -120.037674;setang 2.886672 45.848598 0.000000"
alias  "Dsltct"			"setpos_exact -242.031250 2278.201660 -120.037674;setang -32.527428 -123.355118 0.000000"
alias  "echo_Dsldmd"	"echo CT Smoke |03-08| Long Door, from Mid Door -------|THROW|--"					//03
alias  "Dsldmd2"		"setpos_exact -489.968750 1647.018799 -121.545303;setang -3.034775 -132.927719 0.000000"
alias  "Dsldmd"			"setpos_exact -489.968750 1647.018799 -121.545303;setang -50.388153 -39.982853 0.000000"
alias  "echo_Dsldac"	"echo CT SMOKE |04-08| Long Door, from A Car ----------|THROW|--"					//04
alias  "Dsldac2"		"setpos_exact 1750.818115 2046.793823 0.223467;setang 26.277128 -161.053024 0.000000"
alias  "Dsldac"			"setpos_exact 1750.818115 2046.793823 0.223467;setang -33.098396 -129.506287 0.000000"
alias  "echo_Dsbpbd"	"echo CT Smoke |05-08| Back Plat, from B Door----------|THROW|--"					//05
alias  "Dsbpbd2"		"setpos_exact -1037.968750 2102.031250 -5.880976;setang 18.602720 -121.457870 0.000000"
alias  "Dsbpbd"			"setpos_exact -1037.968750 2102.031250 -5.880976;setang -49.984718 145.404510 0.000000"
alias  "echo_Dsbtctm"	"echo CT Smoke |06-08| B Tuns, from CT Mid-------------|THROW|--"					//06
alias  "Dsbtctm2"		"setpos_exact -985.691467 2553.225830 1.360527;setang 30.290930 91.791428 0.000000"
alias  "Dsbtctm"		"setpos_exact -985.691467 2553.225830 1.360527;setang -26.780743 -143.803818 0.000000"
alias  "echo_Dscw"		"echo CT Smoke |07-08| Car, from Window ---------------|THROW|--"					//07
alias  "Dscw2"			"setpos_exact -1273.968750 2575.968750 70.396858;setang 50.238487 138.831772 0.000000"
alias  "Dscw"			"setpos_exact -1273.968750 2575.968750 70.396858;setang -69.225662 -113.615768 0.000000"
alias  "echo_Dsbts"		"echo CT Smoke |08-08| B Tuns, from Scafold -----------|THROW|--"					//08
alias  "Dsbts2"			"setpos_exact -1122.031250 2691.802246 88.099533;setang 21.758518 48.680031 0.000000"
alias  "Dsbts"			"setpos_exact -1122.031250 2691.802246 88.099533;setang -22.992418 -135.173340 0.000000"
//1-4 T MOLOTOV dust2
alias  "echo_Dmmdx"		"echo T Molotov |01-04| Mid Doors, from Xbox ----------|THROW|--"					//01
alias  "Dmmdx2"	   		"setpos_exact -275.031250 1345.591553 -120.932663;setang 12.949299 60.170906 0.000000"
alias  "Dmmdx"	   	  	"setpos_exact -275.031250 1345.591553 -120.932663;setang -32.357460 134.850311 0.000000"
alias  "echo_Dmcl"	  	"echo T Molotov |02-14| Car, from Long ----------------|JUMP THROW|--"			//02
alias  "Dmcl2"	   	  	"setpos_exact 847.157959 790.010498 47.031250;setang 20.880516 -130.511520 0.000000"
alias  "Dmcl"	  	  	"setpos_exact 847.183044 790.018616 47.031250;setang 6.594257 53.602615 0.000000"
alias  "echo_Dmadss"	"echo T Molotov |03-04| A Default, from Short Stairs --|RUN THROW|--"				//03
alias  "Dmadss2"		"setpos_exact 343.010864 1791.881836 96.031250;setang 89.000000 3.859209 0.000000"
alias  "Dmadss"			"setpos_exact 343.010864 1791.881836 96.031250;setang -15.155519 57.642860 0.000000"
alias  "echo_Dmcctm"	"echo T Molotov |04-04| Car, from CT Mid---------------|THROW|--"					//04
alias  "Dmcctm2"		"setpos_exact -984.470825 2553.215088 0.880602;setang 15.428598 95.455116 0.000000"
alias  "Dmcctm"			"setpos_exact -984.470825 2553.215088 0.880602;setang -22.454195 -129.821899 0.000000"
//1-6 CT MOLOTOV dust2 
alias  "echo_Dmadct"	"echo CT Molotov |01-06| A Default, from CT -----------|THROW|--"					//01
alias  "Dmadct2"		"setpos_exact 532.508850 2275.968750 -108.246368;setang 1.643846 91.158661 0.000000"
alias  "Dmadct"			"setpos_exact 532.508850 2275.968750 -108.246368;;setang -25.093990 17.060673 0.000000"
alias  "echo_Dmbsctm" 	"echo CT Molotov |02-06| Back Site, from CT Mid -------|THROW|--"					//02
alias  "Dmbsctm2"		"setpos_exact -760.031250 2066.031250 -109.246544;setang 42.286449 -45.158417 0.000000"
alias  "Dmbsctm"		"setpos_exact -760.031250 2066.031250 -109.246544;setang -24.032660 132.785919 0.000000"
alias  "echo_Dmbpctm"	"echo CT Molotov |03-06| Back Plat, from CT Mid -------|THROW--|"					//03
alias  "Dmbpctm2"		"setpos_exact -936.828735 2521.125244 -24.968748;setang 89.000000 179.241104 0.000000"
alias  "Dmbpctm"		"setpos_exact -936.828735 2521.125244 -24.968748;setang -20.654589 160.227463 0.000000"
alias  "echo_Dmbbctm"	"echo CT Molotov |04-06| Big Box, from CT Mid ---------|RUN THROW|--"				//04
alias  "Dmbbctm2"		"setpos_exact -760.031250 2066.031250 -109.246544;setang 42.453197 -43.435986 0.000000"
alias  "Dmbbctm"		"setpos_exact -760.031250 2066.031250 -109.246544;setang -21.176765 167.059891 0.000000"
alias  "echo_Dmbdctm"	"echo CT Molotov |05-06| B Default, from CT Mid -------|THROW|--"					//05
alias  "Dmbdctm2"		"setpos_exact -1037.968750 2102.031250 -5.880968;setang 18.705425 -121.553818 0.000000"
alias  "Dmbdctm"		"setpos_exact -1037.968750 2102.031250 -5.880968;;setang -22.375061 115.378769 0.000000"
alias  "echo_Dmbdw"		"echo CT Molotov |06-06| B Default, from Window -------|WALK THROW|"				//06
alias  "Dmbdw2"			"setpos_exact -1233.599731 2575.968750 69.760246;setang 60.497070 91.786949 0.000000"
alias  "Dmbdw"			"setpos_exact -1233.599731 2575.968750 69.760246;setang -24.130829 -100.967758 0.000000"
//1-7 T FLASH dust2
alias  "echo_Dflol"		"echo T Flash |01-07| Long, from outside Long ---------|THROW|--"					//01
alias  "Dflol2"	 		"setpos_exact 572.031250 -395.968750 8.031250;setang -3.826839 -134.883560 0.000000"
alias  "Dflol"	 	  	"setpos_exact 572.031250 -395.968750 8.031250;setang -33.700390 61.078144 0.000000"
alias  "echo_Dflild"	"echo T Flash |02-07| Long, From Inside Long Doors ----|THROW|--"					//02
alias  "Dflild2"		"setpos_exact 740.968750 565.968750 1.312302;setang 0.427970 46.671692 0.000000"
alias  "Dflild"			"setpos_exact 740.968750 565.968750 1.312302;setang -55.875259 51.633080 0.000000"
alias  "echo_Dfsl"	  	"echo T Flash |03-07| short, from Long ----------------|RUN JUMP THROW|--"			//03
alias  "Dfsl2"		  	"setpos_exact 847.158264 790.031250 47.031250;setang 25.286047 -122.713005 0.000000"
alias  "Dfsl"		  	"setpos_exact 847.180237 790.022095 47.031250;;setang -16.349781 108.638756 0.000000"
alias  "echo_Dfssc"		"echo T Flash |04-07| Short Stairs, from Cat ----------|RUN JUMP THROW|--"			//04
alias  "Dfssc2"			"setpos_exact -180.225632 1016.905579 1.566311;setang -21.122492 90.701912 0.000000"
alias  "Dfssc"		  	"setpos_exact -178.902390 931.526550 1.109398;setang -2.713776 90.878159 0.000000"
alias  "echo_Dfmdx"		"echo T Flash |05-07| Mid Door, from Xbox -------------|THROW|--"					//05
alias  "Dfmdx2"			"setpos_exact -275.031250 1345.467163 -121.942474;setang -4.435780 56.107464 0.000000"
alias  "Dfmdx"		  	"setpos_exact -275.031250 1345.467163 -121.942474;setang -38.134628 62.604362 0.000000"
alias  "echo_Dfcbt"		"echo T Flash |06-07| Car, from B Tuns ----------------|THROW|--"					//06
alias  "Dfcbt2"			"setpos_exact -1942.031250 1779.626343 33.031250;setang -2.017783 5.932151 0.000000"
alias  "Dfcbt"		  	"setpos_exact -1942.031250 1779.626343 33.031250;setang -37.993996 173.799820 0.000000"
alias  "echo_Dfctmw"	"echo CT Flash |07-07| CT Mid, from Window ------------|STEP BACK THROW|--"			//07
alias  "Dfctmw2"		"setpos_exact -1417.411987 2604.288086 119.031250;setang 89.000000 1.238932 0.000000"
alias  "Dfctmw"			"setpos_exact -1417.411987 2604.288086 119.031250;setang 64.003227 -10.015385 0.000000"
//1-10 CT FLASH dust2
alias  "echo_Dfsalc"	"echo CT Flash |01-10| Short, from A Ledge Corner -----|THROW|--"					//01
alias  "Dfsalc2"		"setpos_exact 546.163818 2068.031250 127.031250;setang 74.104065 -90.244194 0.000000"
alias  "Dfsalc"			"setpos_exact 546.163818 2068.031250 127.031250;setang -82.788750 -0.849468 0.000000"
alias  "echo_Dfsg"		"echo CT Flash |02-10| Short, from Goose --------------|JUMP DELAY R-CLICK|--"		//02
alias  "Dfsg2"			"setpos_exact 1051.031250 2928.031738 128.595932;setang 4.601367 -179.673492 0.000000"
alias  "Dfsg"			"setpos_exact 1051.031250 2928.031738 128.595932;setang -79.852119 -112.670296 0.000000"
alias  "echo_Dfle"		"echo CT Flash |03-10| Long, from Elevator ------------|THROW|--"					//03
alias  "Dfle2"			"setpos_exact 914.031250 2042.027222 -17.104654;setang 17.426029 -124.726250 0.000000"
alias  "Dfle"			"setpos_exact 914.031250 2042.027222 -17.104654;setang -23.867130 -178.846054 0.000000"
alias  "echo_Dfldr"		"echo CT Flash |04-10|Long Door, from Ramp ------------|THROW|--"					//04
alias  "Dfldr2"			"setpos_exact 1320.278687 2187.178955 1.624679;setang 89.000000 -94.270775 0.000000"
alias  "Dfldr"			"setpos_exact 1320.278687 2187.178955 1.624679;setang -5.410153 -93.256966 0.000000"
alias  "echo_Dfmdct"	"echo CT Flash |05-10| Mid Door, from CT --------------|RUN THROW|--"				//05
alias  "Dfmdct2"		"setpos_exact -57.968750 2010.031250 -121.510979;setang 36.808189 -127.163895 0.000000"
alias  "Dfmdct"			"setpos_exact -57.968750 2010.031250 -121.510979;setang -5.289904 9.281506 0.000000"
alias  "echo_Dfmdctm"	"echo CT Flash |06-10| Mid Door, from CT Mid ----------|THROW|--"					//06
alias  "Df2mdctm2"		"setpos_exact -760.031250 2066.031250 -109.246544;setang 42.442257 -43.053860 0.000000"
alias  "Dfmdctm"		"setpos_exact -760.031250 2066.031250 -109.246544;setang -17.363985 174.416672 0.000000"
alias  "echo_Dfbdctm"	"echo CT Flash |07-10| B Door, from CT Mid ------------|THROW or R-CLICK|--"		//07
alias  "Dfbdctm2"		"setpos_exact -871.968750 2084.020752 -79.714668;setang 17.502632 -171.574448 0.000000"
alias  "Dfbdctm"		"setpos_exact -871.968750 2084.020752 -79.714668;setang -32.891148 165.124573 0.000000"
alias  "echo_Dfbsw"		"echo CT Flash |08-10| B Site, from Window ------------|THROW|--"					//08
alias  "Dfbsw2"			"setpos_exact -1273.968750 2575.968750 70.396843;setang 59.427921 119.101753 0.000000"
alias  "Dfbsw"			"setpos_exact -1273.968750 2575.968750 70.396843;setang -41.560570 1.180413 0.000000"
alias  "echo_Dfctmiw"	"echo CT Flash |09-10| CT Mid, from Window ------------|STEP BACK THROW|--"			//09
alias  "Dfctmiw2"		"setpos_exact -1417.411987 2604.288086 119.031250;setang 89.000000 1.238932 0.000000"
alias  "Dfctmiw"		"setpos_exact -1417.411987 2604.288086 119.031250;setang 64.003227 -10.015385 0.000000"
alias  "echo_Dfutbt"	"echo CT Flash |10-10| Upper Tuns, from B Tuns --------|THROW|--"					//10
alias  "Dfutbt2"		"setpos_exact -1942.031250 1507.358276 36.629669;setang -11.089421 0.460696 0.000000"
alias  "Dfutbt"			"setpos_exact -1942.031250 1507.358276 36.629669;setang -42.356304 -131.721848 0.000000"


//1-7 T FLASH Lineup dust2
alias  "DTFL1"  "echo_Dflol;dflol;	bind kp_ins DTFP1; alias DTFLU DTFL2; alias DTFLD DTFL7"
alias  "DTFL2"  "echo_Dflild;dflild;bind kp_ins DTFP2; alias DTFLU DTFL3; alias DTFLD DTFL1"
alias  "DTFL3"  "echo_Dfsl;dfsl;	bind kp_ins DTFP3; alias DTFLU DTFL4; alias DTFLD DTFL2"
alias  "DTFL4"  "echo_Dfssc;dfssc;	bind kp_ins DTFP4; alias DTFLU DTFL5; alias DTFLD DTFL3"
alias  "DTFL5"  "echo_Dfmdx;dfmdx;	bind kp_ins DTFP5; alias DTFLU DTFL6; alias DTFLD DTFL4"
alias  "DTFL6"  "echo_Dfcbt;dfcbt;	bind kp_ins DTFP6; alias DTFLU DTFL7; alias DTFLD DTFL5"
alias  "DTFL7"	"echo_Dfctmw;dfctmw;bind kp_ins DTFP7; alias DTFLU DTFL1; alias DTFLD DTFL6"
//1-7 T FLASH Position dust2
alias  "DTFP1"  "Dflol2;	bind kp_ins DTFL1"
alias  "DTFP2"  "Dflild2;	bind kp_ins DTFL2"
alias  "DTFP3"  "Dfsl2;		bind kp_ins DTFL3"
alias  "DTFP4"  "Dfssc2;	bind kp_ins DTFL4"
alias  "DTFP5"  "Dfmdx2;	bind kp_ins DTFL5"
alias  "DTFP6"  "Dfcbt2;	bind kp_ins DTFL6"
alias  "DTFP7"  "Dfctmw2;	bind kp_ins DTFL7"
//1-10 CT FLASH Lineup dust2
alias  "DCTFL1"  "echo_Dfsalc;dfsalc;	bind kp_ins DCTFP1;  alias DCTFLU DCTFL2;  alias DCTFLD DCTFL10"
alias  "DCTFL2"  "echo_Dfsg;dfsg;		bind kp_ins DCTFP2;  alias DCTFLU DCTFL3;  alias DCTFLD DCTFL1"
alias  "DCTFL3"  "echo_Dfle;dfle;		bind kp_ins DCTFP3;  alias DCTFLU DCTFL4;  alias DCTFLD DCTFL2"
alias  "DCTFL4"  "echo_Dfldr;dfldr;		bind kp_ins DCTFP4;  alias DCTFLU DCTFL5;  alias DCTFLD DCTFL3"
alias  "DCTFL5"  "echo_Dfmdct;dfmdct;	bind kp_ins DCTFP5;  alias DCTFLU DCTFL6;  alias DCTFLD DCTFL4"
alias  "DCTFL6"  "echo_Dfmdctm;dfmdctm;	bind kp_ins DCTFP6;  alias DCTFLU DCTFL7;  alias DCTFLD DCTFL5"
alias  "DCTFL7"  "echo_Dfbdctm;dfbdctm;	bind kp_ins DCTFP7;  alias DCTFLU DCTFL8;  alias DCTFLD DCTFL6"
alias  "DCTFL8"  "echo_Dfbsw;dfbsw;		bind kp_ins DCTFP8;  alias DCTFLU DCTFL9;  alias DCTFLD DCTFL7"
alias  "DCTFL9"  "echo_Dfctmiw;Dfctmiw;	bind kp_ins DCTFP9;  alias DCTFLU DCTFL10; alias DCTFLD DCTFL8"
alias  "DCTFL10" "echo_Dfutbt;dfutbt;	bind kp_ins DCTFP10; alias DCTFLU DCTFL1;  alias DCTFLD DCTFL9"
//1-10 CT FLASH Position dust2
alias  "DCTFP1"  "Dfsalc2;  bind kp_ins DCTFL1"
alias  "DCTFP2"  "Dfsg2;	bind kp_ins DCTFL2"
alias  "DCTFP3"  "Dfle2;	bind kp_ins DCTFL3"
alias  "DCTFP4"  "Dfldr2;	bind kp_ins DCTFL4"
alias  "DCTFP5"  "Dfmdct2;  bind kp_ins DCTFL5"
alias  "DCTFP6"  "Df2mdctm2;bind kp_ins DCTFL6"
alias  "DCTFP7"  "Dfbdctm2; bind kp_ins DCTFL7"
alias  "DCTFP8"  "Dfbsw2;	bind kp_ins DCTFL8"
alias  "DCTFP9"  "Dfctmiw2; bind kp_ins DCTFL9"
alias  "DCTFP10" "Dfutbt2;  bind kp_ins DCTFL10"
//t flash
alias DTFLU DTFL1
alias DTFLD DTFL1
//ct flash
alias DCTFLU DCTFL1
alias DCTFLD DCTFL1


//1-4 T MOLOTOV Lineup dust2
alias  "DTML1"  "echo_Dmmdx;dmmdx;		bind kp_ins DTMP1;	alias DTMLU DTML2; alias DTMLD DTML4"
alias  "DTML2"  "echo_Dmcl;dmcl;		bind kp_ins DTMP2;	alias DTMLU DTML3; alias DTMLD DTML1"
alias  "DTML3"  "echo_Dmadss;dmadss;	bind kp_ins DTMP3;	alias DTMLU DTML4; alias DTMLD DTML2"
alias  "DTML4"  "echo_Dmcctm;dmcctm;	bind kp_ins DTMP4;	alias DTMLU DTML1; alias DTMLD DTML3"
//1-4 T MOLOTOV Positions dust2
alias  "DTMP1"  "Dmmdx2;	bind kp_ins DTML1"
alias  "DTMP2"  "Dmcl2;		bind kp_ins DTML2"
alias  "DTMP3"  "Dmadss2;	bind kp_ins DTML3"
alias  "DTMP4"  "Dmcctm2;	bind kp_ins DTML4"
//1-6 CT MOLOTOV Lineup dust2
alias  "DCTML1"  "echo_Dmadct;dmadct;	bind kp_ins DCTMP1; alias DCTMLU DCTML2; alias DCTMLD DCTML6"
alias  "DCTML2"  "echo_Dmbsctm;dmbsctm; bind kp_ins DCTMP2; alias DCTMLU DCTML3; alias DCTMLD DCTML1"
alias  "DCTML3"  "echo_Dmbpctm;dmbpctm; bind kp_ins DCTMP3; alias DCTMLU DCTML4; alias DCTMLD DCTML2"
alias  "DCTML4"  "echo_Dmbbctm;dmbbctm; bind kp_ins DCTMP4; alias DCTMLU DCTML5; alias DCTMLD DCTML3"
alias  "DCTML5"  "echo_Dmbdctm;dmbdctm; bind kp_ins DCTMP5; alias DCTMLU DCTML6; alias DCTMLD DCTML4"
alias  "DCTML6"  "echo_Dmbdw;dmbdw;		bind kp_ins DCTMP6; alias DCTMLU DCTML1; alias DCTMLD DCTML5"
//1-6 CT MOLOTOV Position dust2
alias  "DCTMP1"  "Dmadct2;	bind kp_ins DCTML1"
alias  "DCTMP2"  "Dmbsctm2; bind kp_ins DCTML2"
alias  "DCTMP3"  "Dmbpctm2; bind kp_ins DCTML3"
alias  "DCTMP4"  "Dmbbctm2; bind kp_ins DCTML4"
alias  "DCTMP5"  "Dmbdctm2; bind kp_ins DCTML5"
alias  "DCTMP6"  "Dmbdw2;	bind kp_ins DCTML6"
//t molotov 
alias DTMLU DTML1
alias DTMLD DTML1
//ct molotov
alias DCTMLU DCTML1
alias DCTMLD DCTML1


//1-14 T SMOKE Lineups dust2
alias  "DTSL1"  "echo_Dsxts;dsxts;		bind kp_ins DTSP1;  alias DTSLU DTSL2;  alias DTSLD DTSL14"
alias  "DTSL2"  "echo_Dsxtss;dsxtss;	bind kp_ins DTSP2;  alias DTSLU DTSL3;  alias DTSLD DTSL1"
alias  "DTSL3"  "echo_Dsxol;dsxol;		bind kp_ins DTSP3;  alias DTSLU DTSL4;  alias DTSLD DTSL2"
alias  "DTSL4"  "echo_Dslcol;dslcol;	bind kp_ins DTSP4;  alias DTSLU DTSL5;  alias DTSLD DTSL3"
alias  "DTSL5"  "echo_Dsctsb;dsctsb;	bind kp_ins DTSP5;  alias DTSLU DTSL6;  alias DTSLD DTSL4"
alias  "DTSL6"  "echo_Dslel;dslel;		bind kp_ins DTSP6;  alias DTSLU DTSL7;  alias DTSLD DTSL5"
alias  "DTSL7"  "echo_Dsrel;dsrel;		bind kp_ins DTSP7;  alias DTSLU DTSL8;  alias DTSLD DTSL6"
alias  "DTSL8"  "echo_Dscts;dscts;		bind kp_ins DTSP8;  alias DTSLU DTSL9;  alias DTSLD DTSL7"
alias  "DTSL9"  "echo_Dsctss;dsctss;	bind kp_ins DTSP9;  alias DTSLU DTSL10; alias DTSLD DTSL8"
alias  "DTSL10" "echo_Dsctmlt;dsctmlt; 	bind kp_ins DTSP10; alias DTSLU DTSL11; alias DTSLD DTSL9"
alias  "DTSL11" "echo_Dsctmd;dsctmd;	bind kp_ins DTSP11; alias DTSLU DTSL12; alias DTSLD DTSL10"
alias  "DTSL12" "echo_Dsctbmd;dsctbmd; 	bind kp_ins DTSP12; alias DTSLU DTSL13; alias DTSLD DTSL11"
alias  "DTSL13" "echo_Dsbeut;dsbeut;	bind kp_ins DTSP13; alias DTSLU DTSL14; alias DTSLD DTSL12"
alias  "DTSL14" "echo_Dswbt;dswbt;		bind kp_ins DTSP14; alias DTSLU DTSL1;  alias DTSLD DTSL13"
//1-14 T SMOKES Position dust2
alias  "DTSP1"  "Dsxts2;   bind  kp_ins DTSL1"
alias  "DTSP2"  "Dsxtss2;  bind  kp_ins DTSL2"
alias  "DTSP3"  "Dsxotl2;  bind  kp_ins DTSL3"
alias  "DTSP4"  "Dslcol2;  bind  kp_ins DTSL4"
alias  "DTSP5"  "Dsctsb2;  bind  kp_ins DTSL5"
alias  "DTSP6"  "Dslel2;   bind  kp_ins DTSL6"
alias  "DTSP7"  "Dsrel2;   bind  kp_ins DTSL7"
alias  "DTSP8"  "Dscts2;   bind  kp_ins DTSL8"
alias  "DTSP9"  "Dsctss2;  bind  kp_ins DTSL9"
alias  "DTSP10" "Dsctmlt2; bind  kp_ins DTSL10"
alias  "DTSP11" "Dsctmd2;  bind  kp_ins DTSL11"
alias  "DTSP12" "Dsctbmd2; bind  kp_ins DTSL12"
alias  "DTSP13" "Dsbeut2;  bind  kp_ins DTSL13"
alias  "DTSP14" "Dswbt2;   bind  kp_ins DTSL14"
//1-8 CT SMOKE Lineups
alias  "DCTSL1" "echo_Dsse;dsse;		bind kp_ins DCTSP1; alias DCTSLU DCTSL2; alias DCTSLD DCTSL8"
alias  "DCTSL2" "echo_Dsltct;dsltct;	bind kp_ins DCTSP2; alias DCTSLU DCTSL3; alias DCTSLD DCTSL1"
alias  "DCTSL3" "echo_Dsldmd;dsldmd;	bind kp_ins DCTSP3; alias DCTSLU DCTSL4; alias DCTSLD DCTSL2"
alias  "DCTSL4" "echo_Dsldac;dsldac;	bind kp_ins DCTSP4; alias DCTSLU DCTSL5; alias DCTSLD DCTSL3"
alias  "DCTSL5" "echo_Dsbpbd;dsbpbd;	bind kp_ins DCTSP5; alias DCTSLU DCTSL6; alias DCTSLD DCTSL4"
alias  "DCTSL6" "echo_Dsbtctm;dsbtctm; 	bind kp_ins DCTSP6; alias DCTSLU DCTSL7; alias DCTSLD DCTSL5"
alias  "DCTSL7" "echo_Dscw;dscw;		bind kp_ins DCTSP7; alias DCTSLU DCTSL8; alias DCTSLD DCTSL6"
alias  "DCTSL8" "echo_Dsbts;dsbts;		bind kp_ins DCTSP8; alias DCTSLU DCTSL1; alias DCTSLD DCTSL7"
//1-8 CT SMOKE Positions
alias  "DCTSP1" "Dsse2;		bind  kp_ins DCTSL1"
alias  "DCTSP2" "Dsltct2;	bind  kp_ins DCTSL2"
alias  "DCTSP3" "Dsldmd2;	bind  kp_ins DCTSL3"
alias  "DCTSP4" "Dsldac2;	bind  kp_ins DCTSL4"
alias  "DCTSP5" "Dsbpbd2;	bind  kp_ins DCTSL5"
alias  "DCTSP6" "Dsbtctm2;	bind  kp_ins DCTSL6"
alias  "DCTSP7" "Dscw2;		bind  kp_ins DCTSL7"
alias  "DCTSP8" "Dsbts2;	bind  kp_ins DCTSL8"
//t-smoke
alias DTSLU DTSL1
alias DTSLD DTSL1
//ct smoke
alias DCTSLU DCTSL1
alias DCTSLD DCTSL1



//1-33 T SMOKE mirage
alias  "echo_mscwts" 	"echo T Smoke |01-33| Cat Walk, from T Spawn ----------|THROW|--"					//01						
alias  "mscwts2" 	 	"setpos_exact 1422.968750 70.968750 -112.902664;setang 66.295868 67.347244 0.000000"
alias  "mscwts" 	 	"setpos_exact 1422.968750 70.968750 -112.902664;;setang -32.608959 -163.866959 0.000000"
alias  "echo_mswts" 	"echo T Smoke |02-33| Window, from T Spawn ------------|RUN LEFT JUMP THROW|--"		//02
alias  "mswts2"			"setpos_exact 1422.968750 34.830582 -167.968750;setang 34.905273 69.557007 0.000000"
alias  "mswts"			"setpos_exact 1422.968750 34.830582 -167.968750;setang -20.443325 163.179245 0.000000"
alias  "echo_mscts"		"echo T Smoke |03-33| Connector, from T Spawn ---------|JUMP THROW|--"				//03
alias  "mscts2"			"setpos_exact 1135.986816 647.971130 -261.387329;setang 49.779896 44.975555 0.000000"
alias  "mscts"			"setpos_exact 1135.986816 647.971130 -261.387329;setang -34.532871 -140.385040 0.000000"
alias  "echo_mssts" 	"echo T Smoke |04-33| Short, from T Spawn -------------|JUMP THROW|--|"				//04
alias  "mssts2" 	 	"setpos_exact 1422.968750 34.833664 -167.968750;setang 35.027115 69.403923 0.000000"
alias  "mssts" 	 		"setpos_exact 1422.968750 34.830582 -167.968750;setang -30.081646 -174.977249 0.000000"
alias  "echo_msctrts" 	"echo T Smoke |05-33| CT Ramp, from T Spawn -----------|JUMP THROW|--"				//05
alias  "msctrts2" 	 	"setpos_exact 1257.786377 -871.968750 -143.968750;setang 74.390694 -89.382584 0.000000"
alias  "msctrts" 	 	"setpos_exact 1257.786377 -871.968750 -143.968750;setang -17.660564 -144.996567 0.000000"
alias  "echo_mstts" 	"echo T Smoke |06-33| Tripple, from T Spawn -----------|JUMP THROW|--"				//06
alias  "mstts2" 	 	"setpos_exact 1391.968750 -929.076477 -167.968750;setang -9.171636 1.796261 0.000000"
alias  "mstts" 	 		"setpos_exact 1391.968750 -929.803223 -167.968750;setang -6.253115 -152.826279 0.000000"
alias  "echo_mswotp" 	"echo T Smoke |07-33| Window, from Outside T Palace----|RUN THROW|--"				//07
alias  "mswotp2" 	  	"setpos_exact 1391.968750 -1010.762695 -167.968750;setang -9.084333 0.807035 0.000000"
alias  "mswotp" 	  	"setpos_exact 1391.968750 -1010.762695 -167.968750;setang -42.499897 172.100479 0.000000"
alias  "echo_msctrtp"	"echo T Smoke |08-33|CT ramp, from Outside T Palace----|THROW|--"					//08
alias  "msctrtp2"		"setpos_exact 1088.200562 -1015.844177 -258.077484;setang -4.744215 137.909973 0.000000"
alias  "msctrtp"		"setpos_exact 1087.604248 -1016.439941 -258.156769;setang -31.444899 -147.408783 0.000000"
alias  "echo_msstr" 	"echo T Smoke |09-33| Stairs, from T Roof -------------|THROW|--"					//09
alias  "msstr2" 	 	"setpos_exact 1148.054321 -1183.968750 -205.571716;setang 48.568459 -90.253769 0.000000"
alias  "msstr" 	 		"setpos_exact 1148.054321 -1183.968750 -205.571716;setang -43.821823 -165.295059 0.000000"
alias  "echo_mswtr" 	"echo T Smoke |10-33| Window, from T Roof -------------|JUMP THROW bind|--"			//10
alias  "mswtr2" 	 	"setpos_exact 1127.968750 -1199.987061 -108.968750;setang 88.985260 -2.274946 0.000000"
alias  "mswtr" 	 		"setpos_exact 1127.968750 -1199.987061 -108.968750;setang -26.517317 166.827408 0.000000"
alias  "echo_msadtr" 	"echo T Smoke |11-33| A Default from T Roof -----------|THROW|--"					//11
alias  "msadtr2" 	 	"setpos_exact 814.968750 -1271.999268 -108.968750;setang 75.404297 -0.113796 0.000000"
alias  "msadtr" 	 	"setpos_exact 814.968750 -1271.999268 -108.968750;setang -33.141018 -149.385712 0.000000"
alias  "echo_mscjtr" 	"echo T Smoke |12-33| Connector/Jungle, from T Roof----|THROW|--"					//12
alias  "mscjtr2" 	 	"setpos_exact 815.968750 -1457.246582 -108.968750;setang -18.750147 2.064159 0.000000"
alias  "mscjtr" 	 	"setpos_exact 815.968750 -1457.559814 -108.968750;setang -27.558306 -174.413818 0.000000"
alias  "echo_msubtr" 	"echo T Smoke |13-33| Under Balc, from T Roof ---------|THROW|--"					//13
alias  "msubtr2" 	 	"setpos_exact 814.982239 -1548.973755 -108.968750;setang 74.392799 -26.007132 0.000000"
alias  "msubtr" 	 	"setpos_exact 814.982239 -1548.973755 -108.968750;setang -27.943707 163.484100 0.000000"
alias  "echo_msowtr" 	"echo T Smoke |14-33| One way, from T Ramp ------------|THROW|--"					//14
alias  "msowtr2" 	 	"setpos_exact 457.981079 -1711.983154 -240.955612;setang 72.700287 -38.687504 0.000000"
alias  "msowtr" 	 	"setpos_exact 457.987610 -1711.968750 -240.958862;setang -10.307006 133.163147 0.000000"
alias  "echo_msst"		"echo T Smoke |15-33| Stairs, from Tetris -------------|JUMP THROW|--"				//15
alias  "msst2"			"setpos_exact -91.093842 -1418.031250 -115.968750;setang 62.621960 149.832581 0.000000"
alias  "msst"			"setpos_exact -91.093842 -1418.031250 -115.968750;setang -31.808268 -62.421551 0.000000"
alias  "echo_msctrt" 	"echo T Smoke |16-33| CT Ramp, from Tetris ------------|THROW|--"					//16
alias  "msctrt2" 	 	"setpos_exact -91.093834 -1418.031250 -115.968750;setang 75.010666 159.638641 0.000000"
alias  "msctrt" 	 	"setpos_exact -91.093834 -1418.031250 -115.968750;setang -28.189722 -114.155800 0.000000"
alias  "echo_msjtm" 	"echo T Smoke |17-33| Jungle, from Top Mid ------------|JUMP THROW|--"				//17
alias  "msjtm2" 	 	"setpos_exact 394.613220 338.657410 -251.968750;setang 71.736237 -43.562408 0.000000"
alias  "msjtm" 	 		"setpos_exact 394.470245 338.514435 -251.968750;setang -34.658886 -124.566277 0.000000"
alias  "echo_msctm" 	"echo T Smoke |18-33| Connector, from Top Mid ---------|JUMP THROW bind|--"			//18
alias  "msctm2" 	 	"setpos_exact 399.577515 280.378296 -254.609146;setang 74.164757 27.911530 0.000000"
alias  "msctm" 	 		"setpos_exact 399.575165 280.404907 -254.607193;setang -39.485470 -129.980133 0.000000"
alias  "echo_msstm" 	"echo T Smoke |19-33| Short, from Top Mid -------------|RUN THROW|--"				//19
alias  "msstm2" 	 	"setpos_exact 399.998444 5.000257 -203.814362;setang 1.282400 2.513284 0.000000"
alias  "msstm" 	 		"setpos_exact 399.998444 4.656666 -203.629364;setang -22.060497 -134.482208 0.000000"
alias  "echo_msowtm" 	"echo T Smoke |20-33| One Way, from Top Mid -----------|R-CLICK|--"					//20
alias  "msowtm2" 	 	"setpos_exact 370.031250 -720.246643 -162.496857;setang 73.770622 -178.351517 0.000000"
alias  "msowtm" 	 	"setpos_exact 370.031250 -720.246643 -162.496857;setang 35.333359 124.099579 0.000000"
alias  "echo_msmwta"	"echo T Smoke |21-33| Market Window, from T Apps-------|THROW|--"					//21
alias  "msmwta2"		"setpos_exact -160.031250 887.968750 -135.328125;setang 62.863914 44.933872 0.000000"
alias  "msmwta"			"setpos_exact -160.031250 887.968750 -135.328125;setang -50.616238 -146.824265 0.000000"
alias  "echo_mssta" 	"echo T Smoke |22-33| Short, from T Apps --------------|THROW|--"					//22
alias  "mssta2" 	 	"setpos_exact -160.031250 887.968750 -135.328125;setang 70.767838 44.904778 0.000000"
alias  "mssta" 	 		"setpos_exact -160.031250 887.968750 -135.328125;setang -44.269619 -134.435654 0.000000"
alias  "echo_msvta" 	"echo T Smoke |23-33| Van, from T Apps ----------------|JUMP THROW bind|--"			//23
alias  "msvta2" 		"setpos_exact -190.746414 695.619873 -71.968750;setang 89.000000 -0.935475 0.000000"
alias  "msvta" 	 		"setpos_exact -190.746414 695.619873 -71.968750;setang -20.864975 179.318863 0.000000"
alias  "echo_mscs"	 	"echo T Smoke |24-33| Cat, from Stairs ----------------|CROUCH THROW|--"			//24
alias  "mscs2" 	  		"setpos_exact -452.378693 479.968750 -130.881561;setang 19.167377 91.278503 0.000000"
alias  "mscs" 	 		"setpos_exact -452.342682 479.968750 -130.857544;setang -76.258324 -132.324112 0.000000"
alias  "echo_msba" 		"echo T Smoke |25-33| Bench, From Apps ----------------|THROW|--"					//25
alias  "msba2" 			"setpos_exact -540.848022 520.031250 -81.355789;setang 27.964277 -88.023537 0.000000"
alias  "msba" 	 		"setpos_exact -540.848022 520.031250 -81.355789;setang -41.055069 -178.922836 0.000000"
alias  "echo_mswa" 		"echo T Smoke |26-33| Window, from Apps ---------------|THROW|--"					//26
alias  "mswa2" 	 		"setpos_exact -624.165833 615.968750 -78.971527;setang 30.469320 89.491890 0.000000"
alias  "mswa" 	 	 	"setpos_exact -624.243530 615.992065 -78.969345;setang -51.595604 -109.421127 0.000000"
alias  "echo_msmda" 	"echo T Smoke |27-33| Market Door, from Apps ----------|THROW|--"					//27
alias  "msmda2" 	 	"setpos_exact -736.002686 623.971558 -75.968750;setang 16.230545 90.355301 0.000000"
alias  "msmda" 			"setpos_exact -736.002686 623.971558 -75.968750;setang -51.085140 -165.188309 0.000000"
alias  "echo_msmwa"	 	"echo T Smoke |28-33| Market Window, from Apps --------|JUMP THROW|--"				//28
alias  "msmwa2"			"setpos_exact -835.315674 615.069824 -79.113701;setang 24.454559 93.295158 0.000000"
alias  "msmwa"			"setpos_exact -835.315674 615.069824 -79.113701;setang -63.836887 -146.755844 0.000000"
alias  "echo_ms2aa" 	"echo T Smoke |29-33| 2nd Arch, from Apps -------------|JUMP THROW|--"				//29
alias  "ms2aa2" 	  	"setpos_exact -840.438599 522.031250 -78.349075;setang 62.872765 -89.676865 0.000000"
alias  "ms2aa" 	  		"setpos_exact -840.438599 522.031250 -78.349075;setang -53.255424 143.843109 0.000000"
alias  "echo_msowa" 	"echo T Smoke |30-33| One Way, from Apps --------------|THROW or R-CLICK|--"		//30
alias  "msowa2" 	 	"setpos_exact -1183.968750 599.985596 -35.968750;setang 70.509300 134.863800 0.000000"
alias  "msowa" 	 		"setpos_exact -1183.968750 599.985596 -35.968750;setang 64.729622 71.990685 0.000000"
alias  "echo_ms1aa" 	"echo T Smoke |31-33| 1st Arch, from Apps -------------|THROW|--"					//31
alias  "ms1aa2" 	 	"setpos_exact -1367.987061 815.968750 -79.968750;setang 74.202049 116.551651 0.000000"
alias  "ms1aa" 	 		"setpos_exact -1367.974121 815.985413 -79.968750;setang -3.707352 -160.488846 0.000000"
alias  "echo_msmwv" 	"echo T Smoke |32-33| Market Window, from Van ---------|THROW|--"					//32
alias  "msmwv2" 	 	"setpos_exact -2325.227783 811.777039 -119.841331;setang 61.432606 157.003433 0.000000"
alias  "msmwv" 	 		"setpos_exact -2325.210693 811.778748 -119.840912;setang -16.420952 -68.685692 0.000000"
alias  "echo_msowmw" 	"echo T Smoke |33-33| One Way Market Window -----------|THROW|--"					//33
alias  "msowmw2" 	  	"setpos_exact -2599.970215 535.985596 -159.968750;setang 70.469215 134.973541 0.000000"
alias  "msowmw" 	 	"setpos_exact -2599.970215 535.985596 -159.968750;setang -16.582365 -50.818062 0.000000"
//1-10 CT SMOKE mirage 
alias  "echo_mstrcts"	"echo CT Smoke |01-10| T-Ramp, from CT Spawn ----------|JUMP THROW bind|"			//01
alias  "mstrcts2"		"setpos_exact -2026.397583 -2029.968750 -299.120270;setang 70.258400 -131.426178 0.000000"
alias  "mstrcts"		"setpos_exact -2026.397583 -2029.968750 -299.120270;setang -15.312100 12.573707 0.000000"
alias  "echo_msowt"		"echo CT Smoke |02-10| One Way, from Ticket -----------|R-CLICK|--"					//02
alias  "msowt2"			"setpos_exact -964.056885 -2489.520264 -167.968750;setang 69.294586 12.932003 0.000000"
alias  "msowt"			"setpos_exact -964.056885 -2489.520264 -167.968750;setang -41.926632 -10.765607 0.000000"
alias  "echo_mstrctr"	"echo CT Smoke |03-10| T Ramp, from CT Ramp -----------|THROW|--"					//03
alias  "mstrctr2"		"setpos_exact -879.972961 -2264.021484 -171.081177;setang 67.877930 143.971954 0.000000"
alias  "mstrctr"		"setpos_exact -879.972961 -2264.021484 -171.081177;setang -8.777997 33.916443 0.000000"
alias  "echo_mstras"	"echo CT Smoke |04-10| T Ramp, from A Site ------------|THROW|--"					//04
alias  "mstras2"		"setpos_exact -554.968750 -2103.674561 -179.968750;setang 50.959068 154.154419 0.000000"
alias  "mstras"			"setpos_exact -554.984802 -2103.675781 -179.968750;setang -16.105209 41.075729 0.000000"
alias  "echo_mstrj"		"echo CT Smoke |05-10| T Ramp, from Jungle ------------|THROW|--"					//05
alias  "mstrj2"			"setpos_exact -1119.999268 -1527.054443 -156.072006;setang 69.896034 -133.383484 0.000000"
alias  "mstrj"			"setpos_exact -1119.999268 -1527.054443 -156.072006;setang -12.821458 0.171871 0.000000"
alias  "echo_msowc"		"echo CT Smoke |06-10| One Way Connector --------------|THROW or R-CLICK|--"		//06
alias  "msowc2"			"setpos_exact -807.968750 -1152.031250 -120.175369;setang 69.246780 134.967285 0.000000"
alias  "msowc"			"setpos_exact -807.968750 -1152.031250 -120.175369;setang 29.502045 12.667312 0.000000"
alias  "echo_msowuc"	"echo CT Smoke |07-10| One Way Underpass --------------|THROW|--"					//07
alias  "msowuc2"		"setpos_exact -668.632385 -1290.048584 -167.968750;setang 89.000000 89.105988 0.000000"
alias  "msowuc"			"setpos_exact -668.632385 -1290.048584 -167.968750;setang 17.813030 98.444962 0.000000"
alias  "echo_msowlw"	"echo CT Smoke |08-10| One Way, from Left Window ------|THROW|--"					//08
alias  "msowlw2"		"setpos_exact -1209.077637 -873.270813 -167.968750;setang 61.689095 109.456398 0.000000"
alias  "msowlw"			"setpos -1209.077515 -873.270447 -167.90618899999998;setang -48.526600 67.790833 0.000000"
alias  "echo_msowrw"	"echo CT Smoke |09-10| One Way, from Right Window -----|THROW|--"					//09
alias  "msowrw2"		"setpos_exact -1120.031250 -456.004517 -167.968750;setang 70.659401 45.272419 0.000000"
alias  "msowrw"			"setpos_exact -1120.031250 -456.004517 -167.968750;setang 54.415966 -81.427071 0.000000"
alias  "echo_msabs"		"echo CT Smoke |10-10| Apps, from B Site --------------|THROW|--"					//10
alias  "msabs2"			"setpos_exact -2415.969238 -115.757309 -157.970886;setang 70.300476 127.208618 0.000000"
alias  "msabs"			"setpos_exact -2415.997803 -115.757294 -157.968765;setang -28.166698 44.120396 0.000000"
//1-7 T MOLOTOV mirage
alias  "echo_mmwtm"		"echo T Molotov |01-07| Window, from Top Mid ----------|RUN THROW|--"				//01
alias  "mmwtm2"			"setpos_exact 399.968750 -120.581726 -165.968750;setang 76.743553 1.947467 0.000000"
alias  "mmwtm"			"setpos_exact 399.968750 -120.581726 -165.968750;setang -17.011511 -153.078094 0.000000"
alias  "echo_mmtbtr"	"echo T Molotov |02-07| Tripple Bench, from T Roof-----|RUN JUMP THROW bind|"		//02
alias  "mmtbtr2"		"setpos_exact 977.692505 -1184.937866 -108.968750;setang 89.000000 89.666458 0.000000"
alias  "mmtbtr"			"setpos_exact 977.692505 -1184.937866 -108.968750;setang 6.070953 -154.769165 0.000000"
alias  "echo_mmstr"		"echo T Molotov |03-07| Sandwitch, from T Roof --------|THROW|--"					//03
alias  "mmstr2"			"setpos_exact 831.956238 -1255.190430 -108.968750;setang 75.580872 -90.103035 0.000000"
alias  "mmstr"			"setpos_exact 832.009155 -1253.968750 -108.968750;setang -20.065149 -165.148087 0.000000"
alias  "echo_mmdtr"		"echo T Molotov |04-07| Default, from T Ramp ----------|RUN THROW|--"				//04
alias  "mmdtr2"			"setpos_exact 479.291870 -1556.031250 -251.611008;setang 77.689804 88.052612 0.000000"
alias  "mmdtr"			"setpos_exact 479.269958 -1556.031250 -251.600052;setang -9.289508 -174.577820 0.000000"
alias  "echo_mmtt"		"echo T Molotov |05-07| tripple, from Tetris ----------|THROW|--"					//05
alias  "mmtt2"			"setpos_exact -31.916777 -1418.005371 -167.968750;setang 67.938873 143.344238 0.000000"
alias  "mmtt"			"setpos_exact -31.432693 -1418.005371 -167.968750;setang -19.768339 -138.115036 0.000000"
alias  "echo_mmfnt"		"echo T Molotov |06-07| Firebox/Ninja, from Tetris ----|THROW|--"					//06
alias  "mmfnt2"			"setpos_exact -91.094994 -1418.009155 -115.968750;setang 48.044342 159.738388 0.000000"
alias  "mmfnt"			"setpos_exact -91.094994 -1418.009155 -115.968750;setang -11.335484 -102.868759 0.000000"
alias  "echo_mmttb"		"echo T Molotov |07-07| Ticket Booth, from Tetris -----|JUMP THROW bind|--"			//07
alias  "mmttb2"			"setpos_exact -31.915421 -1418.031250 -167.968750;setang 63.007778 153.290558 0.000000"
alias  "mmttb"			"setpos_exact -31.915422 -1418.031250 -167.968750;setang 1.746532 -127.915695 0.000000"
//1-2 CT MOLOTOV mirage
alias  "echo_mmtd"		"echo CT Molotov |01-02| Tetris, from Default ---------|THROW|--"					//01
alias  "mmtd2"			"setpos_exact -364.996552 -2173.031250 -176.187897;setang 7.182738 53.938148 0.000000"
alias  "mmtd"			"setpos_exact -364.996552 -2173.031250 -176.187897;setang -26.004026 44.655296 0.000000"
alias  "echo_mmtud"		"echo CT Molotov |02-02| Tetris, from Under Balc ------|THROW|--"					//02
alias  "mmtud2"			"setpos_exact 150.968964 -2071.993408 -167.968750;setang 70.902267 -46.215267 0.000000"
alias  "mmtud"			"setpos_exact 150.968964 -2071.993408 -167.968750;setang -8.167507 117.405945 0.000000"
//1-5 T FLASH  mirage
alias  "echo_mfmtm"		"echo T Flash |01-05|  Mid, from Top Mid --------------|THROW or R-CLICK|--"		//01
alias  "mfmtm2"			"setpos_exact 224.031250 121.518646 -234.490799;setang 50.871323 -179.235046 0.000000"
alias  "mfmtm"			"setpos_exact 224.031250 121.364159 -234.449738;setang -45.541031 -95.531487 0.000000"
alias  "echo_mfctm"		"echo T Flash |02-05| Connector, from Top Mid ---------|THROW or R-CLIKC|--"		//02
alias  "mfctm2"			"setpos_exact 343.299561 -621.621582 -163.438690;setang 61.005878 -177.074936 0.000000"
alias  "mfctm"			"setpos_exact 343.299622 -621.621582 -163.440735;setang -14.388947 -171.282501 0.000000"
alias  "echo_mfbsc"		"echo T Flash |03-05| B Site, from cat ----------------|THROW or R-CLICK|--"		//03
alias  "mfbsc2"			"setpos_exact -944.718811 -119.968750 -167.968750;setang 76.017532 -90.208946 0.000000"
alias  "mfbsc"			"setpos_exact -944.555054 -119.968750 -167.968750;setang -30.245752 26.387146 0.000000"
alias  "echo_mfva"		"echo T Flash |04-05| Van, from Apps-------------------|STEP THROW|--"				//04
alias  "mfva2"			"setpos_exact -1165.968750 570.480408 -79.968750;setang 89.000000 -179.018921 0.000000"
alias  "mfva"			"setpos_exact -1165.968750 570.480408 -79.968750;setang -3.367111 -80.816711 0.000000"
alias  "echo_mfasg"		"echo T Flash |05-05| Apps, from Stairs GOD------------|THROW|--"					//05
alias  "mfasg2"			"setpos_exact -469.398102 454.355377 -142.227844;setang 89.000000 -0.855068 0.000000"
alias  "mfasg"			"setpos_exact -469.398102 454.355377 -142.227844;setang -8.072797 167.946579 0.000000"
//1-12 CT FLASH mirage
alias  "echo_mftrub"	"echo CT Flash |01-12| T Ramp, from Under Balc---------|THROW|--"					//01
alias  "mftrub2"		"setpos_exact 150.968964 -1914.031250 -167.968750;setang 69.493843 46.276314 0.000000"
alias  "mftrub"			"setpos_exact 150.973114 -1914.007568 -167.968750;setang -39.353500 -108.978981 0.000000"
alias  "echo_mftb"		"echo CT Flash |02-12| Tetris, from Balc --------------|THROW or R-CLICK|--"		//02
alias  "mftb2"			"setpos_exact 150.968964 -1914.024658 -39.968750;setang 64.031326 48.328995 0.000000"
alias  "mftb"			"setpos_exact 150.968964 -1914.024658 -39.968750;setang -80.323120 -163.431320 0.000000"
alias  "echo_mfpb"		"echo CT Flash |03-12| Palace, from Balc --------------|WALK THROW|--"				//03
alias  "mfpb2"			"setpos_exact 150.968964 -2071.970215 -37.968750;setang 68.214027 -39.771870 0.000000"
alias  "mfpb"			"setpos_exact 150.968964 -2071.992920 -37.968750;setang -10.082555 103.887718 0.000000"
alias  "echo_mfass"		"echo CT Flash |04-12| A Site, from Stairs ------------|THROW|--"					//04
alias  "mfass2"			"setpos_exact -496.000061 -1392.280762 -114.942337;setang 89.000000 0.477311 0.000000"
alias  "mfass"			"setpos_exact -496.000061 -1392.272095 -114.942337;setang -47.817543 93.066177 0.000000"
alias  "echo_mfcs"		"echo CT Flash |05-12| Connector, from Stairs----------|THROW|--"					//05
alias  "mfcs2"			"setpos_exact -496.031250 -1309.031250 -159.968750;setang 69.526917 48.323627 0.000000"
alias  "mfcs"			"setpos_exact -496.031250 -1309.031250 -159.968750;setang -65.176048 -10.261290 0.000000"
alias  "echo_mfmw"		"echo CT Flash |06-12| Mid, from Window ---------------|CROUCH THROW--"				//06
alias  "mfmw2"			"setpos_exact -1120.006836 -967.656921 -167.968750;setang 64.138550 -60.116333 0.000000"
alias  "mfmw"			"setpos_exact -1120.008179 -967.656860 -167.968750;setang -14.785339 89.780838 0.000000"
alias  "echo_mfuw"		"echo CT Flash |07-12| Underpass, from Window ---------|CROUCH R-CLICK or THROW|--"	//07
alias  "mfuw2"			"setpos_exact -1196.711792 -856.031250 -167.968750;setang 68.769051 140.995483 0.000000"
alias  "mfuw"			"setpos_exact -1196.711792 -856.031250 -167.968750;setang 4.661007 66.157684 0.000000"
alias  "echo_mfbss"		"echo CT Flash |08-12| B Site, from short -------------|THROW|--"					//08
alias  "mfbss2"			"setpos_exact -944.555054 -119.968750 -167.968750;setang 76.164024 -90.231651 0.000000"
alias  "mfbss"			"setpos_exact -944.555054 -119.968750 -167.968750;setang -30.245752 26.387146 0.000000"
alias  "echo_mfabs"		"echo CT Flash |09-12| Apps, from B Site --------------|THROW|--"					//09
alias  "mfabs2"			"setpos_exact -1789.925537 -231.968750 -166.772339;setang 19.278208 -90.422020 0.000000"
alias  "mfabs"			"setpos_exact -1789.925537 -231.968750 -166.772339;setang -20.757872 80.150261 0.000000"
alias  "echo_mfavb"		"echo CT Flash |10-12| Apps, from Van Box--------------|THROW or R-CLICK|--"		//10
alias  "mfavb2"			"setpos_exact -2391.907227 597.266907 -127.968750;setang 57.027771 126.254143 0.000000"
alias  "mfavb"			"setpos_exact -2391.907227 597.266907 -127.968750;setang -23.686562 16.481817 0.000000"
alias  "echo_mfav"		"echo CT Flash |11-12| Apps, from Van -----------------|THROW|--"					//11
alias  "mfav2"			"setpos_exact -2114.021484 830.583069 -121.578720;setang 63.683712 54.639519 0.000000"
alias  "mfav"			"setpos_exact -2114.031250 830.582214 -121.579018;setang -69.529404 38.815456 0.000000"
alias  "echo_mfaa"		"echo CT Flash |12-12| Apps, from Apps-----------------|R-CLICK|--"					//12
alias  "mfaa2"			"setpos_exact -1952.000122 849.968750 -23.968750;setang 75.301163 46.856827 0.000000"
alias  "mfaa"			"setpos_exact -1952.000122 849.966614 -23.968750;setang -76.560158 -89.940926 0.000000"


//1-33 T SMOKE Lineup mirage
alias  "MTSL1"   "echo_mscwts;mscwts;	bind kp_ins MTSP1;  alias MTSLU MTSL2;  alias MTSLD MTSL33"
alias  "MTSL2"   "echo_mswts;mswts;		bind kp_ins MTSP2;  alias MTSLU MTSL3;  alias MTSLD MTSL1"
alias  "MTSL3"   "echo_mscts;mscts;		bind kp_ins MTSP3;  alias MTSLU MTSL4;  alias MTSLD MTSL2"
alias  "MTSL4"   "echo_mssts;mssts;		bind kp_ins MTSP4;  alias MTSLU MTSL5;  alias MTSLD MTSL3"
alias  "MTSL5"   "echo_msctrts;msctrts;	bind kp_ins MTSP5;  alias MTSLU MTSL6;  alias MTSLD MTSL4"
alias  "MTSL6"   "echo_mstts;mstts;		bind kp_ins MTSP6;  alias MTSLU MTSL7;  alias MTSLD MTSL5"
alias  "MTSL7"   "echo_mswotp;mswotp;	bind kp_ins MTSP7;  alias MTSLU MTSL8;  alias MTSLD MTSL6"
alias  "MTSL8"   "echo_msctrtp;msctrtp;	bind kp_ins MTSP8;  alias MTSLU MTSL9;  alias MTSLD MTSL7"
alias  "MTSL9"   "echo_msstr;msstr;		bind kp_ins MTSP9;  alias MTSLU MTSL10; alias MTSLD MTSL8"
alias  "MTSL10"  "echo_mswtr;mswtr;		bind kp_ins MTSP10; alias MTSLU MTSL11; alias MTSLD MTSL9"
alias  "MTSL11"  "echo_msadtr;msadtr;	bind kp_ins MTSP11; alias MTSLU MTSL12; alias MTSLD MTSL10"
alias  "MTSL12"  "echo_mscjtr;mscjtr;	bind kp_ins MTSP12; alias MTSLU MTSL13; alias MTSLD MTSL11"
alias  "MTSL13"  "echo_msubtr;msubtr;	bind kp_ins MTSP13; alias MTSLU MTSL14; alias MTSLD MTSL12"
alias  "MTSL14"  "echo_msowtr;msowtr;	bind kp_ins MTSP14; alias MTSLU MTSL15; alias MTSLD MTSL13"
alias  "MTSL15"  "echo_msst;msst;		bind kp_ins MTSP15; alias MTSLU MTSL16; alias MTSLD MTSL14"
alias  "MTSL16"  "echo_msctrt;msctrt;	bind kp_ins MTSP16; alias MTSLU MTSL17; alias MTSLD MTSL15"
alias  "MTSL17"  "echo_msjtm;msjtm;		bind kp_ins MTSP17; alias MTSLU MTSL18; alias MTSLD MTSL16"
alias  "MTSL18"  "echo_msctm;msctm;		bind kp_ins MTSP18; alias MTSLU MTSL19; alias MTSLD MTSL17"
alias  "MTSL19"  "echo_msstm;msstm;		bind kp_ins MTSP19; alias MTSLU MTSL20; alias MTSLD MTSL18"
alias  "MTSL20"  "echo_msowtm;msowtm;	bind kp_ins MTSP20; alias MTSLU MTSL21; alias MTSLD MTSL19"
alias  "MTSL21"  "echo_msmwta;msmwta;	bind kp_ins MTSP21; alias MTSLU MTSL22; alias MTSLD MTSL20"
alias  "MTSL22"  "echo_mssta;mssta;		bind kp_ins MTSP22; alias MTSLU MTSL23; alias MTSLD MTSL21"
alias  "MTSL23"  "echo_msvta;msvta;		bind kp_ins MTSP23; alias MTSLU MTSL24; alias MTSLD MTSL22"
alias  "MTSL24"  "echo_mscs;mscs;		bind kp_ins MTSP24; alias MTSLU MTSL25; alias MTSLD MTSL23"
alias  "MTSL25"  "echo_msba;msba;		bind kp_ins MTSP25; alias MTSLU MTSL26; alias MTSLD MTSL24"
alias  "MTSL26"  "echo_mswa;mswa;		bind kp_ins MTSP26; alias MTSLU MTSL27; alias MTSLD MTSL25"
alias  "MTSL27"  "echo_msmda;msmda;		bind kp_ins MTSP27; alias MTSLU MTSL28; alias MTSLD MTSL26"
alias  "MTSL28"  "echo_msmwa;msmwa;		bind kp_ins MTSP28; alias MTSLU MTSL29; alias MTSLD MTSL27"
alias  "MTSL29"  "echo_ms2aa;ms2aa;		bind kp_ins MTSP29; alias MTSLU MTSL30; alias MTSLD MTSL28"
alias  "MTSL30"  "echo_msowa;msowa;		bind kp_ins MTSP30; alias MTSLU MTSL31; alias MTSLD MTSL29"
alias  "MTSL31"  "echo_ms1aa;ms1aa;		bind kp_ins MTSP31; alias MTSLU MTSL32; alias MTSLD MTSL30"
alias  "MTSL32"  "echo_msmwv;msmwv;		bind kp_ins MTSP32; alias MTSLU MTSL33; alias MTSLD MTSL31"
alias  "MTSL33"  "echo_msowmw;msowmw;	bind kp_ins MTSP33; alias MTSLU MTSL1;  alias MTSLD MTSL32"
//1-33 T SMOKE Position mirage
alias  "MTSP1"   "mscwts2;	bind kp_ins MTSL1"
alias  "MTSP2"   "mswts2;	bind kp_ins MTSL2"
alias  "MTSP3"   "mscts2;	bind kp_ins MTSL3"
alias  "MTSP4"   "mssts2;	bind kp_ins MTSL4"
alias  "MTSP5"   "msctrts2;	bind kp_ins MTSL5"
alias  "MTSP6"   "mstts2;	bind kp_ins MTSL6"
alias  "MTSP7"   "mswotp2;	bind kp_ins MTSL7"
alias  "MTSP8"   "msctrtp2;	bind kp_ins MTSL8"
alias  "MTSP9"   "msstr2;	bind kp_ins MTSL9"
alias  "MTSP10"  "mswtr2;	bind kp_ins MTSL10"
alias  "MTSP11"  "msadtr2;	bind kp_ins MTSL11"
alias  "MTSP12"  "mscjtr2;	bind kp_ins MTSL12"
alias  "MTSP13"  "msubtr2;	bind kp_ins MTSL13"
alias  "MTSP14"  "msowtr2;	bind kp_ins MTSL14"
alias  "MTSP15"  "msst2;	bind kp_ins MTSL15"
alias  "MTSP16"  "msctrt2;	bind kp_ins MTSL16"
alias  "MTSP17"  "msjtm2;	bind kp_ins MTSL17"
alias  "MTSP18"  "msctm2;	bind kp_ins MTSL18"
alias  "MTSP19"  "msstm2;	bind kp_ins MTSL19"
alias  "MTSP20"  "msowtm2;	bind kp_ins MTSL20"
alias  "MTSP21"  "msmwta2;	bind kp_ins MTSL21"
alias  "MTSP22"  "mssta2;	bind kp_ins MTSL22"
alias  "MTSP23"  "msvta2;	bind kp_ins MTSL23"
alias  "MTSP24"  "mscs2;	bind kp_ins MTSL24"
alias  "MTSP25"  "msba2;	bind kp_ins MTSL25"
alias  "MTSP26"  "mswa2;	bind kp_ins MTSL26"
alias  "MTSP27"  "msmda2;	bind kp_ins MTSL27"
alias  "MTSP28"  "msmwa2;	bind kp_ins MTSL28"
alias  "MTSP29"  "ms2aa2;	bind kp_ins MTSL29"
alias  "MTSP30"  "msowa2;	bind kp_ins MTSL30"
alias  "MTSP31"  "ms1aa2; 	bind kp_ins MTSL31"
alias  "MTSP32"  "msmwv2;	bind kp_ins MTSL32"
alias  "MTSP33"  "msowmw2;	bind kp_ins MTSL33"
//1-10 CT SMOKE Lineup mirage
alias  "MCTSL1"  "echo_mstrcts;mstrcts;	bind kp_ins MCTSP1; alias MCTSLU MCTSL2; alias MCTSLD MCTSL10"
alias  "MCTSL2"  "echo_msowt;msowt;		bind kp_ins MCTSP2; alias MCTSLU MCTSL3; alias MCTSLD MCTSL1"
alias  "MCTSL3"  "echo_mstrctr;mstrctr;	bind kp_ins MCTSP3; alias MCTSLU MCTSL4; alias MCTSLD MCTSL2"
alias  "MCTSL4"  "echo_mstras;mstras;	bind kp_ins MCTSP4; alias MCTSLU MCTSL5; alias MCTSLD MCTSL3"
alias  "MCTSL5"  "echo_mstrj;mstrj;		bind kp_ins MCTSP5; alias MCTSLU MCTSL6; alias MCTSLD MCTSL4"
alias  "MCTSL6"  "echo_msowc;msowc;		bind kp_ins MCTSP6; alias MCTSLU MCTSL7; alias MCTSLD MCTSL5"
alias  "MCTSL7"  "echo_msowuc;msowuc;	bind kp_ins MCTSP7; alias MCTSLU MCTSL8; alias MCTSLD MCTSL6"
alias  "MCTSL8"  "echo_msowlw;msowlw;	bind kp_ins MCTSP8; alias MCTSLU MCTSL9; alias MCTSLD MCTSL7"
alias  "MCTSL9"  "echo_msowrw;msowrw;	bind kp_ins MCTSP9; alias MCTSLU MCTSL10;alias MCTSLD MCTSL8"
alias  "MCTSL10" "echo_msabs;msabs;		bind kp_ins MCTSP10;alias MCTSLU MCTSL1; alias MCTSLD MCTSL9"
//1-10 CT SMOKE Position mirage
alias  "MCTSP1"  "mstrcts2;	bind kp_ins MCTSL1"
alias  "MCTSP2"  "msowt2;	bind kp_ins MCTSL2"
alias  "MCTSP3"  "mstrctr2;	bind kp_ins MCTSL3"
alias  "MCTSP4"  "mstras2;	bind kp_ins MCTSL4"
alias  "MCTSP5"  "mstrj2;	bind kp_ins MCTSL5"
alias  "MCTSP6"  "msowc2;	bind kp_ins MCTSL6"
alias  "MCTSP7"  "msowuc2;	bind kp_ins MCTSL7"
alias  "MCTSP8"  "msowlw2;	bind kp_ins MCTSL8"
alias  "MCTSP9"  "msowrw2;	bind kp_ins MCTSL9"
alias  "MCTSP10" "msabs2;	bind kp_ins MCTSL10"
//t smoke
alias MTSLU MTSL1
alias MTSLD MASTL1
//ct smoke
alias MCTSLU MCTSL1
alias MCTSLD MCTSL1


//1-7 T MOLOTOV Lineup mirage
alias  "MTML1"  "echo_mmwtm;mmwtm;	bind kp_ins MTMP1; alias MTMLU MTML2; alias MTMLD MTML7"
alias  "MTML2"  "echo_mmtbtr;mmtbtr;bind kp_ins MTMP2; alias MTMLU MTML3; alias MTMLD MTML1"
alias  "MTML3"  "echo_mmstr;mmstr;	bind kp_ins MTMP3; alias MTMLU MTML4; alias MTMLD MTML2"
alias  "MTML4"  "echo_mmdtr;mmdtr;	bind kp_ins MTMP4; alias MTMLU MTML5; alias MTMLD MTML3"
alias  "MTML5"  "echo_mmtt;mmtt;	bind kp_ins MTMP5; alias MTMLU MTML6; alias MTMLD MTML4"
alias  "MTML6"  "echo_mmfnt;mmfnt;	bind kp_ins MTMP6; alias MTMLU MTML7; alias MTMLD MTML5"
alias  "MTML7"  "echo_mmttb;mmttb;	bind kp_ins MTMP7; alias MTMLU MTML1; alias MTMLD MTML6"
//1-7 T MOLOTOV Position mirage
alias  "MTMP1"  "mmwtm2;	bind kp_ins MTML1"
alias  "MTMP2"  "mmtbtr2;	bind kp_ins MTML2"
alias  "MTMP3"  "mmstr2;	bind kp_ins MTML3"
alias  "MTMP4"  "mmdtr2;	bind kp_ins MTML4"
alias  "MTMP5"  "mmtt2;		bind kp_ins MTML5"
alias  "MTMP6"  "mmfnt2;	bind kp_ins MTML6"
alias  "MTMP7"  "mmttb2;	bind kp_ins MTML7"
//1-2 CT MOLOTOV Lineup mirage
alias  "MCTML1"  "echo_mmtd;mmtd;   bind kp_ins MCTMP1; alias MCTMLU MCTML2; alias MCTMLD MCTML2"
alias  "MCTML2"  "echo_mmtud;mmtud; bind kp_ins MCTMP2; alias MCTMLU MCTML1; alias MCTMLD MCTML1"
//1-2 CT MOLOTOV Position mirage
alias  "MCTMP1"  "mmtd2;	bind kp_ins MCTML1"
alias  "MCTMP2"  "mmtud2;	bind kp_ins MCTML2"
//t molotov
alias  "MTMLU" "MTML1"
alias  "MTMLD" "MTML1"
//ct molotov
alias  "MCTMLU" "MCTML1"
alias  "MCTMLD" "MCTML1"


//1-5 T FLASH Lineup mirage
alias  "MTFL1" "echo_mfmtm;mfmtm;	bind kp_ins MTFP1; alias MTFLU MTFL2; alias MTFLD MTFL5"
alias  "MTFL2" "echo_mfctm;mfctm;	bind kp_ins MTFP2; alias MTFLU MTFL3; alias MTFLD MTFL1"
alias  "MTFL3" "echo_mfbsc;mfbsc;	bind kp_ins MTFP3; alias MTFLU MTFL4; alias MTFLD MTFL2"
alias  "MTFL4" "echo_mfva;mfva;		bind kp_ins MTFP4; alias MTFLU MTFL5; alias MTFLD MTFL3"
alias  "MTFL5" "echo_mfasg;mfasg;	bind kp_ins MTFP5; alias MTFLU MTFL1; alias MTFLD MTFL4"
//1-4 T FLASH Position mirage
alias  "MTFP1" "mfmtm2; bind kp_ins MTFL1"
alias  "MTFP2" "mfctm2; bind kp_ins MTFL2"
alias  "MTFP3" "mfbsc2; bind kp_ins MTFL3"
alias  "MTFP4" "mfva2;  bind kp_ins MTFL4"
alias  "MTFP5" "mfasg2;	bind kp_ins MTFL5"
//1-12 CT FLASH Lineup mirage
alias  "MCTFL1"  "echo_mftrub;mftrub;	bind kp_ins MCTFP1;  alias MCTFLU MCTFL2;  alias MCTFLD MCTFL12"
alias  "MCTFL2"  "echo_mftb;mftb;		bind kp_ins MCTFP2;  alias MCTFLU MCTFL3;  alias MCTFLD MCTFL1"
alias  "MCTFL3"  "echo_mfpb;mfpb;		bind kp_ins MCTFP3;  alias MCTFLU MCTFL4;  alias MCTFLD MCTFL2"
alias  "MCTFL4"  "echo_mfass;mfass;		bind kp_ins MCTFP4;  alias MCTFLU MCTFL5;  alias MCTFLD MCTFL3"
alias  "MCTFL5"  "echo_mfcs;mfcs;		bind kp_ins MCTFP5;  alias MCTFLU MCTFL6;  alias MCTFLD MCTFL4"
alias  "MCTFL6"  "echo_mfmw;mfmw;		bind kp_ins MCTFP6;  alias MCTFLU MCTFL7;  alias MCTFLD MCTFL5"
alias  "MCTFL7"  "echo_mfuw;mfuw;		bind kp_ins MCTFP7;  alias MCTFLU MCTFL8;  alias MCTFLD MCTFL6"
alias  "MCTFL8"  "echo_mfbss;mfbss;		bind kp_ins MCTFP8;  alias MCTFLU MCTFL9;  alias MCTFLD MCTFL7"
alias  "MCTFL9"  "echo_mfabs;mfabs;		bind kp_ins MCTFP9;  alias MCTFLU MCTFL10; alias MCTFLD MCTFL8"
alias  "MCTFL10" "echo_mfavb;mfavb;		bind kp_ins MCTFP10; alias MCTFLU MCTFL11; alias MCTFLD MCTFL9"
alias  "MCTFL11" "echo_mfav;mfav;		bind kp_ins MCTFP11; alias MCTFLU MCTFL12; alias MCTFLD MCTFL10"
alias  "MCTFL12" "echo_mfaa;mfaa;		bind kp_ins MCTFP12; alias MCTFLU MCTFL1;  alias MCTFLD MCTFL11"
//1-12 CT FLASH Position mirage
alias  "MCTFP1"  "mftrub2;	bind kp_ins MCTFL1"
alias  "MCTFP2"  "mftb2;	bind kp_ins MCTFL2"
alias  "MCTFP3"  "mfpb2;	bind kp_ins MCTFL3"
alias  "MCTFP4"  "mfass2;	bind kp_ins MCTFL4"
alias  "MCTFP5"  "mfcs2;	bind kp_ins MCTFL5"
alias  "MCTFP6"  "mfmw2;	bind kp_ins MCTFL6"
alias  "MCTFP7"  "mfuw2;	bind kp_ins MCTFL7"
alias  "MCTFP8"  "mfbss2;	bind kp_ins MCTFL8"
alias  "MCTFP9"  "mfabs2;	bind kp_ins MCTFL9"
alias  "MCTFP10" "mfavb2;	bind kp_ins MCTFL10"
alias  "MCTFP11" "mfav2;	bind kp_ins MCTFL11"
alias  "MCTFP12" "mfaa2;	bind kp_ins MCTFL12"
//t flash mirage
alias  "MTFLU"  "MTFL1"
alias  "MTFLD"  "MTFL1"
//ct flash mirage
alias  "MCTFLU"  "MCTFL1"
alias  "MCTFLD"  "MCTFL1"



//1-23 T SMOKE cache
alias  "echo_cszts"		"echo T Smoke |01-20| Z, from T Spawn -----------------|RUN JUMP THROW|--"			//01
alias  "cszts2"			"setpos_exact 2643.349365 12.143652 1613.031250;setang 89.000000 -179.772446 0.000000"
alias  "cszts"			"setpos_exact 2643.454346 12.689742 1613.031250;setang -11.831539 -179.061951 0.000000"
alias  "echo_cshts"		"echo T Smoke |02-20| Highway, from T Spawn -----------|RUN JUMP THROW bind|--"		//02
alias  "cshts2"			"setpos_exact 2594.446045 107.968750 1613.031250;setang -75.659462 90.908577 0.000000"
alias  "cshts"			"setpos_exact 2594.446045 107.968750 1613.031250;setang -19.665329 157.951965 0.000000"
alias  "echo_cssts"		"echo T Smoke |03-20| Spool, from T Spawn -------------|JUMP THROW bind|--"			//03
alias  "cssts2"			"setpos_exact 2156.646973 -182.968750 1613.424194;setang 89.000000 -89.847458 0.000000"
alias  "cssts"			"setpos_exact 2156.646973 -182.968750 1613.424194;setang -16.633772 166.391449 0.000000"
alias  "echo_csrmg"		"echo T Smoke |04-20| Right Mid, from Garage ----------|THROW|--"					//04
alias  "csrmg2"			"setpos_exact 1711.968750 -71.968750 1614.031250;setang 69.951485 -43.408253 0.000000"
alias  "csrmg"			"setpos_exact 1711.968750 -71.968750 1614.031250;setang -10.560504 161.185349 0.000000"
alias  "echo_cslmg"		"echo T Smoke |05-20| Left Mid, from Garage -----------|THROW|--"					//05
alias  "cslmg2"			"setpos_exact 1711.974121 463.987732 1614.031250;setang 70.046570 43.111546 0.000000"
alias  "cslmg"			"setpos_exact 1711.974121 463.987732 1614.031250;setang -10.675973 -167.299591 0.000000"
alias  "echo_cstbt"		"echo T Smoke |06-20| Truck, from Big Truck -----------|JUMP THROW bind|--"			//06
alias  "cstbt2"			"setpos_exact 1810.816650 723.060730 1613.031250;setang 45.532227 52.016300 0.000000"
alias  "cstbt"			"setpos_exact 1810.816650 723.060730 1613.031250;setang -53.346001 159.919525 0.000000"
alias  "echo_cszl"		"echo T Smoke |07-20| Z, from Long --------------------|THROW|--"					//07
alias  "cszl2"			"setpos_exact 1160.711182 715.841675 1613.031250;setang 89.000000 -160.257477 0.000000"
alias  "cszl"			"setpos_exact 1160.711182 715.841675 1613.031250;setang -31.334572 -153.088974 0.000000"
alias  "echo_csowb"		"echo T Smoke |08-20| One Way boost -------------------|THROW|--"					//08
alias  "csowb2"			"setpos_exact 1037.031250 513.031250 1613.487671;setang 68.434029 -141.267242 0.000000"
alias  "csowb"			"setpos_exact 1037.031250 513.031250 1613.487671;setang -49.137814 104.639671 0.000000"
alias  "echo_cssl"		"echo T Smoke |09-20| Safe, from Long -----------------|THROW|--"					//09
alias  "cssl2"			"setpos_exact 1319.997070 1355.521484 1701.031250;setang 37.573845 0.610421 0.000000"
alias  "cssl"			"setpos_exact 1319.997070 1355.521484 1701.031250;setang -49.913193 157.243423 0.000000"
alias  "echo_cssfl"		"echo T Smoke |10-20| Safe/Fence, from Long -----------|THROW|--"					//10
alias  "cssfl2"			"setpos_exact 1319.992554 1520.380859 1701.031250;setang 89.000000 -171.871094 0.000000"
alias  "cssfl"			"setpos_exact 1319.968750 1520.395508 1701.031250;setang -57.751244 161.424835 0.000000"
alias  "echo_cscl"		"echo T Smoke |11-20| Cat, from Long ------------------|THROW|--"					//11
alias  "cscl2"			"setpos_exact 1319.968750 1578.756592 1701.031250;setang 60.981285 43.904327 0.000000"
alias  "cscl"			"setpos_exact 1319.992554 1578.756592 1701.031250;setang -50.903076 -167.315948 0.000000"
alias  "echo_csadl"		"echo T Smoke |12-20| A Default, from Long ------------|THROW|--"					//12
alias  "csadl2"			"setpos_exact 1319.968750 1601.899292 1737.482300;setang 60.730801 45.018734 0.000000"
alias  "csadl"			"setpos_exact 1319.997803 1601.899658 1737.482300;setang -47.685471 -174.764786 0.000000"
alias  "echo_csftl"		"echo T Smoke |13-20| Forklift/Truck, from Long -------|THROW|--"					//13
alias  "csftl2"			"setpos_exact 1269.968750 1612.968750 1751.519287;setang 69.624222 36.289768 0.000000"
alias  "csftl"			"setpos_exact 1269.968750 1612.968750 1751.519287;setang -62.982796 -175.346359 0.000000"
alias  "echo_csfl"		"echo T Smoke |14-20| Forklift, from Long -------------|THROW|--"					//14
alias  "csfl2"			"setpos_exact 1230.754150 1612.968750 1701.902466;setang 69.550011 40.835579 0.000000"
alias  "csfl"			"setpos_exact 1230.754150 1612.968750 1701.902466;setang -74.514435 -173.894516 0.000000"
alias  "echo_csftam"	"echo T Smoke |15-20| Forklift/Truck, from A Main -----|RUN THROW|--"				//15
alias  "csftam2"		"setpos_exact 766.968750 1238.347534 1702.031250;setang 89.000000 178.963440 0.000000"
alias  "csftam"			"setpos_exact 766.991394 1238.266479 1702.031250;setang -3.930409 123.895424 0.000000"
alias  "echo_csfts"		"echo T Smoke |16-20| Forklift/Truck, from Squeaky ----|RUN THROW|--"				//16
alias  "csfts2"			"setpos_exact 139.031250 2197.968750 1688.031250;setang 70.448586 134.783417 0.000000"
alias  "csfts"			"setpos_exact 139.031250 2197.968750 1688.031250;setang -6.040052 -60.836231 0.000000"
alias  "echo_csfs"		"echo T Smoke |17-20| Fence, from Squeaky -------------|Crouch THROW|--"			//17
alias  "csfs2"			"setpos_exact 154.413376 2096.080566 1688.031250;setang 89.000000 2.337884 0.000000"
alias  "csfs"			"setpos_exact 154.413376 2096.080566 1688.031250;setang 9.370919 -29.337667 0.000000"
alias  "echo_cscbm"		"echo T Smoke |18-20| Checkers, from B Main -----------|THROW|--"					//18
alias  "cscbm2"			"setpos_exact 837.785156 -872.015564 1614.031250;setang 67.045090 90.105881 0.000000"
alias  "cscbm"			"setpos_exact 837.744141 -872.015564 1614.031250;setang -15.362073 177.850555 0.000000"
alias  "echo_cstt"		"echo T Smoke |19-25| Tree, from Toxic ----------------|THROW|--"					//19
alias  "cstt2"			"setpos_exact 960.001221 -1463.968750 1644.031250;setang 59.456642 -152.017044 0.000000"
alias  "cstt"			"setpos_exact 960.031250 -1463.968750 1644.031250;setang -26.400745 162.851730 0.000000"
alias  "echo_csbdt"		"echo T Smoke |20-25| B Default, from Toxic -----------|THROW|--"					//20
alias  "csbdt2"			"setpos_exact 827.968750 -1463.968750 1614.031250;setang 58.507366 -33.793293 0.000000"
alias  "csbdt"			"setpos_exact 827.971313 -1463.968750 1614.031250;setang -21.995483 162.191437 0.000000"
alias  "echo_csnbt"		"echo T Smoke |21-23| New Box, from Toxic -------------|JUMP THROW bind|"			//21
alias  "csnbt2"			"setpos_exact 728.445251 -1463.968750 1614.031250;setang 13.505484 -89.306091 0.000000"
alias  "csnbt"			"setpos_exact 728.445251 -1463.968750 1614.031250;setang -34.550278 163.803665 0.000000"
alias  "echo_csht"		"echo T Smoke |21-25| Headshot, from Toxic ------------|THROW|--"					//22
alias  "cshst2"			"setpos_exact 827.999878 -1463.968750 1614.031250;setang 72.622864 -21.320288 0.000000"
alias  "cshst"			"setpos_exact 827.999878 -1463.968750 1614.031250;setang -27.291553 163.365860 0.000000"
alias  "echo_cshowt"	"echo T Smoke |21-25| Headshot One Way, from Toxic ----|THROW|--"					//23
alias  "cshsowt2"		"setpos_exact 827.968750 -1463.968750 1614.031250;setang 72.656639 -20.618563 0.000000"
alias  "cshsowt"		"setpos_exact 827.948181 -1463.968750 1614.031250;setang -25.822598 165.041870 0.000000"
//1-8 CT SMOKE cache
alias  "echo_csowz"		"echo CT Smoke |01-08|  One Way Z ---------------------|THROW|--"					//01
alias  "csowz2"			"setpos_exact -367.031250 116.565590 1663.031250;setang 75.915840 1.467142 0.000000"
alias  "csowz"			"setpos_exact -367.031250 116.565590 1663.031250;setang -0.198670 -170.005798 0.000000"
alias  "echo_csows"		"echo CT Smoke |02-08| One Way Spools -----------------|R-CLICK|--"					//02
alias  "csows2"			"setpos_exact -59.031250 548.683716 1628.393677;setang 25.332550 -67.013939 0.000000"
alias  "csows"			"setpos_exact -59.031250 548.683716 1628.393677;setang 7.989594 -83.784019 0.000000"
alias  "echo_csamt"		"echo CT Smoke |03-08| A Main, from Truck -------------|THROW|--"					//03
alias  "csamt2"			"setpos_exact -782.198486 1110.031250 1689.354492;setang 66.127274 -109.307503 0.000000"
alias  "csamt"			"setpos_exact -782.198059 1110.000366 1689.377075;setang -9.703021 24.963852 0.000000"
alias  "echo_csvtw"		"echo CT Smoke |04-08| Vents, from Truck wall ---------|RUN THROW|--"				//04
alias  "csvtw2"			"setpos_exact -996.968750 1440.254272 1691.119751;setang 57.029728 177.489426 0.000000"
alias  "csvtw"			"setpos_exact -996.979553 1440.231689 1691.119995;setang -33.181599 -46.326721 0.000000"
alias  "echo_csamq"		"echo CT Smoke |05-08| A Main, from Quad --------------|THROW|--"					//05
alias  "csamq2"			"setpos_exact -429.999695 2261.968750 1718.031250;setang 65.100502 134.952606 0.000000"
alias  "csamq"			"setpos_exact -429.968750 2261.986328 1718.031250;setang -1.766171 -30.807280 0.000000"
alias  "echo_csamf"		"echo CT Smoke |06-08| A Main, from Fence -------------|THROW|--"					//06
alias  "csamf2"			"setpos_exact -50.012558 2261.968750 1687.031250;setang 51.345249 52.961308 0.000000"
alias  "csamf"			"setpos_exact -50.012558 2261.968750 1687.031250;setang -18.612713 -64.612831 0.000000"
alias  "echo_csbmh"		"echo CT Smoke |07-08| B Main, from Heaven ------------|CROUCH THROW|--"			//07
alias  "csbmh2"			"setpos_exact -617.968750 -764.968750 1796.031250;setang 70.023354 -133.280106 0.000000"
alias  "csbmh"			"setpos_exact -617.968750 -764.940491 1796.031250;setang 12.638000 6.434308 0.000000"
alias  "echo_csowv"		"echo CT Smoke |08-08| One Way Vents ------------------|THROW|--"					//08
alias  "csowv2"			"setpos_exact 425.968750 -418.997192 1614.031250;setang 70.999825 -45.044708 0.000000"
alias  "csowv"			"setpos_exact 425.968750 -418.997192 1614.031250;setang -20.180223 83.582611 0.000000"
//1-8 T MOLOTOV cache
alias  "echo_cmsl"		"echo T Molotov |01-08| Sandbags, from Long -----------|RUN JUMP THROW|--"			//01
alias  "cmsl2"			"setpos_exact 1350.774658 975.997009 1618.031250;setang 79.405846 88.711006 0.000000"
alias  "cmsl"			"setpos_exact 1350.702637 975.997009 1618.031250;setang 2.589756 -140.584335 0.000000"
alias  "echo_cmvl"		"echo T Molotov |02-08| Vents, from Long --------------|RUN THROW|--"				//02
alias  "cmvl2"			"setpos_exact 1261.099487 1321.491089 1701.031250;setang 88.985260 -93.859039 0.000000"
alias  "cmvl"			"setpos_exact 1261.099487 1321.491089 1701.031250;setang -18.200563 -115.368744 0.000000"
alias  "echo_cmsbv"		"echo T Molotov |03-08| Sandbags, from Vents ----------|THROW or R-CLICK|"			//03
alias  "cmsbv2"			"setpos_exact 605.031250 -75.032669 1687.284058;setang 24.720913 -179.488358 0.000000"
alias  "cmsbv"			"setpos_exact 605.031250 -75.032669 1687.284058;setang -22.650923 -170.092514 0.000000"
alias  "echo_cmsv"		"echo T Molotov |04-08| Spools, from Vents ------------|THROW|--"					//04
alias  "cmsv2"			"setpos_exact 605.005188 -149.968750 1688.985840;setang 20.493984 -131.724609 0.000000"
alias  "cmsv"			"setpos_exact 605.005188 -149.968750 1688.985840;setang -6.584105 133.537994 0.000000"
alias  "echo_cmbdt"		"echo T Molotov |05-08| B Default, from Toxic ---------|THROW|--"					//05
alias  "cmbdt2"			"setpos_exact 1121.207642 -1455.968750 1616.835938;setang 51.153126 -91.842438 0.000000"
alias  "cmbdt"			"setpos_exact 1121.207642 -1455.968750 1616.835938;setang -26.136280 174.922928 0.000000"
alias  "echo_cmhft"		"echo T Molotov |06-08| Headshot, from Toxic ----------|THROW|--"					//06
alias  "cmhft2"			"setpos_exact 907.537354 -1228.031250 1614.031250;setang 7.423015 91.300873 0.000000"
alias  "cmhft"			"setpos_exact 907.537354 -1228.031250 1614.031250;setang -23.559967 -179.691879 0.000000"
alias  "echo_cmnbt"		"echo T Molotov |07-08| New Box, from Toxic" ----------|JUMP THROW bind|			//07
alias  "cmnbt2"			"setpos_exact 827.968750 -1463.968750 1614.031250;setang 72.489754 -20.665716 0.000000"
alias  "cmnbt"			"setpos_exact 827.968750 -1463.968750 1614.031250;setang -27.913883 167.411545 0.000000"
alias  "echo_cmbsb"		"echo T Molotov |08-08| Back Site B, from Toxic -------|THROW|--"					//08
alias  "cmbsb2"			"setpos_exact 609.031250 -1463.968750 1614.031250;setang 70.476952 -133.777390 0.000000"
alias  "cmbsb"			"setpos_exact 609.031250 -1463.968750 1614.031250;setang -32.558304 140.787170 0.000000"
//1-3 CT MOLOTOV cache
alias  "echo_cmst"		"echo CT Molotov |01-03| Safe, from Truck -------------|THROW|--"					//01
alias  "cmst2"			"setpos_exact -905.156250 1031.114014 1693.758667;setang 63.654823 37.262299 0.000000"
alias  "cmst"			"setpos_exact -904.550781 1030.032471 1694.332397;setang -23.496885 43.063911 0.000000"
alias  "echo_cmbh"		"echo CT Molotov |02-03| Boost, from Highway ----------|RUN LEFT THROW|"			//02
alias  "cmbh2"			"setpos_exact -316.968750 66.690956 1662.031250;setang 89.000000 2.015967 0.000000"
alias  "cmbh"			"setpos_exact -316.968750 66.690956 1662.031250;setang 7.311436 -7.054742 0.000000"
alias  "echo_cmbs"		"echo CT Molotov|03-03| Boost, from Sandbags ----------|THROW|--"					//03
alias  "cmbs2"			"setpos_exact 11.759085 -148.968750 1613.031250;setang 30.265629 -158.698395 0.000000"
alias  "cmbs"			"setpos_exact 11.759085 -148.994904 1613.031250;setang -32.654572 38.675369 0.000000"
//1-7 T FLASH cache
alias  "echo_cfmg"		"echo T FLASH |01-07| Mid, from Garage ----------------|RUN THROW|--"				//01
alias  "cfmg2"			"setpos_exact 1737.197266 215.031250 1614.031250;setang 76.116180 -89.307495 0.000000"
alias  "cfmg"			"setpos_exact 1737.197266 215.031250 1614.031250;setang -9.058292 154.280182 0.000000"
alias  "echo_cfasam"	"echo T FLASH |02-07| A Site, from A Main -------------|THROW or R-CLICK|--"		//02
alias  "cfasam2"		"setpos_exact 766.999634 1116.953613 1702.031250;setang 65.728966 0.013548 0.000000"
alias  "cfasam"			"setpos_exact 766.999634 1117.012329 1702.031250;setang -26.021078 117.366554 0.000000"
alias  "echo_cfqs"		"echo T FLASH |03-07| Squad, from Squeaky -------------|THROW|--"					//03
alias  "cfqs2"			"setpos_exact 480.968750 2080.031250 1702.025757;setang 71.966820 -45.932198 0.000000"
alias  "cfqs"			"setpos_exact 480.968750 2080.031250 1702.025757;setang -10.906268 119.346947 0.000000"
alias  "echo_cfbmbh"	"echo T FLASH |04-07| B Main, from B Halls ------------|THROW|--"					//04
alias  "cfbmbh2"		"setpos_exact 1481.584961 -729.984558 1614.031250;setang 76.180428 -90.337761 0.000000"
alias  "cfbmbh"			"setpos_exact 1481.584961 -729.984558 1614.031250;setang -16.715294 -165.484711 0.000000"
alias  "echo_cfbsbm"	"echo T FLASH |05-07| B Site, from B Main -------------|THROW|--"					//05
alias  "cfbsbm2"		"setpos_exact 879.802185 -872.031250 1614.031250;setang 75.498291 106.608070 0.000000"
alias  "cfbsbm"			"setpos_exact 879.802185 -872.031250 1614.031250;setang -14.157107 177.892853 0.000000"
alias  "echo_cfbsot"	"echo T FLASH |06-07| B Site, from Outside Toxic ------|THROW|--"					//06
alias  "cfbsot2"		"setpos_exact 1113.968750 -1173.968750 1614.031250;setang 69.578163 -45.075157 0.000000"
alias  "cfbsot"			"setpos_exact 1113.968750 -1173.968750 1614.031250;setang -11.088833 151.700394 0.000000"
alias  "echo_cfbmc"		"echo T FLASH |07-07| Checkers, from B Main -----------|THROW|--"					//07
alias  "cfbmc2"			"setpos_exact 808.282715 -1173.968750 1614.031250;setang 68.090134 -42.012115 0.000000"
alias  "cfbmc"			"setpos_exact 808.282593 -1173.968750 1614.031250;setang -9.570838 132.692581 0.000000"
//1-7 CT FLASH cache
alias  "echo_cfamtw"	"echo CT FLASH |01-07| A Main, from Truck Wall --------|THROW|--"					//01
alias  "cfamtw2"		"setpos_exact -482.990204 1441.979736 1687.031250;setang 74.782288 90.285751 0.000000"
alias  "cfamtw"			"setpos_exact -482.990204 1441.979736 1687.031250;setang -15.857206 11.924713 0.000000"
alias  "echo_cfamq"		"echo CT FLASH |02-07| A Main, from Quad --------------|THROW|--"					//02
alias  "cfamq2"			"setpos_exact -358.534668 2147.728027 1687.031250;setang 68.652382 -92.075531 0.000000"
alias  "cfamq"			"setpos_exact -358.534668 2147.728027 1687.031250;setang -17.540194 2.039984 0.000000"
alias  "echo_cfamf"		"echo CT FLASH |03-07| A Main, from Fences ------------|THROW|--"					//03
alias  "cfamf2"			"setpos_exact 89.984558 2244.983398 1687.031250;setang 55.714573 44.931767 0.000000"
alias  "cfamf"			"setpos_exact 89.984558 2244.983398 1687.031250;setang -71.181236 -93.482628 0.000000"
alias  "echo_cfms"		"echo CT FLASH |04-07| Mid, from Sandbags -------------|CROUCH THROW|--"			//04
alias  "cfms2"			"setpos_exact 114.968750 -107.322037 1613.655884;setang 53.434616 46.930157 0.000000"
alias  "cfms"			"setpos_exact 114.968750 -107.322037 1613.655884;setang -16.913092 -84.200432 0.000000"
alias  "echo_cfbsh"		"echo CT FLASH |05-07| B Site, from Heaven ------------|THROW or R-CLICK|--"		//05
alias  "cfbsh2"			"setpos_exact -633.975891 -379.968750 1620.031250;setang 66.569130 -90.126099 0.000000"
alias  "cfbsh"			"setpos_exact -633.975891 -379.968750 1620.031250;setang -41.629662 -58.865555 0.000000"
alias  "echo_cfbmnb"	"echo CT FLASH |06-07| B Main, from New Box -----------|JUMP THROW|"				//06
alias  "cfbmnb2"		"setpos_exact 204.968750 -1114.031250 1659.031250;setang 65.396385 47.387581 0.000000"
alias  "cfbmnb"			"setpos_exact 204.968750 -1114.011475 1659.031250;setang -44.501499 112.792343 0.000000"
alias  "echo_cfbmc"		"echo CT FLASH |07-07| B Main, from Checkers ----------|THROW|--"					//07
alias  "cfbmc2"			"setpos_exact 5.553447 -418.998749 1614.031250;setang 89.000000 -91.565590 0.000000"
alias  "cfbmc"			"setpos_exact 5.553447 -418.998749 1614.031250;setang -17.391062 53.037075 0.000000"


//1-23 T SMOKE Lineup cache
alias  "CTSL1"   "echo_cszts;cszts;		bind kp_ins CTSP1 ;alias CTSLU CTSL2 ; alias CTSLD CTSL23"
alias  "CTSL2"   "echo_cshts;cshts;		bind kp_ins CTSP2 ;alias CTSLU CTSL3 ; alias CTSLD CTSL1 "
alias  "CTSL3"   "echo_cssts;cssts;		bind kp_ins CTSP3 ;alias CTSLU CTSL4 ; alias CTSLD CTSL2 "
alias  "CTSL4"   "echo_csrmg;csrmg;		bind kp_ins CTSP4 ;alias CTSLU CTSL5 ; alias CTSLD CTSL3 "
alias  "CTSL5"   "echo_cslmg;cslmg;		bind kp_ins CTSP5 ;alias CTSLU CTSL6 ; alias CTSLD CTSL4 "
alias  "CTSL6"   "echo_cstbt;cstbt;		bind kp_ins CTSP6 ;alias CTSLU CTSL7 ; alias CTSLD CTSL5 "
alias  "CTSL7"   "echo_cszl;cszl;		bind kp_ins CTSP7 ;alias CTSLU CTSL8 ; alias CTSLD CTSL6 "
alias  "CTSL8"   "echo_csowb;csowb;		bind kp_ins CTSP8 ;alias CTSLU CTSL9 ; alias CTSLD CTSL7 "
alias  "CTSL9"   "echo_cssl;cssl;		bind kp_ins CTSP9 ;alias CTSLU CTSL10; alias CTSLD CTSL8 "
alias  "CTSL10"  "echo_cssfl;cssfl;		bind kp_ins CTSP10;alias CTSLU CTSL11; alias CTSLD CTSL9 "
alias  "CTSL11"  "echo_cscl;cscl;		bind kp_ins CTSP11;alias CTSLU CTSL12; alias CTSLD CTSL10"
alias  "CTSL12"  "echo_csadl;csadl;		bind kp_ins CTSP12;alias CTSLU CTSL13; alias CTSLD CTSL11"
alias  "CTSL13"  "echo_csftl;csftl;		bind kp_ins CTSP13;alias CTSLU CTSL14; alias CTSLD CTSL12"
alias  "CTSL14"  "echo_csfl;csfl;		bind kp_ins CTSP14;alias CTSLU CTSL15; alias CTSLD CTSL13"
alias  "CTSL15"  "echo_csftam;csftam;	bind kp_ins CTSP15;alias CTSLU CTSL16; alias CTSLD CTSL14"
alias  "CTSL16"  "echo_csfts;csfts;		bind kp_ins CTSP16;alias CTSLU CTSL17; alias CTSLD CTSL15"
alias  "CTSL17"  "echo_csfs;csfs;		bind kp_ins CTSP17;alias CTSLU CTSL18; alias CTSLD CTSL16"
alias  "CTSL18"  "echo_cscbm;cscbm;		bind kp_ins CTSP18;alias CTSLU CTSL19; alias CTSLD CTSL17"
alias  "CTSL19"  "echo_cstt;cstt;		bind kp_ins CTSP19;alias CTSLU CTSL20; alias CTSLD CTSL18"
alias  "CTSL20"  "echo_csbdt;csbdt;		bind kp_ins CTSP20;alias CTSLU CTSL21; alias CTSLD CTSL19"
alias  "CTSL21"  "echo_csnbt;csnbt;		bind kp_ins CTSP21;alias CTSLU CTSL22; alias CTSLD CTSL20"
alias  "CTSL22"  "echo_csht;cshst;		bind kp_ins CTSP22;alias CTSLU CTSL23; alias CTSLD CTSL21"
alias  "CTSL23"  "echo_cshowt;cshsowt;	bind kp_ins CTSP23;alias CTSLU CTSL1 ; alias CTSLD CTSL22"
//1-23 T SMOKE Position cache
alias  "CTSP1"   "cszts2;	bind kp_ins CTSL1"
alias  "CTSP2"   "cshts2;	bind kp_ins CTSL2"
alias  "CTSP3"   "cssts2;	bind kp_ins CTSL3"
alias  "CTSP4"   "csrmg2;	bind kp_ins CTSL4"
alias  "CTSP5"   "cslmg2;	bind kp_ins CTSL5"
alias  "CTSP6"   "cstbt2;	bind kp_ins CTSL6"
alias  "CTSP7"   "cszl2;	bind kp_ins CTSL7"
alias  "CTSP8"   "csowb2;	bind kp_ins CTSL8"
alias  "CTSP9"   "cssl2;	bind kp_ins CTSL9"
alias  "CTSP10"  "cssfl2;	bind kp_ins CTSL10"
alias  "CTSP11"  "cscl2;	bind kp_ins CTSL11"
alias  "CTSP12"  "csadl2;	bind kp_ins CTSL12"
alias  "CTSP13"  "csftl2;	bind kp_ins CTSL13"
alias  "CTSP14"  "csfl2;	bind kp_ins CTSL14"
alias  "CTSP15"  "csftam2;	bind kp_ins CTSL15"
alias  "CTSP16"  "csfts2;	bind kp_ins CTSL16"
alias  "CTSP17"  "csfs2;	bind kp_ins CTSL17"
alias  "CTSP18"  "cscbm2;	bind kp_ins CTSL18"
alias  "CTSP19"  "cstt2;	bind kp_ins CTSL19"
alias  "CTSP20"  "csbdt2;	bind kp_ins CTSL20"
alias  "CTSP21"  "csnbt2;	bind kp_ins CTSL21"
alias  "CTSP22"  "cshst2;	bind kp_ins CTSL22"
alias  "CTSP23"  "cshsowt2;	bind kp_ins CTSL23"
//1-8 CT SMOKE Lineup cache
alias  "CCTSL1"  "echo_csowz;csowz;	bind kp_ins CCTSP1;alias CCTSLU CCTSL2; alias CCTSLD CCTSL8"
alias  "CCTSL2"  "echo_csows;csows;	bind kp_ins CCTSP2;alias CCTSLU CCTSL3; alias CCTSLD CCTSL1"
alias  "CCTSL3"  "echo_csamt;csamt;	bind kp_ins CCTSP3;alias CCTSLU CCTSL4; alias CCTSLD CCTSL2"
alias  "CCTSL4"  "echo_csvtw;csvtw;	bind kp_ins CCTSP4;alias CCTSLU CCTSL5; alias CCTSLD CCTSL3"
alias  "CCTSL5"  "echo_csamq;csamq;	bind kp_ins CCTSP5;alias CCTSLU CCTSL6; alias CCTSLD CCTSL4"
alias  "CCTSL6"  "echo_csamf;csamf;	bind kp_ins CCTSP6;alias CCTSLU CCTSL7; alias CCTSLD CCTSL5"
alias  "CCTSL7"  "echo_csbmh;csbmh;	bind kp_ins CCTSP7;alias CCTSLU CCTSL8; alias CCTSLD CCTSL6"
alias  "CCTSL8"  "echo_csowv;csowv;	bind kp_ins CCTSP8;alias CCTSLU CCTSL1; alias CCTSLD CCTSL7"
//1-8 CT SMOKE Position cache
alias  "CCTSP1"  "csowz2;	bind kp_ins CCTSL1"
alias  "CCTSP2"  "csows2;	bind kp_ins CCTSL2"
alias  "CCTSP3"  "csamt2;	bind kp_ins CCTSL3"
alias  "CCTSP4"  "csvtw2;	bind kp_ins CCTSL4"
alias  "CCTSP5"  "csamq2;	bind kp_ins CCTSL5"
alias  "CCTSP6"  "csamf2;	bind kp_ins CCTSL6"
alias  "CCTSP7"  "csbmh2;	bind kp_ins CCTSL7"
alias  "CCTSP8"  "csowv2;	bind kp_ins CCTSL8"
//t smoke
alias  CTSLU CTSL1
alias  CTSLD CTSL1
//ct smoke
alias  CCTSLU CCTSL1
alias  CCTSLD CCTSL1


//1-8 T MOLOTOV Lineup cache
alias  "CTML1"  "echo_cmsl;cmsl;	Bind kp_ins CTMP1; alias CTMLU CTML2; alias CTMLD CTML8"
alias  "CTML2"  "echo_cmvl;cmvl;	Bind kp_ins CTMP2; alias CTMLU CTML3; alias CTMLD CTML1"
alias  "CTML3"  "echo_cmsbv;cmsbv;	Bind kp_ins CTMP3; alias CTMLU CTML4; alias CTMLD CTML2"
alias  "CTML4"  "echo_cmsv;cmsv;	Bind kp_ins CTMP4; alias CTMLU CTML5; alias CTMLD CTML3"
alias  "CTML5"  "echo_cmbdt;cmbdt;	Bind kp_ins CTMP5; alias CTMLU CTML6; alias CTMLD CTML4"
alias  "CTML6"  "echo_cmhft;cmhft;	Bind kp_ins CTMP6; alias CTMLU CTML7; alias CTMLD CTML5"
alias  "CTML7"  "echo_cmnbt;cmnbt;	Bind kp_ins CTMP7; alias CTMLU CTML8; alias CTMLD CTML6"
alias  "CTML8"  "echo_cmbsb;cmbsb;	Bind kp_ins CTMP8; alias CTMLU CTML1; alias CTMLD CTML7"
//1-8 T MOLOTOV Position cache
alias  "CTMP1"  "cmsl2;		Bind kp_ins CTML1"
alias  "CTMP2"  "cmvl2;		Bind kp_ins CTML2"
alias  "CTMP3"  "cmsbv2;	Bind kp_ins CTML3"
alias  "CTMP4"  "cmsv2;		Bind kp_ins CTML4"
alias  "CTMP5"  "cmbdt2;	Bind kp_ins CTML5"
alias  "CTMP6"  "cmhft2;	Bind kp_ins CTML6"
alias  "CTMP7"  "cmnbt2;	Bind kp_ins CTML7"
alias  "CTMP8"  "cmbsb2;	Bind kp_ins CTML8"
//1-3 CT MOLOTOV Lineup cache
alias  "CCTML1"  "echo_cmst;cmst;	Bind kp_ins CCTMP1; alias CCTMLU CCTML2; alias CCTMLD CCTML3"
alias  "CCTML2"  "echo_cmbh;cmbh;	Bind kp_ins CCTMP2; alias CCTMLU CCTML3; alias CCTMLD CCTML1"
alias  "CCTML3"  "echo_cmbs;cmbs;	Bind kp_ins CCTMP3; alias CCTMLU CCTML1; alias CCTMLD CCTML2"
//1-3 CT MOLOTOV Position cache
alias  "CCTMP1"  "cmst2;	Bind kp_ins CCTML1"
alias  "CCTMP2"  "cmbh2;	Bind kp_ins CCTML2"
alias  "CCTMP3"  "cmbs2;	Bind kp_ins CCTML3"
//t molotov
alias  CTMLU CTML1
alias  CTMLD CTML1
//ct molotov
alias  CCTMLU CCTML1
alias  CCTMLD CCTML1


//1-7 T FLASH Lineup cache
alias  "CTFL1"  "echo_cfmg;cfmg;		bind kp_ins CTFP1; alias CTFLU CTFL2;alias CTFLD CTFL8"
alias  "CTFL2"  "echo_cfasam;cfasam;	bind kp_ins CTFP2; alias CTFLU CTFL3;alias CTFLD CTFL1"
alias  "CTFL3"  "echo_cfqs;cfqs;		bind kp_ins CTFP3; alias CTFLU CTFL4;alias CTFLD CTFL2"
alias  "CTFL4"  "echo_cfbmbh;cfbmbh;	bind kp_ins CTFP4; alias CTFLU CTFL5;alias CTFLD CTFL3"
alias  "CTFL5"  "echo_cfbsbm;cfbsbm;	bind kp_ins CTFP5; alias CTFLU CTFL6;alias CTFLD CTFL4"
alias  "CTFL6"  "echo_cfbsot;cfbsot;	bind kp_ins CTFP6; alias CTFLU CTFL7;alias CTFLD CTFL5"
alias  "CTFL7"  "echo_cfbmc;cfbmc;		bind kp_ins CTFP7; alias CTFLU CTFL1;alias CTFLD CTFL6"
//1-7 T FLASH Position cache
alias  "CTFP1"  "cfmg2;		bind kp_ins CTFL1"
alias  "CTFP2"  "cfasam2;	bind kp_ins CTFL2"
alias  "CTFP3"  "cfqs2;		bind kp_ins CTFL3"
alias  "CTFP4"  "cfbmbh2;	bind kp_ins CTFL4"
alias  "CTFP5"  "cfbsbm2;	bind kp_ins CTFL5"
alias  "CTFP6"  "cfbsot2;	bind kp_ins CTFL6"
alias  "CTFP7"  "cfbmc2;	bind kp_ins CTFL7"
//1-7 CT FLASH Lineup cache
alias  "CCTFL1"  "echo_cfamtw;cfamtw;	bind kp_ins CCTFP1; alias CCTFLU CCTFL2; alias CCTFLD CCTFL7;
alias  "CCTFL2"  "echo_cfamq;cfamq;		bind kp_ins CCTFP2; alias CCTFLU CCTFL3; alias CCTFLD CCTFL1;
alias  "CCTFL3"  "echo_cfamf;cfamf;		bind kp_ins CCTFP3; alias CCTFLU CCTFL4; alias CCTFLD CCTFL2;
alias  "CCTFL4"  "echo_cfms;cfms;		bind kp_ins CCTFP4; alias CCTFLU CCTFL5; alias CCTFLD CCTFL3;
alias  "CCTFL5"  "echo_cfbsh;cfbsh;		bind kp_ins CCTFP5; alias CCTFLU CCTFL6; alias CCTFLD CCTFL4;
alias  "CCTFL6"  "echo_cfbmnb;cfbmnb;	bind kp_ins CCTFP6; alias CCTFLU CCTFL7; alias CCTFLD CCTFL5;
alias  "CCTFL7"  "echo_cfbmc;cfbmc;		bind kp_ins CCTFP7; alias CCTFLU CCTFL1; alias CCTFLD CCTFL6;
//1-7 CT FLASH Position cache
alias  "CCTFP1"  "cfamtw2;	bind kp_ins CCTFL1"
alias  "CCTFP2"  "cfamq2;	bind kp_ins CCTFL2"
alias  "CCTFP3"  "cfamf2;	bind kp_ins CCTFL3"
alias  "CCTFP4"  "cfms2;	bind kp_ins CCTFL4"
alias  "CCTFP5"  "cfbsh2;	bind kp_ins CCTFL5"
alias  "CCTFP6"  "cfbmnb2;	bind kp_ins CCTFL6"
alias  "CCTFP7"  "cfbmc2;	bind kp_ins CCTFL7"
//t flash
alias  CTFLU CTFL1
alias  CTFLD CTFL1
//ct flash
alias  CCTFLU CCTFL1
alias  CCTFLD CCTFL1



//1-23 T SMOKE train
alias  "echo_tsgrsts"	"echo T Smoke |01-23| green/Red Sandwitch, from T Spawn -|THROW|--"					//01
alias  "tsgrsts2"		"setpos_exact -838.170288 1268.031250 -222.968750;setang 75.982491 -90.412193 0.000000"
alias  "tsgrsts"		"setpos_exact -838.162292 1268.024414 -222.968750;setang -37.604507 -42.064575 0.000000"
alias  "echo_tscbtts"	"echo T Smoke |02-23| Center Bomb Train, from T Spaw-----|THROW|--"					//02
alias  "tscbtts2"		"setpos_exact -660.665283 1157.718262 -216.968750;setang 89.000000 -91.384140 0.000000"
alias  "tscbtts"		"setpos_exact -660.665283 1157.718262 -216.968750;setang -43.198013 -44.553295 0.000000"
alias  "echo_tsrzts"	"echo T Smoke |03-23| Right Z, from T Spawn -------------|THROW|--"					//03
alias  "tsrzts2"		"setpos_exact -627.772705 1261.741577 -216.368256;setang 89.000000 -95.094162 0.000000"
alias  "tsrzts"			"setpos_exact -627.772705 1261.741577 -216.368256;setang -44.319992 -53.548634 0.000000"
alias  "echo_tsots"		"echo T Smoke |04-23| Olaf, from T Spawn ----------------|THROW|--"					//04
alias  "tsots2"			"setpos_exact -555.031250 1262.031250 -212.594788;setang 29.283419 -57.718494 0.000000"
alias  "tsots"			"setpos_exact -555.031250 1262.031250 -212.594803;setang -68.096550 -50.974125 0.000000"
alias  "echo_tsrbtts"	"echo T Smoke |05-23| Right Bomb Train, from T Spawn ----|THROW|--"					//05
alias  "tsrbtts2"		"setpos_exact -526.628235 1325.406860 -86.902039;setang 89.000000 -93.529968 0.000000"
alias  "tsrbtts"		"setpos_exact -526.628235 1325.406860 -86.902039;setang -26.417480 -57.328667 0.000000"
alias  "echo_tszts"		"echo T Smoke |06-23| Z, from T Spawn -------------------|THROW|--"					//06
alias  "tszts2"			"setpos_exact -448.614746 1236.031250 -86.902039;setang -4.153811 -86.419441 0.000000"
alias  "tszts"			"setpos_exact -448.614746 1236.031250 -86.902039;setang -29.766037 -58.441879 0.000000
alias  "echo_tsfbtts"	"echo T Smoke |07-23| Front Bomb Train, from T Spawn ----|THROW|--"					//07
alias  "tsfbtts2"		"setpos_exact -453.358459 1286.284668 -86.553314;setang 89.000000 -91.585258 0.000000" 
alias  "tsfbtts"		"setpos_exact -453.358459 1286.284668 -86.553314;setang -25.130558 -58.731426 0.000000"
alias  "echo_tsebts"	"echo T Smoke |08-23| E BOX, from T Spawn ---------------|THROW|--"					//08
alias  "tsebts2"		"setpos_exact -481.869690 1724.990112 -209.968750;setang 37.242413 33.363880 0.000000"
alias  "tsebts"			"setpos_exact -481.865631 1725.011597 -209.968750;setang -45.937080 -78.790627 0.000000"
alias  "echo_tsbrsts"	"echo T Smoke |09-23| Blue/Red Sandwitch, from T Spawn --|THROW|--"					//09
alias  "tsbrsts2"		"setpos_exact -645.479370 1697.721924 -209.968750;setang 29.677944 161.094437 0.000000"
alias  "tsbrsts"		"setpos_exact -645.479370 1697.721924 -209.968750;setang -41.564690 -65.086685 0.000000"
alias  "echo_tsbll"		"echo T Smoke |10-23| Back Lane, from Long --------------|RUN THROW|--"				//10
alias  "tsbll2"			"setpos_exact 1535.968750 1775.968750 -223.968750;setang 64.864609 44.835953 0.000000"
alias  "tsbll"			"setpos_exact 1535.968750 1775.968750 -223.968750;setang -9.818258 -112.486588 0.000000"
alias  "echo_tsil"		"echo T Smoke |11-23| Ivy, from Long --------------------|THROW|--"					//11
alias  "tsil2"			"setpos_exact 1388.426270 1446.000488 -223.968750;setang 53.594368 -90.402718 0.000000"
alias  "tsil"			"setpos_exact 1388.426270 1446.000488 -223.968750;setang -6.188282 -95.524574 0.000000"
alias  "echo_tshtc"		"echo T Smoke |12-23| Hell, from Tcon -------------------|THROW|--"					//12
alias  "tshtc2"			"setpos_exact -803.570190 388.278839 -215.968750;setang 68.725624 -137.866409 0.000000"
alias  "tshtc"			"setpos_exact -803.572388 388.278839 -215.968750;setang -21.022144 13.708805 0.000000"
alias  "echo_tscowfb"	"echo T Smoke |13-23| Camera One Way, from Bomb Site ----|CROUCH THROW|--"			//13
alias  "tscowfb2"		"setpos_exact 317.438751 147.033768 -215.968750;setang 9.597065 89.890289 0.000000"
alias  "tscowfb"		"setpos_exact 317.438751 147.033768 -215.968750;setang -22.229637 -2.358528 0.000000"
alias  "echo_tsrzupd"	"echo T Smoke |14-23| Right Z, from Upper Popdog --------|JUMP THROW bind|--"		//14
alias  "tsrzupd2"		"setpos_exact -596.275269 -410.294495 16.031250;setang 89.000000 -1.034201 0.000000"
alias  "tsrzupd"		"setpos_exact -596.275269 -410.294495 16.031250;setang -46.544224 11.755314 0.000000"
alias  "echo_tscbtbs"	"echo T Smoke |15-23| Center Bomb Train, B Stairs -------|JUMP THROW bind|--"		//15
alias  "tscbtbs2"		"setpos_exact -598.005676 -583.968750 16.031250;setang 27.310663 -89.253914 0.000000"
alias  "tscbtbs"		"setpos_exact -598.005676 -583.968750 16.031250;setang -41.787201 22.726959 0.000000"
alias  "echo_tsitpd"	"echo T Smoke |16-23| Ivy, from Top Popdog --------------|THROW|--"					//16
alias  "tsitpd2"		"setpos_exact -655.999207 -449.668640 16.031250;setang 76.388527 -179.932419 0.000000"
alias  "tsitpd"			"setpos_exact -655.999207 -449.668640 16.031250;setang -38.577927 27.880314 0.000000"
alias  "echo_tsbctpd"	"echo T Smoke |17-23| B con, from Top Popdog ------------|THROW|--"					//17
alias  "tsbctpd2"		"setpos_exact -653.999329 -479.968719 16.031250;setang 73.779793 -179.850250 0.000000"
alias  "tsbctpd"		"setpos_exact -653.999329 -479.968719 16.031250;setang -41.597443 -8.420190 0.000000"
alias  "echo_tsigtbs"	"echo T Smoke |18-23| Ivy/Green Train, from B Stairs-----|THROW|--"					//18
alias  "tsigtbs2"		"setpos_exact -640.027832 -583.969666 16.031250;setang 89.000000 -0.141736 0.000000"
alias  "tsigtbs"		"setpos_exact -640.027832 -583.969666 16.031250;setang -44.699406 32.218452 0.000000"
alias  "echo_tshbs"		"echo T Smoke |19-23| Hell, from B Stairs ---------------|THROW|--"					//19
alias  "tshbs2"			"setpos_exact -613.161682 -583.968750 16.031250;setang 75.875328 -87.597992 0.000000"
alias  "tshbs"			"setpos_exact -613.161682 -583.968750 16.031250;setang -44.022999 53.455647 0.000000"
alias  "echo_tsbcbh"	"echo T Smoke |20-23| B Con, from B Halls ---------------|RUN THROW|--"				//20
alias  "tsbcbh2"		"setpos_exact -1159.999634 -1048.001709 -95.968750;setang 89.000000 3.234965 0.000000"
alias  "tsbcbh"			"setpos_exact -1159.999634 -1048.001709 -95.968750;setang -11.023086 5.091055 0.000000"
alias  "echo_tsbtbh"	"echo T Smoke |21-23| Blue Train, from B Halls ----------|THROW|--"					//21
alias  "tsbtbh2"		"setpos_exact -1159.978027 -1088.112549 -95.968750;setang 89.000000 -1.508712 0.000000"
alias  "tsbtbh"			"setpos_exact -1159.978027 -1088.112549 -95.968750;setang -6.832071 13.307947 0.000000"
alias  "echo_tslbbh"	"echo T Smoke |22-23| Left Bomb, from B Halls -----------|RUN THROW|--"				//22
alias  "tslbbh2"		"setpos_exact -1155.979004 -1301.504395 -95.968750;setang 66.166451 -138.826889 0.000000"
alias  "tslbbh"			"setpos_exact -1155.979004 -1301.504395 -95.968750;setang -15.857571 38.882820 0.000000"
alias  "echo_tscub"		"echo T Smoke |23-23| Catwalk, from Upper B -------------|THROW|--"					//23
alias  "tscub2"			"setpos_exact -1055.968750 -1607.969116 -151.968750;setang 65.787048 123.747856 0.000000"
alias  "tscub"			"setpos_exact -1055.968750 -1607.969116 -151.968750;setang -9.076089 -21.028521 0.000000"
//1-9 CT SMOKE train
alias  "echo_tstcob"	"echo CT Smoke |01-09| Tcon, from Old Bomb --------------|THROW|--"					//01
alias  "tstcob2"		"setpos_exact 1021.096924 -254.973801 -215.968750;setang 67.809944 -132.431763 0.000000"
alias  "tstcob"			"setpos_exact 1021.096924 -254.988556 -215.968750;setang -38.494926 154.562332 0.000000"
alias  "echo_tstcz"		"echo CT Smoke |02-09| Tcon, from Z ---------------------|JUMP THROW|--"			//02
alias  "tstcz2"			"setpos_exact 1077.998169 -753.957458 -223.968750;setang 70.483932 -37.591202 0.000000"
alias  "tstcz"			"setpos_exact 1077.999756 -753.979309 -223.968750;setang -45.804070 143.151688 0.000000"
alias  "echo_tsowsz"	"echo CT Smoke |03-09| One Way Sandwitch, from Z --------|JUMP THROW bind|--"		//03
alias  "tsowsz2"		"setpos_exact 517.334839 -399.763824 -215.968750;setang 89.000000 87.581276 0.000000"
alias  "tsowsz"			"setpos_exact 517.334839 -399.763824 -215.968750;setang 0.403118 112.328926 0.000000"
alias  "echo_tsowebzb"	"echo CT Smoke |04-09| One Way EBox, from Z/Bomb --------|THROW|--"					//04
alias  "tsowebzb2"		"setpos_exact 492.896942 -136.819550 -217.573593;setang 31.281321 67.170158 0.000000"
alias  "tsowebzb"		"setpos_exact 492.896942 -136.819550 -217.573593;setang -34.057343 -159.218842 0.000000"
alias  "echo_tsowebc"	"echo CT Smoke |05-09| One Way EBox, from Camera --------|Crouch THROW|--"			//05
alias  "tsowebc2"		"setpos_exact 1007.981506 149.050690 -215.968750;setang 75.910057 -1.310453 0.000000"
alias  "tsowebc"		"setpos_exact 1007.981506 149.050690 -215.968750;setang -9.832564 -176.703659 0.000000"
alias  "echo_tsowstb"	"echo CT Smoke |06-09| One Way Sandwitch, from Top Bomb -|THROW|--"					//06
alias  "tsowstb2"		"setpos_exact 515.479492 -26.537792 -132.594360;setang 11.835532 -159.706146 0.000000"
alias  "tsowstb"		"setpos_exact 515.479492 -26.537792 -132.594360;setang -17.395052 121.146042 0.000000"
alias  "echo_tsowobeb"	"echo CT Smoke |07-09| One Way Old Bomb, from Ebox ------|JUMP THROW bind|--"		//07
alias  "tsowobeb2"		"setpos_exact -370.028717 -86.332207 -215.968750;setang 89.000000 0.595913 0.000000
alias  "tsowobeb"		"setpos_exact -370.028717 -86.332207 -215.968750;setang -0.908284 -0.306591 0.000000"
alias  "echo_tsowbrbb"	"echo CT Smoke |08-09| One Way B Ramp, from Back Blue ---|CROUCH THROW|--"			//08
alias  "tsowbrbb2"		"setpos_exact 223.031250 -960.010315 -351.968750;setang 60.931026 153.883743 0.000000"
alias  "tsowbrbb"		"setpos_exact 223.031250 -960.010315 -351.968750;setang -14.233523 169.357864 0.000000"
alias  "echo_tsowbsub"	"echo CT Smoke |09-09| One Way B Stairs, from Upper B ---|Run THROW|--"				//09
alias  "tsowbsub2"		"setpos_exact -1055.990845 -1775.968750 -151.968750;setang 70.688332 -134.864059 0.000000"
alias  "tsowbsub"		"setpos_exact -1055.990845 -1775.968750 -151.968750;setang -12.861467 85.292297 0.000000"
//1-6 T MOLOTOV train
alias  "echo_tmstc"		"echo T Molotov|01-06| Snadwitch, from Tcon -------------|RUN THROW|--"				//01
alias  "tmstc2"			"setpos_exact -803.570068 388.278107 -215.968750;setang 63.928955 -124.536339 0.000000"
alias  "tmstc"			"setpos_exact -803.570068 388.278107 -215.968750;setang -11.463088 26.208202 0.000000"
alias  "echo_tmebtc"	"echo T Molotov|02-06| E box, from Tcon -----------------|RUN JUMP or THROW|--"		//02
alias  "tmebtc2"		"setpos_exact -750.761169 304.031250 -215.968750;setang 4.310772 -91.050163 0.000000"
alias  "tmebtc"			"setpos_exact -750.761169 304.031250 -215.968750;setang -3.053643 51.947502 0.000000"
alias  "echo_tmci"		"echo T Molotov|03-06| Cubby, from Ivy ------------------|RUN THROW|--				//03
alias  "tmci2"			"setpos_exact 1460.409912 1588.383179 -227.968750;setang 89.000000 -88.238564 0.000000"
alias  "tmci"			"setpos_exact 1460.409912 1588.383179 -227.968750;setang -13.480363 -113.574211 0.000000"
alias  "echo_tmhh"		"echo T Molotov|04-06| Heaven, from Hell ----------------|THROW|--"					//04
alias  "tmhh2"			"setpos_exact 816.012390 735.997070 -154.968750;setang 76.137314 98.975395 0.000000"
alias  "tmhh"			"setpos_exact 816.012390 735.997070 -154.968750;setang -23.796263 -92.986671 0.000000"
alias  "echo_tmbbbh"	"echo T Molotov |05-06| Back Blue, B Halls --------------|THROW|--"					//05
alias  "tmbbbh2"		"setpos_exact -1061.190796 -1012.801086 -55.968750;setang -1.241734 -4.320885 0.000000"
alias  "tmbbbh"			"setpos_exact -1061.190796 -1012.801086 -55.968750;setang 89.000000 -0.991119 0.000000"
alias  "echo_tmlub"		"echo T Molotov |06-06| Ladder, from Upper B ------------|WALK BACK THROW|--"		//06
alias  "tmlub2"			"setpos_exact -986.747620 -1637.499023 -151.968750;setang 89.000000 -89.117172 0.000000"
alias  "tmlub"			"setpos_exact -986.747620 -1637.499023 -151.968750;setang -10.283748 -19.689480 0.000000"
//1-4 CT MOLOTOV train
alias  "echo_tmoz"		"echo CT Molotov |01-04| Olaf, from Z -------------------|JUMP THROW bind|--"		//01
alias  "tmoz2"			"setpos_exact 542.760315 -413.694824 -215.968750;setang 89.000000 87.901375 0.000000"
alias  "tmoz"			"setpos_exact 542.760315 -413.694824 -215.968750;setang 2.917692 119.010490 0.000000"
alias  "echo_tmbseb"	"echo CT Molotov |02-04| B Stairs, from EBox ------------|THROW|--"					//02
alias  "tmbseb2"		"setpos_exact -133.275757 -16.726789 -191.875000;setang 54.747261 179.144485 0.000000"
alias  "tmbseb"			"setpos_exact -133.275757 -16.726789 -191.875000;setang -40.033524 -136.244614 0.000000"
alias  "echo_tmupeb"	"echo CT Molotov |03-04| Upper Popdog, from EBox --------|THROW|--"					//03
alias  "tmupeb2"		"setpos_exact -133.278397 -15.596681 -191.875000;setang 24.025700 -178.536270 0.000000"
alias  "tmupeb"			"setpos_exact -133.278397 -15.596681 -191.875000;setang -35.991604 -135.500534 0.000000"
alias  "echo_tmbdbb"	"echo CT Molotov |01-04| B Default, from back blue ------|RUN THROW|--"				//04
alias  "tmbdbb2"		"setpos_exact 254.747406 -1022.813171 -355.968750;setang 89.000000 178.866806 0.000000"
alias  "tmbdbb"			"setpos_exact 254.747406 -1022.813171 -355.968750;setang -12.946258 -124.799515 0.000000"
//1-11 T FLASH train
alias  "echo_tfasd"		"echo T Flash |01-11| A Site, from Dumpster -------------|THROW|--"					//01
alias  "tfasd2"			"setpos_exact -453.219299 1286.272583 -86.553314;setang 89.000000 -88.741669 0.000000"
alias  "tfasd"			"setpos_exact -453.219299 1286.272583 -86.553314;setang -26.341545 -88.319252 0.000000"
alias  echo_tfztc"		"echo T Flash |02-11| Z, from Tcon ----------------------|THROW|--"					//02
alias  "tfztc2"			"setpos_exact -792.992188 304.010223 -215.968750;setang 69.384895 -138.664627 0.000000"
alias  "tfztc"			"setpos_exact -792.992188 304.010223 -215.968750;setang -44.003090 151.665894 0.000000"
alias  "echo_tfaso"		"echo T Flash |03-11| A Site, from Olaf -----------------|JUMP THROW bind|--"		//03
alias  "tfaso2"			"setpos_exact -114.733582 680.580994 -215.968750;setang 11.753665 92.654243 0.000000"
alias  "tfaso"			"setpos_exact -114.733582 680.580994 -215.968750;setang -31.251923 -47.028141 0.000000"
alias  "echo_tfli"		"echo T Flash |04-11|  Lanes, from IVY ------------------|THROW|--"					//04
alias  "tfli2"			"setpos_exact 1129.987061 1436.031250 -223.968750;setang 59.662971 -30.044643 0.000000"
alias  "tfli"			"setpos_exact 1129.987061 1436.031250 -223.968750;setang -21.675446 0.104155 0.000000"
alias  "echo_tfbgi"		"echo T Flash |05-11| Back Green, from Ivy --------------|THROW|--"					//05
alias  "tfbgi2"			"setpos_exact 1375.968750 839.450134 -223.968750;setang 89.000000 -1.691999 0.000000"
alias  "tfbgi"			"setpos_exact 1375.968750 839.450134 -223.968750;setang -0.507174 -108.506416 0.000000"
alias  "echo_tfbspd"	"echo T Flash |06-11| B Site, from Popdog ---------------|THROW|--"					//06
alias  "tfbspd2"		"setpos_exact -660.174683 -316.031250 -215.968750;setang 66.077576 135.993561 0.000000"
alias  "tfbspd"			"setpos_exact -660.174683 -316.031250 -215.968750;setang 6.730310 -48.595165 0.000000"
alias  "echo_tfpdupd"	"echo T Flash |07-11| Popdog, from Upper popdog ---------|R-CLICK|--"				//07
alias  "tfpdupd2"		"setpos_exact -568.031250 -468.571228 16.031250;setang 22.201538 -0.223420 0.000000"
alias  "tfpdupd"		"setpos_exact -568.031250 -468.571228 16.031250;setang -30.994425 143.946945 0.000000"
alias  "echo_tfbhbs"	"echo T Flash |08-11| B Halls, from B stairs ------------|THROW or R-CLICK|--"		//08
alias  "tfbhbs2"		"setpos_exact -655.968750 -508.006805 16.031250;setang 75.430893 166.079987 0.000000"
alias  "tfbhbs"			"setpos_exact -655.968750 -508.006805 16.031250;setang -6.725921 -164.378403 0.000000"
alias  echo_tfbsbr"		"echo T Flash |09-11| B Site, from B Ramp ---------------|THROW|--"					//09
alias  "tfbsbr2"		"setpos_exact -1047.997070 -875.515259 -151.968750;setang 89.000000 0.446806 0.000000"
alias  "tfbsbr"			"setpos_exact -1047.997070 -875.515259 -151.968750;setang 29.863958 0.869206 0.000000"
alias  "echo_tfbsbh"	"echo T Flash |10-11| B Site, from B Halls --------------|THROW|--"					//10
alias  "tfbsbh2"		"setpos_exact -1159.973633 -1048.017212 -95.968750;setang 75.899117 153.329697 0.000000"
alias  "tfbsbh"			"setpos_exact -1159.973633 -1048.017212 -95.968750;setang -6.732901 5.067283 0.000000"
alias  echo_tfcbh"		"echo T Flash |11-11| Catwalk, from B Halls -------------|WALK THROW|--"			//11
alias  "tfcbh2"			"setpos_exact -931.319214 -1339.370728 -151.968750;setang 88.947205 89.837029 0.000000"
alias  "tfcbh"			"setpos_exact -931.319214 -1339.370728 -151.968750;setang -45.824833 89.784225 0.000000"
//1-8 CT FLASH train
alias  echo_tfabz"		"echo CT Flash |01-08| A Bomb, from Z -------------------|RUN THROW|--"				//01
alias  "tfabz2"			"setpos_exact 400.031250 -420.031250 -211.840134;setang 68.424995 128.610489 0.000000"
alias  "tfabz"			"setpos_exact 400.031250 -420.031250 -211.840134;setang -28.859020 -89.674629 0.000000"
alias  echo_tfsbab"		"echo CT Flash |02-08| Sandwitch, Back A Bomb -----------|THROW|--"					//02
alias  "tfsbab2"		"setpos_exact 694.031250 -65.697762 -215.968750;setang 35.909637 141.612869 0.000000"
alias  "tfsbab"			"setpos_exact 694.031250 -65.697762 -215.968750;setang -22.856762 171.497772 0.000000"
alias  echo_tfibg"		"echo CT Flash |03-08| Ivy, from Back Green -------------|THROW|--"					//03
alias  "tfibg2"			"setpos_exact 986.107788 479.841705 -218.584488;setang 89.000000 179.312210 0.000000"
alias  "tfibg"			"setpos_exact 986.107788 479.841705 -218.584488;setang -30.961584 -176.332123 0.000000"
alias  echo_tfibl"		"echo CT Flash |04-08| Ivy, from Back Lane --------------|THROW|--"					//04
alias  "tfibl2"			"setpos_exact 1959.968750 254.203064 -223.968750;setang 47.129574 -0.314822 0.000000"
alias  "tfibl"			"setpos_exact 1959.968750 254.203064 -223.968750;setang -25.998411 137.493088 0.000000"
alias  "echo_tfbrtz"	"echo CT Flash |05-08| B Red Train, from Z --------------|THROW|--"					//05
alias  "tfbrtz2"		"setpos_exact 824.048584 -568.057190 -220.400253;setang 68.393097 38.655788 0.000000"
alias  "tfbrtz"			"setpos_exact 824.048584 -568.057190 -220.400253;setang -13.578902 -27.581802 0.000000"
alias  echo_tfbhtb"		"echo CT Flash |06-08| B Halls, from Top Blue -----------|THROW|--"					//06
alias  "tfbhtb2"		"setpos_exact 50.860470 -1023.914978 -165.870316;setang 89.000000 179.678375 0.000000"
alias  "tfbhtb"			"setpos_exact 50.860470 -1023.914978 -165.870316;setang -23.860077 -179.212845 0.000000"
alias  echo_tfubcw"		"echo CT Flash |07-08| Upper B, from Catwalk ------------|WALK THROW|--"			//07
alias  "tfubcw2"		"setpos_exact -799.032654 -1731.970947 -127.968750;setang 89.000000 -0.650553 0.000000"
alias  "tfubcw"			"setpos_exact -799.032654 -1731.970947 -127.968750;setang -13.036031 0.827849 0.000000"
alias  echo_tfbhubc"	"echo CT Flash |08-08| B Halls, from Upper B Cubby ------|RUN THROW|--"				//08
alias  "tfbhubc2"		"setpos_exact -1047.968750 -1497.031250 -151.968750;setang 63.497471 119.760490 0.000000"
alias  "tfbhubc"		"setpos_exact -1047.968750 -1497.031250 -151.968750;setang -28.242540 -89.891495 0.000000"


//1-23 T SMOKE Lineup train
alias  "TTSL1"   "echo_tsgrsts;tsgrsts;	bind kp_ins TTSP1;  alias TTSLU TTSL2;  alias TTSLD TTSL23"
alias  "TTSL2"   "echo_tscbtts;tscbtts;	bind kp_ins TTSP2;  alias TTSLU TTSL3;  alias TTSLD TTSL1"
alias  "TTSL3"   "echo_tsrzts;tsrzts;	bind kp_ins TTSP3;  alias TTSLU TTSL4;  alias TTSLD TTSL2"
alias  "TTSL4"   "echo_tsots;tsots;		bind kp_ins TTSP4;  alias TTSLU TTSL5;  alias TTSLD TTSL3"
alias  "TTSL5"   "echo_tsrbtts;tsrbtts;	bind kp_ins TTSP5;  alias TTSLU TTSL6;  alias TTSLD TTSL4"
alias  "TTSL6"   "echo_tszts;tszts;		bind kp_ins TTSP6;  alias TTSLU TTSL7;  alias TTSLD TTSL5"
alias  "TTSL7"   "echo_tsfbtts;tsfbtts;	bind kp_ins TTSP7;  alias TTSLU TTSL8;  alias TTSLD TTSL6"
alias  "TTSL8"   "echo_tsebts;tsebts;	bind kp_ins TTSP8;  alias TTSLU TTSL9;  alias TTSLD TTSL7"
alias  "TTSL9"   "echo_tsbrsts;tsbrsts;	bind kp_ins TTSP9;  alias TTSLU TTSL10; alias TTSLD TTSL8"
alias  "TTSL10"  "echo_tsbll;tsbll;		bind kp_ins TTSP10; alias TTSLU TTSL11; alias TTSLD TTSL9"
alias  "TTSL11"  "echo_tsil;tsil;		bind kp_ins TTSP11; alias TTSLU TTSL12; alias TTSLD TTSL10"
alias  "TTSL12"  "echo_tshtc;tshtc;		bind kp_ins TTSP12; alias TTSLU TTSL13; alias TTSLD TTSL11"
alias  "TTSL13"  "echo_tscowfb;tscowfb;	bind kp_ins TTSP13; alias TTSLU TTSL14; alias TTSLD TTSL12"
alias  "TTSL14"  "echo_tsrzupd;tsrzupd;	bind kp_ins TTSP14; alias TTSLU TTSL15; alias TTSLD TTSL13"
alias  "TTSL15"  "echo_tscbtbs;tscbtbs;	bind kp_ins TTSP15; alias TTSLU TTSL16; alias TTSLD TTSL14"
alias  "TTSL16"  "echo_tsitpd;tsitpd;	bind kp_ins TTSP16; alias TTSLU TTSL17; alias TTSLD TTSL15"
alias  "TTSL17"  "echo_tsbctpd;tsbctpd;	bind kp_ins TTSP17; alias TTSLU TTSL18; alias TTSLD TTSL16"
alias  "TTSL18"  "echo_tsigtbs;tsigtbs;	bind kp_ins TTSP18; alias TTSLU TTSL19; alias TTSLD TTSL17"
alias  "TTSL19"  "echo_tshbs;tshbs;		bind kp_ins TTSP19; alias TTSLU TTSL20; alias TTSLD TTSL18"
alias  "TTSL20"  "echo_tsbcbh;tsbcbh;	bind kp_ins TTSP20; alias TTSLU TTSL21; alias TTSLD TTSL19"
alias  "TTSL21"  "echo_tsbtbh;tsbtbh;	bind kp_ins TTSP21; alias TTSLU TTSL22; alias TTSLD TTSL20"
alias  "TTSL22"  "echo_tslbbh;tslbbh;	bind kp_ins TTSP22; alias TTSLU TTSL23; alias TTSLD TTSL21"
alias  "TTSL23"  "echo_tscub;tscub;		bind kp_ins TTSP23; alias TTSLU TTSL1 ; alias TTSLD TTSL22"
//1-23 T SMOKE Position train
alias  "TTSP1"   "tsgrsts2;	bind kp_ins TTSL1"
alias  "TTSP2"   "tscbtts2;	bind kp_ins TTSL2"
alias  "TTSP3"   "tsrzts2;	bind kp_ins TTSL3"
alias  "TTSP4"   "tsots2;	bind kp_ins TTSL4"
alias  "TTSP5"   "tsrbtts2;	bind kp_ins TTSL5"
alias  "TTSP6"   "tszts2;	bind kp_ins TTSL6"
alias  "TTSP7"   "tsfbtts2;	bind kp_ins TTSL7"
alias  "TTSP8"   "tsebts2;	bind kp_ins TTSL8"
alias  "TTSP9"   "tsbrsts2;	bind kp_ins TTSL9"
alias  "TTSP10"  "tsbll2;	bind kp_ins TTSL10"
alias  "TTSP11"  "tsil2;	bind kp_ins TTSL11"
alias  "TTSP12"  "tshtc2;	bind kp_ins TTSL12"
alias  "TTSP13"  "tscowfb2;	bind kp_ins TTSL13"
alias  "TTSP14"  "tsrzupd2;	bind kp_ins TTSL14"
alias  "TTSP15"  "tscbtbs2;	bind kp_ins TTSL15"
alias  "TTSP16"  "tsitpd2;	bind kp_ins TTSL16"
alias  "TTSP17"  "tsbctpd2;	bind kp_ins TTSL17"
alias  "TTSP18"  "tsigtbs2;	bind kp_ins TTSL18"
alias  "TTSP19"  "tshbs2;	bind kp_ins TTSL19"
alias  "TTSP20"  "tsbcbh2;	bind kp_ins TTSL20"
alias  "TTSP21"  "tsbtbh2;	bind kp_ins TTSL21"
alias  "TTSP22"  "tslbbh2;	bind kp_ins TTSL22"
alias  "TTSP23"  "tscub2;	bind kp_ins TTSL23"
//1-9 CT SMOKE Lineup train
alias  "TCTSL1"  "echo_tstcob;tstcob;		bind kp_ins TCTSP1; alias TCTSLU TCTSL2; alias TCTSLD TCTSL9"
alias  "TCTSL2"  "echo_tstcz;tstcz;			bind kp_ins TCTSP2; alias TCTSLU TCTSL3; alias TCTSLD TCTSL1"
alias  "TCTSL3"  "echo_tsowsz;tsowsz;		bind kp_ins TCTSP3; alias TCTSLU TCTSL4; alias TCTSLD TCTSL2"
alias  "TCTSL4"  "echo_tsowebzb;tsowebzb;	bind kp_ins TCTSP4; alias TCTSLU TCTSL5; alias TCTSLD TCTSL3"
alias  "TCTSL5"  "echo_tsowebc;tsowebc;		bind kp_ins TCTSP5; alias TCTSLU TCTSL6; alias TCTSLD TCTSL4"
alias  "TCTSL6"  "echo_tsowstb;tsowstb;		bind kp_ins TCTSP6; alias TCTSLU TCTSL7; alias TCTSLD TCTSL5"
alias  "TCTSL7"  "echo_tsowobeb;tsowobeb;	bind kp_ins TCTSP7; alias TCTSLU TCTSL8; alias TCTSLD TCTSL6"
alias  "TCTSL8"  "echo_tsowbrbb;tsowbrbb;	bind kp_ins TCTSP8; alias TCTSLU TCTSL9; alias TCTSLD TCTSL7"
alias  "TCTSL9"  "echo_tsowbsub;tsowbsub;	bind kp_ins TCTSP9; alias TCTSLU TCTSL1; alias TCTSLD TCTSL8"
//1-9 CT SMOKE Position train
alias  "TCTSP1"  "tstcob2;		bind kp_ins TCTSL1"
alias  "TCTSP2"  "tstcz2;		bind kp_ins TCTSL2"
alias  "TCTSP3"  "tsowsz2;		bind kp_ins TCTSL3"
alias  "TCTSP4"  "tsowebzb2;	bind kp_ins TCTSL4"
alias  "TCTSP5"  "tsowebc2;		bind kp_ins TCTSL5"
alias  "TCTSP6"  "tsowstb2;		bind kp_ins TCTSL6"
alias  "TCTSP7"  "tsowobeb2;	bind kp_ins TCTSL7"
alias  "TCTSP8"  "tsowbrbb2;	bind kp_ins TCTSL8"
alias  "TCTSP9"  "tsowbsub2;	bind kp_ins TCTSL9"
//T-Smoke 
alias TTSLU TTSL1
alias TTSLD TTSL1
//CT-Smoke
alias TCTSLU TCTSL1
alias TCTSLD TCTSL1


//1-6 T MOLOTOV Lineup train
alias  "TTML1"  "echo_tmstc;tmstc;		bind kp_ins TTMP1; alias TTMLU TTML2; alias TTMLD TTML6"
alias  "TTML2"  "echo_tmebtc;tmebtc;	bind kp_ins TTMP2; alias TTMLU TTML3; alias TTMLD TTML1"
alias  "TTML3"  "echo_tmci;tmci;		bind kp_ins TTMP3; alias TTMLU TTML4; alias TTMLD TTML2"
alias  "TTML4"  "echo_tmhh;tmhh;		bind kp_ins TTMP4; alias TTMLU TTML5; alias TTMLD TTML3"
alias  "TTML5"  "echo_tmbbbh;tmbbbh;	bind kp_ins TTMP5; alias TTMLU TTML6; alias TTMLD TTML4"
alias  "TTML6"  "echo_tmlub;tmlub;		bind kp_ins TTMP6; alias TTMLU TTML1; alias TTMLD TTML5"
//1-6 T MOLOTOV Position train
alias  "TTMP1"  "tmstc2;	bind kp_ins TTML1"
alias  "TTMP2"  "tmebtc2;	bind kp_ins TTML2"
alias  "TTMP3"  "tmci2;		bind kp_ins TTML3"
alias  "TTMP4"  "tmhh2;		bind kp_ins TTML4"
alias  "TTMP5"  "tmbbbh2;	bind kp_ins TTML5"
alias  "TTMP6"  "tmlub2;	bind kp_ins TTML6"
//1-4 CT MOLOTOV Lineup train
alias  "TCTML1"  "echo_tmoz;tmoz;		bind kp_ins TCTMP1; alias TCTMLU TCTML2; alias TCTMLD TCTML4"
alias  "TCTML2"  "echo_tmbseb;tmbseb;	bind kp_ins TCTMP2; alias TCTMLU TCTML3; alias TCTMLD TCTML1"
alias  "TCTML3"  "echo_tmupeb;tmupeb;	bind kp_ins TCTMP3; alias TCTMLU TCTML4; alias TCTMLD TCTML2"
alias  "TCTML4"  "echo_tmbdbb;tmbdbb;	bind kp_ins TCTMP4; alias TCTMLU TCTML1; alias TCTMLD TCTML3"
//1-4 CT MOLOTOV Position train
alias  "TCTMP1"  "tmoz2;	bind kp_ins TCTML1"
alias  "TCTMP2"  "tmbseb2;	bind kp_ins TCTML2"
alias  "TCTMP3"  "tmupeb2;	bind kp_ins TCTML3"
alias  "TCTMP4"  "tmbdbb2;	bind kp_ins TCTML4"
//T Molotov
alias TTMLU TTML1
alias TTMLD TTML1
//CT-Molotov
alias TCTMLU TCTML1
alias TCTMLD TCTML1


//1-11 T FLASH Lineup train
alias  "TTFL1"   "echo_tfasd;tfasd;		bind kp_ins TTFP1;  alias TTFLU TTFL2;  alias TTFLD TTFL11"
alias  "TTFL2"   "echo_tfztc;tfztc;		bind kp_ins TTFP2;  alias TTFLU TTFL3;  alias TTFLD TTFL1"
alias  "TTFL3"   "echo_tfaso;tfaso;		bind kp_ins TTFP3;  alias TTFLU TTFL4;  alias TTFLD TTFL2"
alias  "TTFL4"   "echo_tfli;tfli;		bind kp_ins TTFP4;  alias TTFLU TTFL5;  alias TTFLD TTFL3"
alias  "TTFL5"   "echo_tfbgi;tfbgi;		bind kp_ins TTFP5;  alias TTFLU TTFL6;  alias TTFLD TTFL4"
alias  "TTFL6"   "echo_tfbspd;tfbspd;	bind kp_ins TTFP6;  alias TTFLU TTFL7;  alias TTFLD TTFL5"
alias  "TTFL7"   "echo_tfpdupd;tfpdupd;	bind kp_ins TTFP7;  alias TTFLU TTFL8;  alias TTFLD TTFL6"
alias  "TTFL8"   "echo_tfbhbs;tfbhbs;	bind kp_ins TTFP8;  alias TTFLU TTFL9;  alias TTFLD TTFL7"
alias  "TTFL9"   "echo_tfbsbr;tfbsbr;	bind kp_ins TTFP9;  alias TTFLU TTFL10; alias TTFLD TTFL8"
alias  "TTFL10"  "echo_tfbsbh;tfbsbh;	bind kp_ins TTFP10; alias TTFLU TTFL11; alias TTFLD TTFL9"
alias  "TTFL11"  "echo_tfcbh;tfcbh;		bind kp_ins TTFP11; alias TTFLU TTFL1 ; alias TTFLD TTFL10"
//1-11 T FLASH Position train
alias  "TTFP1"   "tfasd2;	bind kp_ins TTFL1"
alias  "TTFP2"   "tfztc2;	bind kp_ins TTFL2"
alias  "TTFP3"   "tfaso2;	bind kp_ins TTFL3"
alias  "TTFP4"   "tfli2;	bind kp_ins TTFL4"
alias  "TTFP5"   "tfbgi2;	bind kp_ins TTFL5"
alias  "TTFP6"   "tfbspd2;	bind kp_ins TTFL6"
alias  "TTFP7"   "tfpdupd2;	bind kp_ins TTFL7"
alias  "TTFP8"   "tfbhbs2;	bind kp_ins TTFL8"
alias  "TTFP9"   "tfbsbr2;	bind kp_ins TTFL9"
alias  "TTFP10"  "tfbsbh2;	bind kp_ins TTFL10"
alias  "TTFP11"  "tfcbh2;	bind kp_ins TTFL11"
//1-8 CT FLASH Lineup train
alias  "TCTFL1"  "echo_tfabz;tfabz;		bind kp_ins TCTFP1; alias TCTFLU TCTFL2; alias TCTFLD TCTFL8"
alias  "TCTFL2"  "echo_tfsbab;tfsbab;	bind kp_ins TCTFP2; alias TCTFLU TCTFL3; alias TCTFLD TCTFL1"
alias  "TCTFL3"  "echo_tfibg;tfibg;		bind kp_ins TCTFP3; alias TCTFLU TCTFL4; alias TCTFLD TCTFL2"
alias  "TCTFL4"  "echo_tfibl;tfibl;		bind kp_ins TCTFP4; alias TCTFLU TCTFL5; alias TCTFLD TCTFL3"
alias  "TCTFL5"  "echo_tfbrtz;tfbrtz;	bind kp_ins TCTFP5; alias TCTFLU TCTFL6; alias TCTFLD TCTFL4"
alias  "TCTFL6"  "echo_tfbhtb;tfbhtb;	bind kp_ins TCTFP6; alias TCTFLU TCTFL7; alias TCTFLD TCTFL5"
alias  "TCTFL7"  "echo_tfubcw;tfubcw;	bind kp_ins TCTFP7; alias TCTFLU TCTFL8; alias TCTFLD TCTFL6"
alias  "TCTFL8"  "echo_tfbhubc;tfbhubc;	bind kp_ins TCTFP8; alias TCTFLU TCTFL1; alias TCTFLD TCTFL7"
//1-8 CT FLASH Position train
alias  "TCTFP1"  "tfabz2;	bind kp_ins TCTFL1"
alias  "TCTFP2"  "tfsbab2;	bind kp_ins TCTFL2"
alias  "TCTFP3"  "tfibg2;	bind kp_ins TCTFL3"
alias  "TCTFP4"  "tfibl2;	bind kp_ins TCTFL4"
alias  "TCTFP5"  "tfbrtz2;	bind kp_ins TCTFL5"
alias  "TCTFP6"  "tfbhtb2;	bind kp_ins TCTFL6"
alias  "TCTFP7"  "tfubcw2;	bind kp_ins TCTFL7"
alias  "TCTFP8"  "tfbhubc2;	bind kp_ins TCTFL8"
//T-Flash
alias TTFLU TTFL1
alias TTFLD TTFL1
//CT-Flash
alias TCTFLU TCTFL1
alias TCTFLD TCTFL1



//1-27 T-Side SMOKE inferno
alias  "echo_istmts"	"echo T Smoke |01-27| Top Mid, from T Spawn --------------|STEP THROW|--"			//01
alias  "istmts2"		"setpos_exact -857.968750 449.902283 -31.665127;setang 72.761795 178.401169 0.000000"
alias  "istmts"			"setpos_exact -857.968750 449.902283 -31.665127;setang -44.401531 1.405892 0.000000"
alias  "echo_isrmm"		"echo T Smoke |02-27| Right Mid from Mexico --------------|THROW|--"				//02
alias  "isrmm2"			"setpos_exact 295.990173 644.004761 20.031250;setang 18.807228 -45.859497 0.000000"
alias  "isrmm"			"setpos_exact 295.990173 644.004761 20.031250;setang -22.455982 -11.856322 0.000000"
alias  "echo_ismm"		"echo T Smoke |03-27| Moto, from Mexico ------------------|CROUCH JUMP THROW|--"	//03
alias  "ismm2"			"setpos_exact 272.031250 644.001709 20.031250;setang 18.849934 -134.204605 0.000000"
alias  "ismm"			"setpos_exact 272.031250 644.001709 20.031250;setang -25.238041 2.547442 0.000000"
alias  "echo_islam"		"echo T Smoke |04-27| Long, from Alt Mid -----------------|THROW|--"				//04
alias  "islam2"			"setpos_exact 274.681335 -224.627777 88.031250;setang 89.000000 -0.821562 0.000000"
alias  "islam"			"setpos_exact 274.681335 -224.627777 88.031250;setang -41.052132 31.799410 0.000000"
alias  "echo_islmdam"	"echo T Smoke |05-27| Left Mid, from Deep Alt Mid --------|THROW|--"				//05
alias  "islmdam2"		"setpos_exact 493.002350 -267.992218 88.031250;setang 89.000000 89.028023 0.000000"
alias  "islmdam"		"setpos_exact 493.002350 -267.992218 88.031250;setang -41.653618 45.969559 0.000000"
alias  "echo_islham"	"echo T Smoke |06-27|Lane/Hay, Alt Mid -------------------|THROW|--"				//06
alias  "islham2"		"setpos_exact 697.511902 -242.261810 91.031250;setang 89.000000 -0.110076 0.000000"
alias  "islham"			"setpos_exact 697.511902 -242.261810 91.031250;setang -53.097946 16.442726 0.000000"
alias  "echo_isbham"	"echo T Smoke |07-27| Barrels/Hay, from Alt Mid ----------|CROUCH JUMP THROW bind|--"//07
alias  "isbham2"		"setpos_exact 604.513794 -265.187622 88.031250;setang 89.000000 -0.004432 0.000000"
alias  "isbham"			"setpos_exact 604.513794 -265.187622 88.031250;setang -23.437620 14.805969 0.000000"
alias  "echo_ismam"		"echo T Smoke |08-27| Moto, from Alt Mid -----------------|JUMP THROW bind|--"		//08
alias  "ismam2"			"setpos_exact 604.513794 -265.187622 88.031250;setang 89.000000 -0.004432 0.000000"
alias  "ismam"			"setpos_exact 604.513794 -265.187622 88.031250;setang -20.401588 31.675571 0.000000"
alias  "echo_isrmam"	"echo T Smoke |09-27| Right Mid, from Alt Mid ------------|Crouch Throw|--"			//09
alias  "isrmam2"		"setpos_exact 790.031250 -302.988647 98.984001;setang 68.276024 -138.677841 0.000000"
alias  "isrmam"			"setpos_exact 790.031250 -302.988647 98.984001;setang -58.426853 41.080406 0.000000"
alias  "echo_isbam"		"echo T Smoke |10-27| Balc, from Alt Mid -----------------|THROW|--"				//10
alias  "isbam2"			"setpos_exact 693.867432 11.968750 88.255936;setang 89.000000 89.768997 0.000000"
alias  "isbam"			"setpos_exact 693.867432 11.968750 88.255936;setang -51.134453 -12.082219 0.000000"
alias  "echo_isbpam"	"echo T Smoke |11-27| Big Pit, from Alt Mid --------------|THROW|--"				//11
alias  "isbpam2"		"setpos_exact 704.151794 11.968750 88.738014;setang 72.948753 90.370575 0.000000"
alias  "isbpam"			"setpos_exact 704.160339 11.968750 88.738411;setang -52.337799 -2.135024 0.000000"
alias  "echo_isaam"		"echo T Smoke |12-27| Arch, from Alt Mid -----------------|THROW|--"				//12
alias  "isaam2"			"setpos_exact 726.253540 185.790634 97.478981;setang 60.857567 -136.475433 0.000000"
alias  "isaam"			"setpos_exact 726.010803 186.011993 97.474739;setang -46.349754 45.800774 0.000000"
alias  "echo_ispam"		"echo T Smoke |13-27| Pit, from Alt Mid ------------------|THROW|--"				//13
alias  "ispam2"			"setpos_exact 726.031250 220.960938 93.973953;setang 3.392517 -178.346375 0.000000"
alias  "ispam"			"setpos_exact 726.031250 220.962921 93.973755;setang -55.241890 -8.699924 0.000000"
alias  "echo_islmam"	"echo T Smoke |14-27| Left Mid, from Alt Mid -------------|THROW|--"				//14
alias  "islmam2"		"setpos_exact 726.000305 246.549271 91.565147;setang 35.154942 179.843384 0.000000"
alias  "islmam"			"setpos_exact 726.000305 246.549271 91.565147;setang -30.079454 40.926552 0.000000"
alias  "echo_isasm"		"echo T Smoke |15-27| Arch, from 2nd Mid -----------------|THROW|--"				//15
alias  "isasm2"			"setpos_exact 726.031250 288.680084 96.031250;setang 6.763980 -179.543030 0.000000"
alias  "isasm"			"setpos_exact 726.031250 288.680084 96.031250;setang -43.560978 41.450943 0.000000"
alias  "echo_isolam"	"echo T Smoke |16-27| Outside Library, from Alt Mid ------|WALK THROW|--"			//16
alias  "isolam2"		"setpos_exact 726.031250 333.896576 96.031250;setang -4.957631 -178.648529 0.000000"
alias  "isolam"			"setpos_exact 726.006836 333.917542 96.031250;setang -45.968948 26.172327 0.000000"
alias  "echo_isham"		"echo T Smoke |17-27| Hay, from Alt Mid ------------------|THROW|--"				//17
alias  "isham2"			"setpos_exact 721.031250 393.320099 92.843742;setang 16.162397 178.676529 0.000000"
alias  "isham"			"setpos_exact 721.031250 393.320099 92.843742;setang -51.959007 -19.791485 0.000000"
alias  "echo_islm"		"echo T Smoke |18-27| Library, from Mid ------------------|THROW|--"				//18
alias  "islm2"			"setpos_exact 960.156067 434.031250 88.031250;setang 74.362251 -90.043663 0.000000"
alias  "islm"			"setpos_exact 960.156067 434.031250 88.031250;setang -47.024956 28.967554 0.000000"
alias  "echo_iscl"		"echo T Smoke |19-27| Coffin, from Logs ------------------|JUMP THROW|--"			//19
alias  "iscl2"			"setpos_exact -79.448692 1330.031250 106.708900;setang 67.217499 -141.415756 0.000000"
alias  "iscl"			"setpos_exact -79.448692 1330.031250 106.708900;setang -11.005769 69.318787 0.000000"
alias  "echo_isctl"		"echo T Smoke |20-27| Coffin, from Top Logs --------------|THROW|--"				//20
alias  "isctl2"			"setpos_exact 110.815239 1569.627441 132.013870;setang 64.148445 -162.822510 0.000000"
alias  "isctl"			"setpos_exact 110.815239 1569.627441 132.013870;setang -45.094753 76.556061 0.000000"
alias  "echo_isctsl"	"echo T Smoke |21-27| CT Spawn, from Logs ----------------|THROW|--"				//21
alias  "isctsl2"		"setpos_exact 119.999580 1587.966187 113.669106;setang 89.000000 62.591972 0.000000"
alias  "isctsl"			"setpos_exact 119.999580 1587.966187 113.669106;setang -34.798424 56.149929 0.000000"
alias  "echo_iscb"		"echo T Smoke |22-27| Coffin, from Banana ----------------|THROW|--"				//22
alias  "iscb2"			"setpos_exact 338.871887 1650.802856 122.031250;setang 71.425583 -28.472059 0.000000"
alias  "iscb"			"setpos_exact 338.871887 1650.802856 122.031250;setang -50.093639 84.572739 0.000000"
alias  "echo_isctstb"	"echo T Smoke |23-27| CT Spawn/Tree , from Banana --------|THROW|--"				//23
alias  "isctstb2"		"setpos_exact 361.207794 1795.970947 125.609856;setang 89.000000 44.645775 0.000000"
alias  "isctstb"		"setpos_exact 361.207794 1795.970947 125.609856;setang -32.027519 58.743397 0.000000"
alias  "echo_isfob"		"echo T Smoke |24-27| First Orange, from Banana-----------|THROW|--"				//24
alias  "isfob2"			"setpos_exact 460.464905 1828.470825 136.120117;setang 61.597527 -95.642250 0.000000"
alias  "isfob"			"setpos_exact 460.464905 1828.470825 136.120117;setang -25.443281 86.280159 0.000000"
alias  "echo_isctsb"	"echo T Smoke |25-27| CT Spawn, from Banana --------------|THROW|--"				//25
alias  "isctsb2"		"setpos_exact 460.448334 1828.488892 136.114594;setang 61.597683 -95.824829 0.000000"
alias  "isctsb"			"setpos_exact 460.448334 1828.488892 136.114594;setang -24.519115 62.337608 0.000000"
alias  "echo_isctbs"	"echo T Smoke |26-27| CT Boost, from Sandbags ------------|THROW|--"				//26
alias  "isctbs2"		"setpos_exact 610.974487 1873.000244 134.190033;setang 68.470566 -42.629978 0.000000"
alias  "isctbs"			"setpos_exact 610.974487 1873.000244 134.190033;setang -17.514277 69.675629 0.000000"
alias  "echo_isfos"		"echo T Smoke |27-27| Front Oranges, from Snadbags -------|THROW|--"				//27
alias  "isfos2"			"setpos_exact 664.968750 1873.031250 168.031250;setang 53.491871 -36.528191 0.000000"
alias  "isfos"			"setpos_exact 664.968750 1873.031250 168.031250;setang -29.140152 136.444611 0.000000"
//1-15 CT-Side SMOKE inferno
alias  "echo_ismcts"	"echo CT Smoke |01-15| Mid, from CT Spawn ----------------|THROW|--"				//01
alias  "ismcts2"		"setpos_exact 2129.031250 1917.968750 128.031250;setang 28.492292 154.084671 0.000000"
alias  "ismcts"			"setpos_exact 2129.031250 1917.968750 128.031250;setang -46.826851 -121.514229 0.000000"
alias  "echo_isbl"		"echo CT Smoke |02-15| Balcony, from Long ----------------|THROW|--"				//02
alias  "isbl2"			"setpos_exact 1913.227295 1225.968750 174.031250;setang 89.000000 -90.674629 0.000000"
alias  "isbl"			"setpos_exact 1913.227295 1225.968750 174.031250;setang -46.497322 -87.005005 0.000000"
alias  "echo_isowp"		"echo CT Smoke |03-15| One Way, from Pit -----------------|THROW|--"				//03
alias  "isowp2"			"setpos_exact 2631.968750 -16.031250 84.031250;setang 63.898064 34.641491 0.000000"
alias  "isowp"			"setpos_exact 2631.968750 -16.031250 84.031250;setang -5.692367 -179.128860 0.000000"
alias  "echo_isowbp"	"echo CT Smoke |04-15| One Way, from Back Pit ------------|THROW|--"				//04
alias  "isowbp2"		"setpos_exact 2643.637207 -337.031250 90.766235;setang 68.438354 39.001198 0.000000"
alias  "isowbp"			"setpos_exact 2643.637207 -337.031250 90.766235;setang -17.044886 171.898758 0.000000"
alias  "echo_isowb"		"echo CT Smoke |05-15| One Way, from Balcony -------------|THROW|--"				//05
alias  "isowb2"			"setpos_exact 2110.925537 -319.988800 292.031250;setang 89.000000 179.755096 0.000000"
alias  "isowb"			"setpos_exact 2110.925537 -319.988800 292.031250;setang -16.187532 130.413361 0.000000"
alias  "echo_isfctw"	"echo CT Smoke |06-15| Fountain, from CT Well ------------|THROW|--"				//06
alias  "isfctw2"		"setpos_exact 1971.687988 2636.702393 128.031250;setang 56.786182 -103.900604 0.000000"
alias  "isfctw"			"setpos_exact 1971.687988 2636.702393 128.031250;setang -39.996227 175.975357 0.000000"
alias  "echo_isbcts"	"echo CT Smoke |07-15| Banana, from CT Spawn -------------|THROW|--"				//07
alias  "isbcts2"		"setpos_exact 2032.023682 2975.975830 133.030960;setang 70.609924 53.842133 0.000000"
alias  "isbcts"			"setpos_exact 2032.023682 2975.975830 133.030960;setang -38.131714 -154.727448 0.000000"
alias  "echo_isboc"		"echo CT Smoke |08-15| Banana, from Outside Church -------|THROW|--"				//08
alias  "isboc2"			"setpos_exact 1439.998657 2956.278564 131.349182;setang 67.196983 53.687038 0.000000"
alias  "isboc"			"setpos_exact 1439.998657 2956.278564 131.349182;setang -29.981487 -133.287323 0.000000"
alias  "echo_isloc"		"echo CT Smoke |09-15| Logs, from Outside Church ---------|THROW|--"				//09
alias  "isloc2"			"setpos_exact 1329.921631 2977.218750 144.281250;setang 67.108711 122.368797 0.000000"
alias  "isloc"			"setpos_exact 1329.921631 2977.218750 144.281250;setang -30.755987 -129.919357 0.000000"
alias  "echo_iscbbb"	"echo CT Smoke |10-15| Close Banana, from Below Boost ----|THROW|--"				//10
alias  "iscbbb2"		"setpos_exact 1089.392944 2781.968750 128.031250;setang 88.683197 89.764977 0.000000"
alias  "iscbbb"			"setpos_exact 1089.392944 2781.968750 128.031250;setang 1.137642 -145.547897 0.000000"
alias  "echo_iscbd"		"echo CT Smoke |11-15| Close Banana, from Dark -----------|THROW|--"				//11
alias  "iscbd2"			"setpos_exact 151.968750 3063.995117 160.031250;setang 62.969921 36.176414 0.000000"
alias  "iscbd"			"setpos_exact 151.968750 3063.995117 160.031250;setang -8.019628 -40.489166 0.000000"
alias  "echo_iscbo"		"echo CT Smoke |12-15| Close Banana, from Orange ---------|THROW|--"				//12
alias  "iscbo2"			"setpos_exact 386.385803 2537.663330 160.031250;setang 15.951077 -91.710777 0.000000"
alias  "iscbo"			"setpos_exact 386.385803 2537.663330 160.031250;setang -26.500118 -19.823505 0.000000"
alias  "echo_iscbto"	"echo CT Smoke |13-15| Close Banana, from Top Orange -----|THROW|--"				//13
alias  "iscbto2"		"setpos_exact 569.914124 2520.408691 291.031250;setang 89.000000 0.134610 0.000000"
alias  "iscbto"			"setpos_exact 569.914124 2520.408691 291.031250;setang 28.873955 -28.351013 0.000000"
alias  "echo_isdbb"		"echo CT Smoke |14-15| Deep Banana, from Banana ----------|THROW|--"				//14
alias  "isdbb2"			"setpos_exact 875.968750 2481.443359 145.031250;setang 48.422989 -0.214493 0.000000"
alias  "isdbb"			"setpos_exact 875.968750 2481.443359 145.031250;setang -23.992226 -125.139305 0.000000"
alias  "echo_isows"		"echo CT Smoke |15-15| One Way, from Sandbags ---------------|THROW or R-Click|--"	//15
alias  "isows2"			"setpos_exact 610.968750 1873.031250 134.189804;setang 70.765335 -42.363400 0.000000"
alias  "isows"			"setpos_exact 610.968750 1873.031250 134.189804;setang 11.154097 165.150177 0.000000"
//1-15 T-Side MOLOTOV inferno
alias  "echo_imbam"		"echo T Molotov |01-15| Boiler, from Alt Mid -------------|THROW|--"				//01
alias  "imbam2"			"setpos_exact 695.087219 -267.968750 99.031242;setang 89.000000 -90.124680 0.000000"
alias  "imbam"			"setpos_exact 695.087219 -267.968750 99.031242;setang -21.532530 32.424114 0.000000"
alias  "echo_imprw"		"echo T Molotov |02-15| Patio Roof, from Window ----------|THROW|--"				//02
alias  "imprw2"			"setpos_exact 894.859619 -56.048077 296.031250;setang 89.000000 -1.707593 0.000000"
alias  "imprw"			"setpos_exact 894.859619 -56.048077 296.031250;setang -47.141594 0.826806 0.000000"
alias  "echo_imptm"		"echo T Molotov |03-15| Patio, from  Top Mid -------------|RUN THROW|--"			//03
alias  "imptm2"			"setpos_exact 1157.562988 589.968750 122.031250;setang 21.732782 92.508369 0.000000"
alias  "imptm"			"setpos_exact 1157.562988 589.968750 122.031250;setang -13.348514 -43.742046 0.000000"
alias  "echo_imspl"		"echo T Molotov |04-15| Small Pit, from Lanes ------------|THROW|--"				//04
alias  "imspl2"			"setpos_exact 1764.968750 -108.968750 130.073364;setang 66.494759 -27.576258 0.000000"
alias  "imspl"			"setpos_exact 1764.968750 -108.968750 130.073364;setang -27.621223 60.546925 0.000000"
alias  "echo_imdb"		"echo T Molotov |05-15| Default, from Balc ---------------|THROW|--"				//05
alias  "imdb2"			"setpos_exact 1911.199951 -160.031250 256.031250;setang 70.797127 43.552685 0.000000"
alias  "imdb"			"setpos_exact 1911.199951 -160.031250 256.031250;setang -19.570068 -70.336937 0.000000"
alias  "echo_imsb"		"echo T Molotov |06-15| Sandbags, from Banana ------------|RUN THROW|--"			//06
alias  "imsb2"			"setpos_exact 327.111023 1627.339600 122.031250;setang 89.000000 57.184258 0.000000"
alias  "imsb"			"setpos_exact 327.111023 1627.339600 122.031250;setang -11.122025 56.075432 0.000000"
alias  "echo_imfoc"		"echo T Molotov |07-15| First Orange, from Car -----------|JUMP THROW bind|--"		//07
alias  "imfoc2"			"setpos_exact 339.975342 2027.880859 128.031250;setang 33.704948 79.461784 0.000000"
alias  "imfoc"			"setpos_exact 339.972687 2027.928101 128.031250;setang -46.366074 69.403351 0.000000"
alias  "echo_imsoc"		"echo T Molotov |08-15| Second Orange, from Car ----------|JUMP THROW|--"			//08
alias  "imsoc2"			"setpos_exact 409.326050 2009.151367 128.031250;setang 31.207144 125.255600 0.000000"
alias  "imsoc"			"setpos_exact 409.345978 2009.172729 128.031250;setang -23.414471 119.236206 0.000000
alias  "echo_imdtc"		"echo T Molotov |09-15| Dark, from Top Car ---------------|THROW|--"				//09
alias  "imdtc2"			"setpos_exact 474.218750 2034.300049 203.031250;setang 89.000000 90.542824 0.000000"
alias  "imdtc"			"setpos_exact 474.218750 2034.300049 203.031250;setang -20.593023 109.524460 0.000000"
alias  "echo_imcs"		"echo T Molotov |10-15| Coffin, from Snadbags ------------|THROW|--"				//10
alias  "imcs2"			"setpos_exact 664.968750 1873.031250 168.031250;setang 74.357620 -37.418209 0.000000"
alias  "imcs"			"setpos_exact 664.968750 1873.031250 168.031250;setang -24.272781 96.641022 0.000000"
alias  "echo_imnbs"		"echo T Molotov |11-15| New Box, from Sandbags -----------|THROW|--"				//11
alias  "imnbs2"			"setpos_exact 999.982422 1878.530640 149.267227;setang 89.000000 -179.874573 0.000000"
alias  "imnbs"			"setpos_exact 999.982422 1878.530640 149.267227;setang -26.647552 141.132538 0.000000"
alias  "echo_imdcb"		"echo T Molotov |12-15| Dark, from Close Banana ----------|Step THROW|--"			//12
alias  "imdcb2"			"setpos_exact 941.959961 2108.010742 140.031250;setang 71.981766 24.942797 0.000000"
alias  "imdcb"			"setpos_exact 941.959961 2108.010742 140.031250;setang -22.160713 129.513229 0.000000"
alias  "echo_imctbb"	"echo T Molotov |13-15| CT Boost, from Banana ------------|Crouch THROW|--"			//13
alias  "imctbb2"		"setpos_exact 672.103699 2125.968750 136.031250;setang 73.397682 90.122276 0.000000"
alias  "imctbb"			"setpos_exact 672.103699 2125.968750 136.031250;setang -18.764736 69.213516 0.000000"
alias  "echo_imnbcb"	"echo T Molotov |14-15| New Box, from Close Banana -------|THROW|--"				//14
alias  "imnbcb2"		"setpos_exact 875.998718 2386.237793 145.251266;setang 12.262418 -0.397832 0.000000"
alias  "imnbcb"			"setpos_exact 875.998718 2386.237793 145.251266;setang -17.886372 166.898911 0.000000"
alias  "echo_imfcc"		"echo T Molotov |15-15| Front Coffin, from Church --------|JUMP THROW|--"			//15
alias  "imfcc2"			"setpos_exact 929.176636 3295.995117 144.031250;setang 89.000000 -179.929657 0.000000"
alias  "imfcc"			"setpos_exact 929.176636 3295.995117 144.031250;setang -45.887463 -131.960571 0.000000"
//1-5 CT-Side MOLOTOV inferno
alias  "echo_imocts"	"echo CT Molotov |01-05| Oranges, from CT Spawn ----------|THROW|--"				//01
alias  "imocts2"		"setpos_exact 1483.840210 2893.968750 129.470245;setang 23.162680 89.752396 0.000000"
alias  "imocts"			"setpos_exact 1483.840210 2893.968750 129.470245;setang -16.120533 -162.139648 0.000000"
alias  "echo_imdt"		"echo CT Molotov |02-05| Dark, from Tree -----------------|THROW|--"				//02
alias  "imdt2"			"setpos_exact 1128.016113 2643.000488 134.497559;setang 68.160667 -133.775421 0.000000"
alias  "imdt"			"setpos_exact 1128.016113 2643.000488 134.497559;setang -24.899345 154.803116 0.000000"
alias  "echo_imnbt"		"echo CT Molotov |03-05| New Box, from Tree --------------|THROW|--"				//03
alias  "imnbt2"			"setpos_exact 1128.000122 2643.031250 134.494995;setang 73.464455 -158.738037 0.000000"
alias  "imnbt"			"setpos_exact 1128.000122 2643.031250 134.494995;setang -23.001171 -178.221207 0.000000"
alias  "echo_imcwc"		"echo CT Molotov |04-05| Coffin/water, from Church -------|JUMP THROW|--"			//04
alias  "imcwc2"			"setpos_exact 929.176636 3295.995117 144.031250;setang 89.000000 -179.929306 0.000000"
alias  "imcwc"			"setpos_exact 929.176636 3295.995117 144.031250;setang -45.887463 -131.960571 0.000000"
alias  "echo_imcbf"		"echo CT Molotov |05-05| Close Banana, from Fountain -----|THROW|--"				//05
alias  "imcbf2"			"setpos_exact 247.993393 2883.031250 160.031250;setang 68.461006 -42.889030 0.000000"
alias  "imcbf"			"setpos_exact 248.001083 2883.031250 160.031250;setang -19.767860 -44.473083 0.000000"
//1-5 T-Side FLASH inferno
alias  "echo_iftmm"		"echo T FLASH |01-05| Top Mid, from Mexico --------------|Walk THROW|--"			//01
alias  "iftmm2"			"setpos_exact 272.031250 644.011841 20.031250;setang 18.852793 -134.103165 0.000000"
alias  "iftmm"			"setpos_exact 272.031250 644.011841 20.031250;setang -30.673660 0.774419 0.000000"
alias  "echo_iftmam"	"echo T FLASH |02-05| Top Mid, from Alt Mid -------------|THROW|--"					//02
alias  "iftmam2"		"setpos_exact 736.005554 159.993500 99.358513;setang 76.193367 179.680832 0.000000"
alias  "iftmam"			"setpos_exact 736.005554 159.993500 99.358513;setang -28.429869 50.241528 0.000000"
alias  "echo_ifpa"		"echo T FLASH |03-05| Plat, from Apps -------------------|WALK THROW|--"			//03
alias  "ifpa2"			"setpos_exact 1275.968750 -111.968750 256.031250;setang 66.452103 -33.207809 0.000000"
alias  "ifpa"			"setpos_exact 1275.968750 -111.968750 256.031250;setang 9.454458 116.691383 0.000000"
alias  "echo_ifpga"		"echo T FLASH |04-05| Pit/Graveyard, from Apps ----------|CROUCH THROW|--"			//04
alias  "ifpga2"			"setpos_exact 1329.031250 -365.989349 256.031250;setang 68.922844 -133.420898 0.000000"
alias  "ifpga"			"setpos_exact 1329.031250 -365.989349 256.031250;setang -29.733957 -22.831499 0.000000"
alias  "echo_ifcb"		"echo T FLASH |05-05| Car, from Banana ------------------|THROW or R-CLICK|--"		//05
alias  "ifcb2"			"setpos_exact 273.968750 1378.440918 107.031250;setang 69.277847 33.036057 0.000000"
alias  "ifcb"			"setpos_exact 273.982513 1378.460449 107.031250;setang -71.196579 151.149689 0.000000"
//1-14 CT-Side FLASH inferno
alias  "echo_ifoaf"		"echo CT Flash |01-14| Long, from Arch -------------------|THROW|--"				//01
alias  "ifoaf2"			"setpos_exact 1762.031250 1447.968750 160.031250;setang 72.629967 127.490471 0.000000"
alias  "ifoaf"			"setpos_exact 1762.031250 1447.951416 160.031250;setang -40.705269 -37.096870 0.000000"
alias  "echo_iftmc"		"echo CT Flash |02-14| Top Mid, from Cubby ---------------|R-CLICK|--"				//02
alias  "iftmc2"			"setpos_exact 1291.031250 1186.031250 160.031250;setang 68.203468 -136.542465 0.000000"
alias  "iftmc"			"setpos_exact 1291.031250 1186.031250 160.031250;setang -77.154930 -1.665051 0.000000"
alias  "echo_iftml"		"echo CT Flash |03-14| Top Mid, from Long ----------------|R-CLICK|--"				//03
alias  "iftml2"			"setpos_exact 1721.968750 1012.031250 171.031250;setang 67.049400 -44.915970 0.000000"
alias  "iftml"			"setpos_exact 1721.968750 1012.001038 171.031250;setang -35.408978 -179.344696 0.000000"
alias  "echo_iftmcl"	"echo CT Flash |04-14| Top Mid, From Close Long ----------|THROW|--"				//04
alias  "iftmcl2"		"setpos_exact 1347.063721 829.999756 145.145462;setang 47.367069 92.764824 0.000000"
alias  "iftmcl"			"setpos_exact 1347.063721 829.999756 145.145462;setang -54.995609 98.371170 0.000000"
alias  "echo_ifmtm"		"echo CT Flash |05-14| Mid, from Top Mid -----------------|THROW|--"				//05
alias  "ifmtm2"			"setpos_exact 1517.991821 792.031250 139.955093;setang 71.236572 -44.609974 0.000000"
alias  "ifmtm"			"setpos_exact 1517.991821 792.031250 139.955093;setang -16.913090 -160.268402 0.000000"
alias  "echo_iftmb"		"echo CT Flash |06-14| Top Mid, from Boiler --------------|RUN THROW|--"			//06
alias  "iftmb2"			"setpos_exact 1314.031250 347.222870 129.031250;setang 47.786236 179.553925 0.000000"
alias  "iftmb"			"setpos_exact 1314.031250 347.222870 129.031250;setang -26.450598 -90.553787 0.000000"
alias  "echo_ifaa"		"echo CT Flash |07-14| Alley, from Apps ------------------|THROW|--"				//07
alias  "ifaa2"			"setpos_exact 1121.031250 -367.968750 256.031250;setang 70.791458 -136.935715 0.000000"
alias  "ifaa"			"setpos_exact 1121.031250 -367.968750 256.031250;setang -6.798101 74.801872 0.000000"
alias  "echo_ifbsct"	"echo CT Flash |08-14| B Site, from CT -------------------|THROW|--"				//08
alias  "ifbsct2"		"setpos_exact 1744.031250 2694.496826 160.031250;setang 73.685669 -178.862701 0.000000"
alias  "ifbsct"			"setpos_exact 1744.031250 2694.496826 160.031250;setang -2.161512 -100.138107 0.000000"
alias  "echo_ifcbt"		"echo CT Flash |09-14| Close Banana, from Tree  ----------|RUN THROW|--"			//09
alias  "ifcbt2"			"setpos_exact 1023.965576 2654.031250 133.199738;setang 35.662041 -90.998108 0.000000"
alias  "ifcbt"			"setpos_exact 1023.965576 2654.031250 133.199738;setang -9.587554 -0.419661 0.000000"
alias  "echo_ifbfo"		"echo CT Flash |10-14| Banana, from First Orange ---------|THROW|--"				//10
alias  "ifbfo2"			"setpos_exact 498.968750 2444.031250 160.031250;setang 66.782112 -43.682770 0.000000"
alias  "ifbfo"			"setpos_exact 498.968750 2444.031250 160.031250;setang 1.996500 166.338852 0.000000"
alias  "echo_ifcbfo"	"echo CT Flash |11-14| Close Banana, from 1st Orange------|THROW|--"				//11
alias  "ifcbfo2"		"setpos_exact 498.968750 2444.031250 160.031250;setang 68.118561 -37.038818 0.000000"
alias  "ifcbfo"			"setpos_exact 498.968750 2444.031250 160.031250;setang 1.748943 142.807571 0.000000"
alias  "echo_ifbsbo"	"echo CT Flash |12-14| B Site/Banana, from Oranges -------|THROW|--"				//12
alias  "ifbsbo2"		"setpos_exact 498.980377 2444.031250 160.031250;setang 48.915810 -45.087517 0.000000"
alias  "ifbsbo"			"setpos_exact 498.980377 2444.031250 160.031250;setang -20.806635 143.302826 0.000000"
alias  "echo_ifbcb"		"echo CT Flash |13-14| Banana from, Close Banana ---------|THROW|--"				//13
alias  "ifbcb2"			"setpos_exact 941.968750 2221.968750 142.401779;setang 69.262489 44.997009 0.000000"
alias  "ifbcb"			"setpos_exact 941.968750 2221.968750 142.401779;setang -29.420738 -142.099823 0.000000"
alias  "echo_ifsb"		"echo CT Flash |14-14| Banana, from Sandbags -------------|THROW|--"				//14
alias  "ifsb2"			"setpos_exact 610.968750 1873.031250 134.189789;setang 70.600235 -42.927467 0.000000"
alias  "ifsb"			"setpos_exact 610.968750 1873.031250 134.189804;setang -44.186985 -0.872295 0.000000"


//1-27 T-Side SMOKE Lineup inferno
alias  "ITSL1"   "echo_istmts;istmts;	bind kp_ins ITSP1;   alias ITSLU ITSL2;   alias ITSLD ITSL27"
alias  "ITSL2"   "echo_isrmm;isrmm;		bind kp_ins ITSP2;   alias ITSLU ITSL3;   alias ITSLD ITSL1"
alias  "ITSL3"   "echo_ismm;ismm;		bind kp_ins ITSP3;   alias ITSLU ITSL4;   alias ITSLD ITSL2"
alias  "ITSL4"   "echo_islam;islam;		bind kp_ins ITSP4;   alias ITSLU ITSL5;   alias ITSLD ITSL3"
alias  "ITSL5"   "echo_islmdam;islmdam;	bind kp_ins ITSP5;   alias ITSLU ITSL6;   alias ITSLD ITSL4"
alias  "ITSL6"   "echo_islham;islham;	bind kp_ins ITSP6;   alias ITSLU ITSL7;   alias ITSLD ITSL5"
alias  "ITSL7"   "echo_isbham;isbham;	bind kp_ins ITSP7;   alias ITSLU ITSL8;   alias ITSLD ITSL6"
alias  "ITSL8"   "echo_ismam;ismam;		bind kp_ins ITSP8;   alias ITSLU ITSL9;   alias ITSLD ITSL7"
alias  "ITSL9"   "echo_isrmam;isrmam;	bind kp_ins ITSP9;   alias ITSLU ITSL10;  alias ITSLD ITSL8"
alias  "ITSL10"  "echo_isbam;isbam;		bind kp_ins ITSP10;  alias ITSLU ITSL11;  alias ITSLD ITSL9"
alias  "ITSL11"  "echo_isbpam;isbpam;	bind kp_ins ITSP11;  alias ITSLU ITSL12;  alias ITSLD ITSL10"
alias  "ITSL12"  "echo_isaam;isaam;		bind kp_ins ITSP12;  alias ITSLU ITSL13;  alias ITSLD ITSL11"
alias  "ITSL13"  "echo_ispam;ispam;		bind kp_ins ITSP13;  alias ITSLU ITSL14;  alias ITSLD ITSL12"
alias  "ITSL14"  "echo_islmam;islmam;	bind kp_ins ITSP14;  alias ITSLU ITSL15;  alias ITSLD ITSL13"
alias  "ITSL15"  "echo_isasm;isasm;		bind kp_ins ITSP15;  alias ITSLU ITSL16;  alias ITSLD ITSL14"
alias  "ITSL16"  "echo_isolam;isolam;	bind kp_ins ITSP16;  alias ITSLU ITSL17;  alias ITSLD ITSL15"
alias  "ITSL17"  "echo_isham;isham;		bind kp_ins ITSP17;  alias ITSLU ITSL18;  alias ITSLD ITSL16"
alias  "ITSL18"  "echo_islm;islm;		bind kp_ins ITSP18;  alias ITSLU ITSL19;  alias ITSLD ITSL17"
alias  "ITSL19"  "echo_iscl;iscl;		bind kp_ins ITSP19;  alias ITSLU ITSL20;  alias ITSLD ITSL18"
alias  "ITSL20"  "echo_isctl;isctl;		bind kp_ins ITSP20;  alias ITSLU ITSL21;  alias ITSLD ITSL19"
alias  "ITSL21"  "echo_isctsl;isctsl;	bind kp_ins ITSP21;  alias ITSLU ITSL22;  alias ITSLD ITSL20"
alias  "ITSL22"  "echo_iscb;iscb;		bind kp_ins ITSP22;  alias ITSLU ITSL23;  alias ITSLD ITSL21"
alias  "ITSL23"  "echo_isctstb;isctstb;	bind kp_ins ITSP23;  alias ITSLU ITSL24;  alias ITSLD ITSL22"
alias  "ITSL24"  "echo_isfob;isfob;		bind kp_ins ITSP24;  alias ITSLU ITSL25;  alias ITSLD ITSL23"
alias  "ITSL25"  "echo_isctsb;isctsb;	bind kp_ins ITSP25;  alias ITSLU ITSL26;  alias ITSLD ITSL24"
alias  "ITSL26"  "echo_isctbs;isctbs;	bind kp_ins ITSP26;  alias ITSLU ITSL27;  alias ITSLD ITSL25"
alias  "ITSL27"  "echo_isfos;isfos;		bind kp_ins ITSP27;  alias ITSLU ITSL1;   alias ITSLD ITSL26"

//1-27 T-SIDE SMOKE Position inferno
alias  "ITSP1"   "istmts2;	bind kp_ins ITSL1"
alias  "ITSP2"   "isrmm2;	bind kp_ins ITSL2"
alias  "ITSP3"   "ismm2;	bind kp_ins ITSL3"
alias  "ITSP4"   "ismm2;	bind kp_ins ITSL4"
alias  "ITSP5"   "islmdam2;	bind kp_ins ITSL5"
alias  "ITSP6"   "islham2;	bind kp_ins ITSL6"
alias  "ITSP7"   "isbham2;	bind kp_ins ITSL7"
alias  "ITSP8"   "ismam2;	bind kp_ins ITSL8"
alias  "ITSP9"   "isrmam2;	bind kp_ins ITSL9"
alias  "ITSP10"  "isbam2;	bind kp_ins ITSL10"
alias  "ITSP11"  "isbpam2;	bind kp_ins ITSL11"
alias  "ITSP12"  "isaam2;	bind kp_ins ITSL12"
alias  "ITSP13"  "ispam2;	bind kp_ins ITSL13"
alias  "ITSP14"  "islmam2;	bind kp_ins ITSL14"
alias  "ITSP15"  "isasm2;	bind kp_ins ITSL15"
alias  "ITSP16"  "isolam2;	bind kp_ins ITSL16"
alias  "ITSP17"  "isham2;	bind kp_ins ITSL17"
alias  "ITSP18"  "islm2;	bind kp_ins ITSL18"
alias  "ITSP19"  "iscl2;	bind kp_ins ITSL19"
alias  "ITSP20"  "isctl2;	bind kp_ins ITSL20"
alias  "ITSP21"  "isctsl2;	bind kp_ins ITSL21"
alias  "ITSP22"  "iscb2;	bind kp_ins ITSL22"
alias  "ITSP23"  "isctstb2;	bind kp_ins ITSL23"
alias  "ITSP24"  "isfob2;	bind kp_ins ITSL24"
alias  "ITSP25"  "isctsb2;	bind kp_ins ITSL25"
alias  "ITSP26"  "isctbs2;	bind kp_ins ITSL26"
alias  "ITSP27"  "isfos2;	bind kp_ins ITSL27"
//1-15 CT-Side SMOKE Lineup inferno
alias  "ICTSL1"   "echo_ismcts;ismcts;	bind kp_ins ICTSP1;  alias ICTSLU ICTSL2;  alias ICTSLD ICTSL15"
alias  "ICTSL2"   "echo_isbl;ismcts;	bind kp_ins ICTSP2;  alias ICTSLU ICTSL3;  alias ICTSLD ICTSL1"
alias  "ICTSL3"   "echo_isowp;isowp;	bind kp_ins ICTSP3;  alias ICTSLU ICTSL4;  alias ICTSLD ICTSL2"
alias  "ICTSL4"   "echo_isowbp;isowbp;	bind kp_ins ICTSP4;  alias ICTSLU ICTSL5;  alias ICTSLD ICTSL3"
alias  "ICTSL5"   "echo_isowb;isowb;	bind kp_ins ICTSP5;  alias ICTSLU ICTSL6;  alias ICTSLD ICTSL4"
alias  "ICTSL6"   "echo_isfctw;isfctw;	bind kp_ins ICTSP6;  alias ICTSLU ICTSL7;  alias ICTSLD ICTSL5"
alias  "ICTSL7"   "echo_isbcts;isbcts;	bind kp_ins ICTSP7;  alias ICTSLU ICTSL8;  alias ICTSLD ICTSL6"
alias  "ICTSL8"   "echo_isboc;isboc;	bind kp_ins ICTSP8;  alias ICTSLU ICTSL9;  alias ICTSLD ICTSL7"
alias  "ICTSL9"   "echo_isloc;isloc;	bind kp_ins ICTSP9;  alias ICTSLU ICTSL10; alias ICTSLD ICTSL8"
alias  "ICTSL10"  "echo_iscbbb;iscbbb;	bind kp_ins ICTSP10; alias ICTSLU ICTSL11; alias ICTSLD ICTSL9"
alias  "ICTSL11"  "echo_iscbd;iscbd;	bind kp_ins ICTSP11; alias ICTSLU ICTSL12; alias ICTSLD ICTSL10"
alias  "ICTSL12"  "echo_iscbo;iscbo;	bind kp_ins ICTSP12; alias ICTSLU ICTSL13; alias ICTSLD ICTSL11"
alias  "ICTSL13"  "echo_iscbto;iscbto;	bind kp_ins ICTSP13; alias ICTSLU ICTSL14; alias ICTSLD ICTSL12"
alias  "ICTSL14"  "echo_isdbb;isdbb;	bind kp_ins ICTSP14; alias ICTSLU ICTSL15; alias ICTSLD ICTSL13"
alias  "ICTSL15"  "echo_isows;isows;	bind kp_ins ICTSP15; alias ICTSLU ICTSL1 ; alias ICTSLD ICTSL14"
//1-15 CT-Side SMOKE Position inferno
alias  "ICTSP1"   "ismcts2;	bind kp_ins ICTSL1"
alias  "ICTSP2"   "ismcts2;	bind kp_ins ICTSL2"
alias  "ICTSP3"   "isowp2;	bind kp_ins ICTSL3"
alias  "ICTSP4"   "isowbp2;	bind kp_ins ICTSL4"
alias  "ICTSP5"   "isowb2;	bind kp_ins ICTSL5"
alias  "ICTSP6"   "isfctw2;	bind kp_ins ICTSL6"
alias  "ICTSP7"   "isbcts2;	bind kp_ins ICTSL7"
alias  "ICTSP8"   "isboc2;	bind kp_ins ICTSL8"
alias  "ICTSP9"   "isloc2;	bind kp_ins ICTSL9"
alias  "ICTSP10"  "iscbbb2;	bind kp_ins ICTSL10"
alias  "ICTSP11"  "iscbd2;	bind kp_ins ICTSL11"
alias  "ICTSP12"  "iscbo2;	bind kp_ins ICTSL12"
alias  "ICTSP13"  "iscbto2;	bind kp_ins ICTSL13"
alias  "ICTSP14"  "isdbb2;	bind kp_ins ICTSL14"
alias  "ICTSP15"  "isows2;	bind kp_ins ICTSL15"
//T-Side SMOKE
alias  ITSLU  ITSL1
alias  ITSLD  ITSL1
//CT-Side SMOKE 
alias  ICTSLU  ICTSL1
alias  ICTSLD  ICTSL1


//1-15 T-Side MOLOROV Lineup inferno                        
alias  "ITML1"   "echo_imbam;imbam;		bind kp_ins ITMP1;  alias ITMLU ITML2;  alias ITMLD ITML15"
alias  "ITML2"   "echo_imprw;imprw;		bind kp_ins ITMP2;  alias ITMLU ITML3;  alias ITMLD ITML1"
alias  "ITML3"   "echo_imptm;imptm;		bind kp_ins ITMP3;  alias ITMLU ITML4;  alias ITMLD ITML2"
alias  "ITML4"   "echo_imspl;imspl;		bind kp_ins ITMP4;  alias ITMLU ITML5;  alias ITMLD ITML3"
alias  "ITML5"   "echo_imdb;imdb;		bind kp_ins ITMP5;  alias ITMLU ITML6;  alias ITMLD ITML4"
alias  "ITML6"   "echo_imsb;imsb;		bind kp_ins ITMP6;  alias ITMLU ITML7;  alias ITMLD ITML5"
alias  "ITML7"   "echo_imfoc;imfoc;		bind kp_ins ITMP7;  alias ITMLU ITML8;  alias ITMLD ITML6"
alias  "ITML8"   "echo_imsoc;imsoc;		bind kp_ins ITMP8;  alias ITMLU ITML9;  alias ITMLD ITML7"
alias  "ITML9"   "echo_imdtc;imdtc;		bind kp_ins ITMP9;  alias ITMLU ITML10; alias ITMLD ITML8"
alias  "ITML10"  "echo_imcs;imcs;		bind kp_ins ITMP10; alias ITMLU ITML11; alias ITMLD ITML9"
alias  "ITML11"  "echo_imnbs;imnbs;		bind kp_ins ITMP11; alias ITMLU ITML12; alias ITMLD ITML10"
alias  "ITML12"  "echo_imdcb;imdcb;		bind kp_ins ITMP12; alias ITMLU ITML13; alias ITMLD ITML11"
alias  "ITML13"  "echo_imctbb;imctbb;	bind kp_ins ITMP13; alias ITMLU ITML14; alias ITMLD ITML12"
alias  "ITML14"  "echo_imnbcb;imnbcb;	bind kp_ins ITMP14; alias ITMLU ITML15; alias ITMLD ITML13"
alias  "ITML15"  "echo_imfcc;imfcc;		bind kp_ins ITMP15; alias ITMLU ITML1 ; alias ITMLD ITML14"
//1-15 T-Side MOLOTOV Position inferno
alias  "ITMP1"   "imbam2;	bind kp_ins ITML1"
alias  "ITMP2"   "imprw2;	bind kp_ins ITML2"
alias  "ITMP3"   "imptm2;	bind kp_ins ITML3"
alias  "ITMP4"   "imspl2;	bind kp_ins ITML4"
alias  "ITMP5"   "imdb2;	bind kp_ins ITML5"
alias  "ITMP6"   "imsb2;	bind kp_ins ITML6"
alias  "ITMP7"   "imfoc2;	bind kp_ins ITML7"
alias  "ITMP8"   "imsoc2;	bind kp_ins ITML8"
alias  "ITMP9"   "imdtc2;	bind kp_ins ITML9"
alias  "ITMP10"  "imcs2;	bind kp_ins ITML10"
alias  "ITMP11"  "imnbs2;	bind kp_ins ITML11"
alias  "ITMP12"  "imdcb2;	bind kp_ins ITML12"
alias  "ITMP13"  "imctbb2;	bind kp_ins ITML13"
alias  "ITMP14"  "imnbcb2;	bind kp_ins ITML14"
alias  "ITMP15"  "imfcc2;	bind kp_ins ITML15"
//1-5 CT-Side MOLOTOV Lineup inferno
alias  "ICTML1"  "echo_imocts;imocts;	bind kp_ins ICTMP1; alias ICTMLU ICTML2; alias ICTMLD ICTML5"
alias  "ICTML2"  "echo_imdt;imdt;		bind kp_ins ICTMP2; alias ICTMLU ICTML3; alias ICTMLD ICTML1"
alias  "ICTML3"  "echo_imnbt;imnbt;		bind kp_ins ICTMP3; alias ICTMLU ICTML4; alias ICTMLD ICTML2"
alias  "ICTML4"  "echo_imcwc;imcwc;		bind kp_ins ICTMP4; alias ICTMLU ICTML5; alias ICTMLD ICTML3"
alias  "ICTML5"  "echo_imcbf;imcbf;		bind kp_ins ICTMP5; alias ICTMLU ICTML1; alias ICTMLD ICTML4"
//1-5 CT-Side MOLOTOV Position inferno
alias  "ICTMP1"  "imocts2;	bind kp_ins ICTML1"
alias  "ICTMP2"  "imdt2;	bind kp_ins ICTML2"
alias  "ICTMP3"  "imnbt2;	bind kp_ins ICTML3"
alias  "ICTMP4"  "imcwc2;	bind kp_ins ICTML4"
alias  "ICTMP5"  "imcbf2;	bind kp_ins ICTML5"
//T-Side MOLOTOV
alias  ITMLU  ITML1
alias  ITMLD  ITML1
//CT-Side MOLOTOV
alias  ICTMLU  ICTML1
alias  ICTMLD  ICTML1


//1-5 T-Side FLASH Lineup inferno
alias  "ITFL1"  "echo_iftmm;iftmm;		bind kp_ins ITFP1; alias ITFLU ITFL2; alias ITFLD ITFL5"
alias  "ITFL2"  "echo_iftmam;iftmam;	bind kp_ins ITFP2; alias ITFLU ITFL3; alias ITFLD ITFL1"
alias  "ITFL3"  "echo_ifpa;ifpa;		bind kp_ins ITFP3; alias ITFLU ITFL4; alias ITFLD ITFL2"
alias  "ITFL4"  "echo_ifpga;ifpga;		bind kp_ins ITFP4; alias ITFLU ITFL5; alias ITFLD ITFL3"
alias  "ITFL5"  "echo_ifcb;ifcb;		bind kp_ins ITFP5; alias ITFLU ITFL1; alias ITFLD ITFL4"
//1-5 T-Side FLASH Position inferno
alias  "ITFP1"  "iftmm2;	bind kp_ins ITFL1"
alias  "ITFP2"  "iftmam2;	bind kp_ins ITFL2"
alias  "ITFP3"  "ifpa2;		bind kp_ins ITFL3"
alias  "ITFP4"  "ifpga2;	bind kp_ins ITFL4"
alias  "ITFP5"  "ifcb2;		bind kp_ins ITFL5"
//1-14 CT-Side FLASH Lineup inferno
alias  "ICTFL1"   "echo_ifoaf;ifoaf;	bind kp_ins ICTFP1;  alias ICTFLU ICTFL2;  alias ICTFLD ICTFL14"
alias  "ICTFL2"   "echo_iftmc;iftmc;	bind kp_ins ICTFP2;  alias ICTFLU ICTFL3;  alias ICTFLD ICTFL1"
alias  "ICTFL3"   "echo_iftml;iftml;	bind kp_ins ICTFP3;  alias ICTFLU ICTFL4;  alias ICTFLD ICTFL2"
alias  "ICTFL4"   "echo_iftmcl;iftmcl;	bind kp_ins ICTFP4;  alias ICTFLU ICTFL5;  alias ICTFLD ICTFL3"
alias  "ICTFL5"   "echo_ifmtm;ifmtm;	bind kp_ins ICTFP5;  alias ICTFLU ICTFL6;  alias ICTFLD ICTFL4"
alias  "ICTFL6"   "echo_iftmb;iftmb;	bind kp_ins ICTFP6;  alias ICTFLU ICTFL7;  alias ICTFLD ICTFL5"
alias  "ICTFL7"   "echo_ifaa;ifaa;		bind kp_ins ICTFP7;  alias ICTFLU ICTFL8;  alias ICTFLD ICTFL6"
alias  "ICTFL8"   "echo_ifbsct;ifbsct;	bind kp_ins ICTFP8;  alias ICTFLU ICTFL9;  alias ICTFLD ICTFL7"
alias  "ICTFL9"   "echo_ifcbt;ifcbt;	bind kp_ins ICTFP9;  alias ICTFLU ICTFL10; alias ICTFLD ICTFL8"
alias  "ICTFL10"  "echo_ifbfo;ifbfo;	bind kp_ins ICTFP10; alias ICTFLU ICTFL11; alias ICTFLD ICTFL9"
alias  "ICTFL11"  "echo_ifcbfo;ifcbfo;	bind kp_ins ICTFP11; alias ICTFLU ICTFL12; alias ICTFLD ICTFL10"
alias  "ICTFL12"  "echo_ifbsbo;ifbsbo;	bind kp_ins ICTFP12; alias ICTFLU ICTFL13; alias ICTFLD ICTFL11"
alias  "ICTFL13"  "echo_ifbcb;ifbcb;	bind kp_ins ICTFP13; alias ICTFLU ICTFL14; alias ICTFLD ICTFL12"
alias  "ICTFL14"  "echo_ifsb;ifsb;		bind kp_ins ICTFP14; alias ICTFLU ICTFL1 ; alias ICTFLD ICTFL13"
//1-14 CT-Side FLASH Position inferno
alias  "ICTFP1"   "ifoaf2;	bind kp_ins ICTFL1"
alias  "ICTFP2"   "iftmc2;	bind kp_ins ICTFL2"
alias  "ICTFP3"   "iftml2;	bind kp_ins ICTFL3"
alias  "ICTFP4"   "iftmcl2;	bind kp_ins ICTFL4"
alias  "ICTFP5"   "ifmtm2;	bind kp_ins ICTFL5"
alias  "ICTFP6"   "iftmb2;	bind kp_ins ICTFL6"
alias  "ICTFP7"   "ifaa2;	bind kp_ins ICTFL7"
alias  "ICTFP8"   "ifbsct2;	bind kp_ins ICTFL8"
alias  "ICTFP9"   "ifcbt2;	bind kp_ins ICTFL9"
alias  "ICTFP10"  "ifbfo2;	bind kp_ins ICTFL10"
alias  "ICTFP11"  "ifcbfo2;	bind kp_ins ICTFL11"
alias  "ICTFP12"  "ifbsbo2;	bind kp_ins ICTFL12"
alias  "ICTFP13"  "ifbcb2;	bind kp_ins ICTFL13"
alias  "ICTFP14"  "ifsb2;	bind kp_ins ICTFL14"
//T-Side FLASH
alias  ITFLU  ITFL1
alias  ITFLD  ITFL1
//CT-Side FLASH
alias  ICTFLU  ICTFL1
alias  ICTFLD  ICTFL1



//Change Nade DUST2
alias  "dust2ts"	"say SMOKE -----|01-14|--------| T SMOKE --|------SMOKE;	bind rightarrow DTSLU; bind leftarrow DTSLD;  alias d2tn  dust2tm"
alias  "dust2tm"	"say MOLOTOV ---|01-04|--------| T MOLOTOV |----MOLOTOV;	bind rightarrow DTMLU; bind leftarrow DTMLD;  alias d2tn  dust2tf"
alias  "dust2tf"	"say FLASH -----|01-07|--------| T FLASH --|------FLASH;	bind rightarrow DTFLU; bind leftarrow DTFLD;  alias d2tn  dust2ts"
alias  "dust2cts"	"say SMOKE -----|01-08|-------| CT SMOKE --|------SMOKE;	bind rightarrow DCTSLU;bind leftarrow DCTSLD; alias d2ctn dust2ctm"
alias  "dust2ctm"	"say MOLOTOV ---|01-06|-------| CT MOLOTOV |----MOLOTOV;	bind rightarrow DCTMLU;bind leftarrow DCTMLD; alias d2ctn dust2ctf"
alias  "dust2ctf"	"say FLASH -----|01-10|-------| CT FLASH --|------FLASH;	bind rightarrow DCTFLU;bind leftarrow DCTFLD; alias d2ctn dust2cts"
alias  d2tn   dust2ts
alias  d2ctn  dust2cts

//Change Nade MIRAGE
alias  "miragets"	"say SMOKE ---- |01-33|--------| T SMOKE --|------SMOKE;	bind rightarrow MTSLU; bind leftarrow MTSLD;  alias mitn  miragetm"
alias  "miragetm"	"say MOLOTOV ---|01-07|--------| T MOLOTOV |----MOLOTOV;	bind rightarrow MTMLU; bind leftarrow MTMLD;  alias mitn  miragetf"
alias  "miragetf"	"say FLASH -----|01-05|--------| T FLASH --|------FLASH;	bind rightarrow MTFLU; bind leftarrow MTFLD;  alias mitn  miragets"
alias  "miragects"	"say SMOKE -----|01-10|-------| CT SMOKE --|------SMOKE;	bind rightarrow MCTSLU;bind leftarrow MCTSLD; alias mictn miragectm"
alias  "miragectm"	"say MOLOTOV ---|01-02|-------| CT MOLOTOV |----MOLOTOV;	bind rightarrow MCTMLU;bind leftarrow MCTMLD; alias mictn miragectf"
alias  "miragectf"	"say FLASH -----|01-12|-------| CT FLASH --|------FLASH;	bind rightarrow MCTFLU;bind leftarrow MCTFLD; alias mictn miragects"
alias  mitn  miragets
alias  mictn miragects

//Change Nade CACHE
alias  "cachets"	"say SMOKE -----|01-23|--------| T SMOKE --|------SMOKE;	bind rightarrow CTSLU;  bind leftarrow CTSLD;  alias catn cachetm"
alias  "cachetm"	"say MOLOTOV ---|01-08|--------| T MOLOTOV |----MOLOTOV;	bind rightarrow CTMLU;  bind leftarrow CTMLD;  alias catn cachetf"
alias  "cachetf"	"say FLASH -----|01-07|--------| T FLASH --|------FLASH;	bind rightarrow CTFLU;  bind leftarrow CTFLD;  alias catn cachets"
alias  "cachects"	"say SMOKE -----|01-08|-------| CT SMOKE --|------SMOKE;	bind rightarrow CCTSLU; bind leftarrow CCTSLD; alias cactn cachectm"
alias  "cachectm"	"say MOLOTOV ---|01-03|-------| CT MOLOTOV |------SMOKE;	bind rightarrow CCTMLU; bind leftarrow CCTMLD; alias cactn cachectf"
alias  "cachectf"	"say FLASH -----|01-07|-------| CT FLASH --|------SMOKE;	bind rightarrow CCTFLU; bind leftarrow CCTFLD; alias cactn cachects"
alias  catn  cachets
alias  cactn cachects

//Change Nade TRAIN
alias  "traints"	"say SMOKE -----|01-23|--------| T SMOKE --|------SMOKE;	bind rightarrow TTSLU;bind leftarrow TTSLD; alias trtn traintm"
alias  "traintm"	"say MOLOTOV ---|01-06|--------| T MOLOTOV |----MOLOTOV;    bind rightarrow TTMLU;bind leftarrow TTMLD; alias trtn traintf"
alias  "traintf"	"say FLASH -----|01-11|--------| T FLASH --|------FLASH;	bind rightarrow TTFLU;bind leftarrow TTFLD; alias trtn traints"
alias  "traincts"	"say SMOKE -----|01-09|-------| CT SMOKE --|------SMOKE;	bind rightarrow TCTSLU;bind leftarrow TCTSLD; alias trctn trainctm"
alias  "trainctm"	"say MOLOTOV ---|01-04|-------| CT MOLOTOV |----MOLOTOV;	bind rightarrow TCTMLU;bind leftarrow TCTMLD; alias trctn trainctf"
alias  "trainctf"	"say FLASH -----|01-08|-------| CT FLASH --|------FLASH;	bind rightarrow TCTFLU;bind leftarrow TCTFLD; alias trctn traincts"
alias  trtn  traints
alias  trctn traincts

//Chnage Nade INFERNO
alias  "infernots"	"say SMOKE -----|01-27|--------| T SMOKE --|------SMOKE; bind rightarrow ITSLU;bind leftarrow ITSLD; alias intn infernotm"
alias  "infernotm"	"say MOLOTOV ---|01-15|--------| T MOLOTOV |----MOLOTOV; bind rightarrow ITMLU;bind leftarrow ITMLD; alias intn infernotf"
alias  "infernotf"	"say FLASH -----|01-05|--------| T FLASH --|------FLASH; bind rightarrow ITFLU;bind leftarrow ITFLD; alias intn infernots"
alias  "infernocts"	"say SMOKE -----|01-15|-------| CT SMOKE --|------SMOKE; bind rightarrow ICTSLU;bind leftarrow ICTSLD; alias inctn infernoctm"
alias  "infernoctm"	"say MOLOTOV ---|01-05|-------| CT MOLOTOV |----MOLOTOV; bind rightarrow ICTMLU;bind leftarrow ICTMLD; alias inctn infernoctf"
alias  "infernoctf"	"say FLASH -----|01-14|-------| CT FLASH --|------FLASH; bind rightarrow ICTFLU;bind leftarrow ICTFLD; alias inctn infernocts"
alias  intn  infernots
alias  trctn traincts


//CrossHair Color Presets
alias "chcp1"	"exec crosshaircolor1.log ;echo Crosshair Color Preset 1 ;alias chcp chcp2 ;alias 2chcp 2chcp1"
alias "chcp2"	"exec crosshaircolor2.log ;echo Crosshair Color Preset 2 ;alias chcp chcp3 ;alias 2chcp 2chcp2"
alias "chcp3"	"exec crosshaircolor3.log ;echo Crosshair Color Preset 3 ;alias chcp chcp4 ;alias 2chcp 2chcp3"
alias "chcp4"	"exec crosshaircolor4.log ;echo Crosshair Color Preset 4 ;alias chcp chcp5 ;alias 2chcp 2chcp4"
alias "chcp5"	"exec crosshaircolor5.log ;echo Crosshair Color Preset 5 ;alias chcp chcp1 ;alias 2chcp 2chcp5"
alias chcp chcp1
//Crosshair Color Logging
alias "2chcp1"	"echo 1 ;con_logfile cfg/crosshaircolor1.log"
alias "2chcp2"	"echo 2 ;con_logfile cfg/crosshaircolor2.log"
alias "2chcp3"	"echo 3 ;con_logfile cfg/crosshaircolor3.log"
alias "2chcp4"	"echo 4 ;con_logfile cfg/crosshaircolor4.log"
alias "2chcp5"	"echo 5 ;con_logfile cfg/crosshaircolor5.log"

//Crosshair Color Blue
alias "chcbl1" 	"2chcp ;echo cl_crosshaircolor_b 0   ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |BLUE| |0  | is Saved"
alias "chcbl2" 	"2chcp ;echo cl_crosshaircolor_b 25  ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |BLUE| |25 | is Saved"
alias "chcbl3" 	"2chcp ;echo cl_crosshaircolor_b 50  ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |BLUE| |50 | is Saved"
alias "chcbl4" 	"2chcp ;echo cl_crosshaircolor_b 75  ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |BLUE| |75 | is Saved"
alias "chcbl5" 	"2chcp ;echo cl_crosshaircolor_b 100 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |BLUE| |100| is Saved"
alias "chcbl6" 	"2chcp ;echo cl_crosshaircolor_b 125 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |BLUE| |125| is Saved"
alias "chcbl7" 	"2chcp ;echo cl_crosshaircolor_b 150 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |BLUE| |150| is Saved"
alias "chcbl8" 	"2chcp ;echo cl_crosshaircolor_b 175 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |BLUE| |175| is Saved"
alias "chcbl9" 	"2chcp ;echo cl_crosshaircolor_b 200 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |BLUE| |200| is Saved"
alias "chcbl10"	"2chcp ;echo cl_crosshaircolor_b 225 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |BLUE| |225| is Saved"
alias "chcbl11"	"2chcp ;echo cl_crosshaircolor_b 255 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |BLUE| |255| is Saved"
alias  "chcb1"	"echo cl_crosshaircolor_b 0   ;cl_crosshaircolor_b 0   ;alias -chcb chcbl1  ;bind - chcb11 ;bind = chcb2"
alias  "chcb2"	"echo cl_crosshaircolor_b 25  ;cl_crosshaircolor_b 25  ;alias -chcb chcbl2  ;bind - chcb1  ;bind = chcb3"
alias  "chcb3"	"echo cl_crosshaircolor_b 50  ;cl_crosshaircolor_b 50  ;alias -chcb chcbl3  ;bind - chcb2  ;bind = chcb4"
alias  "chcb4"	"echo cl_crosshaircolor_b 75  ;cl_crosshaircolor_b 75  ;alias -chcb chcbl4  ;bind - chcb3  ;bind = chcb5"
alias  "chcb5"	"echo cl_crosshaircolor_b 100 ;cl_crosshaircolor_b 100 ;alias -chcb chcbl5  ;bind - chcb4  ;bind = chcb6"
alias  "chcb6"	"echo cl_crosshaircolor_b 125 ;cl_crosshaircolor_b 125 ;alias -chcb chcbl6  ;bind - chcb5  ;bind = chcb7"
alias  "chcb7"	"echo cl_crosshaircolor_b 150 ;cl_crosshaircolor_b 150 ;alias -chcb chcbl7  ;bind - chcb6  ;bind = chcb8"
alias  "chcb8"	"echo cl_crosshaircolor_b 175 ;cl_crosshaircolor_b 175 ;alias -chcb chcbl8  ;bind - chcb7  ;bind = chcb9"
alias  "chcb9"	"echo cl_crosshaircolor_b 200 ;cl_crosshaircolor_b 200 ;alias -chcb chcbl9  ;bind - chcb8  ;bind = chcb10"
alias  "chcb10"	"echo cl_crosshaircolor_b 225 ;cl_crosshaircolor_b 225 ;alias -chcb chcbl10 ;bind - chcb9  ;bind = chcb11"
alias  "chcb11"	"echo cl_crosshaircolor_b 255 ;cl_crosshaircolor_b 255 ;alias -chcb chcbl11 ;bind - chcb10 ;bind = chcb1"
alias +chcb "chcb6 ;cl_crosshaircolor 5"
alias -chcb "cl_crosshaircolor 5"

//Crosshair Color Green
alias "chcgl1"	"2chcp ;echo cl_crosshaircolor_g 0   ;con_logfile 0  ;echo _____________________________________ ;echo Crosshair Color |GREEN| |0  | is Saved"
alias "chcgl2"	"2chcp ;echo cl_crosshaircolor_g 25  ;con_logfile 0  ;echo _____________________________________ ;echo Crosshair Color |GREEN| |25 | is Saved"
alias "chcgl3"	"2chcp ;echo cl_crosshaircolor_g 50  ;con_logfile 0  ;echo _____________________________________ ;echo Crosshair Color |GREEN| |50 | is Saved"
alias "chcgl4"	"2chcp ;echo cl_crosshaircolor_g 75  ;con_logfile 0  ;echo _____________________________________ ;echo Crosshair Color |GREEN| |75 | is Saved"
alias "chcgl5"	"2chcp ;echo cl_crosshaircolor_g 100 ;con_logfile 0  ;echo _____________________________________ ;echo Crosshair Color |GREEN| |100| is Saved"
alias "chcgl6"	"2chcp ;echo cl_crosshaircolor_g 125 ;con_logfile 0  ;echo _____________________________________ ;echo Crosshair Color |GREEN| |125| is Saved"
alias "chcgl7"	"2chcp ;echo cl_crosshaircolor_g 150 ;con_logfile 0  ;echo _____________________________________ ;echo Crosshair Color |GREEN| |150| is Saved"
alias "chcgl8"	"2chcp ;echo cl_crosshaircolor_g 175 ;con_logfile 0  ;echo _____________________________________ ;echo Crosshair Color |GREEN| |175| is Saved"
alias "chcgl9"	"2chcp ;echo cl_crosshaircolor_g 200 ;con_logfile 0  ;echo _____________________________________ ;echo Crosshair Color |GREEN| |200| is Saved"
alias "chcgl10"	"2chcp ;echo cl_crosshaircolor_g 225 ;con_logfile 0  ;echo _____________________________________ ;echo Crosshair Color |GREEN| |225| is Saved"
alias "chcgl11"	"2chcp ;echo cl_crosshaircolor_g 255 ;con_logfile 0  ;echo _____________________________________ ;echo Crosshair Color |GREEN| |255| is Saved"
alias  "chcg1"	"echo cl_crosshaircolor_g 0   ;cl_crosshaircolor_g 0   ;alias -chcg chcgl1  ;bind - chcg11 ;bind = chcg2"
alias  "chcg2"	"echo cl_crosshaircolor_g 25  ;cl_crosshaircolor_g 25  ;alias -chcg chcgl2  ;bind - chcg1  ;bind = chcg3"
alias  "chcg3"	"echo cl_crosshaircolor_g 50  ;cl_crosshaircolor_g 50  ;alias -chcg chcgl3  ;bind - chcg2  ;bind = chcg4"
alias  "chcg4"	"echo cl_crosshaircolor_g 75  ;cl_crosshaircolor_g 75  ;alias -chcg chcgl4  ;bind - chcg3  ;bind = chcg5"
alias  "chcg5"	"echo cl_crosshaircolor_g 100 ;cl_crosshaircolor_g 100 ;alias -chcg chcgl5  ;bind - chcg4  ;bind = chcg6"
alias  "chcg6"	"echo cl_crosshaircolor_g 125 ;cl_crosshaircolor_g 125 ;alias -chcg chcgl6  ;bind - chcg5  ;bind = chcg7"
alias  "chcg7"	"echo cl_crosshaircolor_g 150 ;cl_crosshaircolor_g 150 ;alias -chcg chcgl7  ;bind - chcg6  ;bind = chcg8"
alias  "chcg8"	"echo cl_crosshaircolor_g 175 ;cl_crosshaircolor_g 175 ;alias -chcg chcgl8  ;bind - chcg7  ;bind = chcg9"
alias  "chcg9"	"echo cl_crosshaircolor_g 200 ;cl_crosshaircolor_g 200 ;alias -chcg chcgl9  ;bind - chcg8  ;bind = chcg10"
alias  "chcg10"	"echo cl_crosshaircolor_g 225 ;cl_crosshaircolor_g 225 ;alias -chcg chcgl10 ;bind - chcg9  ;bind = chcg11"
alias  "chcg11"	"echo cl_crosshaircolor_g 255 ;cl_crosshaircolor_g 255 ;alias -chcg chcgl11 ;bind - chcg10 ;bind = chcg1"
alias +chcg "chcg6;cl_crosshaircolor 5"
alias -chcg "cl_crosshaircolor 5"

//Crosshair Color Red
alias "chcrl1"  "2chcp ;echo cl_crosshaircolor_r 0   ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |RED| |0  | is Saved"
alias "chcrl2"  "2chcp ;echo cl_crosshaircolor_r 25  ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |RED| |25 | is Saved"
alias "chcrl3"  "2chcp ;echo cl_crosshaircolor_r 50  ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |RED| |50 | is Saved"
alias "chcrl4"  "2chcp ;echo cl_crosshaircolor_r 75  ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |RED| |75 | is Saved"
alias "chcrl5"  "2chcp ;echo cl_crosshaircolor_r 100 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |RED| |100| is Saved"
alias "chcrl6"  "2chcp ;echo cl_crosshaircolor_r 125 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |RED| |125| is Saved"
alias "chcrl7"  "2chcp ;echo cl_crosshaircolor_r 150 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |RED| |150| is Saved"
alias "chcrl8"  "2chcp ;echo cl_crosshaircolor_r 175 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |RED| |175| is Saved"
alias "chcrl9"  "2chcp ;echo cl_crosshaircolor_r 200 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |RED| |200| is Saved"
alias "chcrl10" "2chcp ;echo cl_crosshaircolor_r 225 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |RED| |225| is Saved"
alias "chcrl11" "2chcp ;echo cl_crosshaircolor_r 255 ;con_logfile 0 ;echo _____________________________________ ;echo Crosshair Color |RED| |255| is Saved"
alias "chcr1"	"echo cl_crosshaircolor_r 0   ;cl_crosshaircolor_r 0   ;alias -chcr chcrl1  ;bind - chcr11 ;bind = chcr2"
alias "chcr2"	"echo cl_crosshaircolor_r 25  ;cl_crosshaircolor_r 25  ;alias -chcr chcrl2  ;bind - chcr1  ;bind = chcr3"
alias "chcr3"	"echo cl_crosshaircolor_r 50  ;cl_crosshaircolor_r 50  ;alias -chcr chcrl3  ;bind - chcr2  ;bind = chcr4"
alias "chcr4"	"echo cl_crosshaircolor_r 75  ;cl_crosshaircolor_r 75  ;alias -chcr chcrl4  ;bind - chcr3  ;bind = chcr5"
alias "chcr5"	"echo cl_crosshaircolor_r 100 ;cl_crosshaircolor_r 100 ;alias -chcr chcrl5  ;bind - chcr4  ;bind = chcr6"
alias "chcr6"	"echo cl_crosshaircolor_r 125 ;cl_crosshaircolor_r 125 ;alias -chcr chcrl6  ;bind - chcr5  ;bind = chcr7"
alias "chcr7"	"echo cl_crosshaircolor_r 150 ;cl_crosshaircolor_r 150 ;alias -chcr chcrl7  ;bind - chcr6  ;bind = chcr8"
alias "chcr8"	"echo cl_crosshaircolor_r 175 ;cl_crosshaircolor_r 175 ;alias -chcr chcrl8  ;bind - chcr7  ;bind = chcr9"
alias "chcr9"	"echo cl_crosshaircolor_r 200 ;cl_crosshaircolor_r 200 ;alias -chcr chcrl9  ;bind - chcr8  ;bind = chcr10"
alias "chcr10"	"echo cl_crosshaircolor_r 225 ;cl_crosshaircolor_r 225 ;alias -chcr chcrl10 ;bind - chcr9  ;bind = chcr11"
alias "chcr11"	"echo cl_crosshaircolor_r 255 ;cl_crosshaircolor_r 255 ;alias -chcr chcrl11 ;bind - chcr10 ;bind = chcr1"
alias +chcr "chcr6;cl_crosshaircolor 5"
alias -chcr "cl_crosshaircolor 5"


alias Nuke_nades echo nuke test
alias Overpass_nades echo overpass test

//change map
alias  "nm0" "say  Dust2 -----|22 Smokes|---|10 Molotovs|---|17 Flashes|----Dust2   ;bind uparrow d2tn ;bind downarrow d2ctn ;alias nm nm1"
alias  "nm1" "say  Mirage ----|43 Smokes|---|09 Molotovs|---|16 Flashes|----Mirage  ;bind uparrow mitn ;bind downarrow mictn ;alias nm nm2"
alias  "nm2" "say  Cache ---- |31 Smokes|---|11 Molotovs|---|14 Flashes|----Cache   ;bind uparrow catn ;bind downarrow cactn ;alias nm nm3"
alias  "nm3" "say  Train -----|32 Smokes|---|10 Molotovs|---|19 Flashes|----Train   ;bind uparrow trtn ;bind downarrow trctn ;alias nm nm4"
alias  "nm4" "say  Inferno -- |40 Smokes|---|20 Molotovs|---|19 Flashes|----Inferno ;bind uparrow intn ;bind downarrow inctn ;aliaS nm nm5"
alias  "nm5" "say  Nuke ------|19 Smokes|---|03 Molotovs|---|01 Flashes|----Nuke	;alias Nuke_nades	 ;alias nm nm6"
alias  "nm6" "say  Overpass --|26 Smokes|---|?? Molotovs|---|?? Flashes|----Overpass;alias Overpass_nades;alias nm nm0"
alias  "nm"  "nm0"


//crosshair lineup
//alias  "echo_cl"  "echo Config saved to ccsc press again to change crosshair; host_writeconfig ccsc;	alias ccsc Crosshair Default"
//alias  "Crosshair Default"  "exec ccsc; 	alias ccsc Crosshair Lineup 1"
//alias  "Crosshair Lineup 1"  ";				alias ccsc Crosshair Lineup 2"
//alias  "Crosshair Lineup 2"  ";				alias ccsc Crosshair Default"
//alias ccsc Crosshair Default

//grenade trajectory timer
alias  "gtt1"  "echo Grenade Trajectory Timer OFF; sv_grenade_trajectory 0;	alias gtt gtt2"
alias  "gtt2"  "echo Grenade Trajectory Timer .5 sec;sv_grenade_trajectory 1 ;sv_grenade_trajectory_time .5;alias gtt gtt3"
alias  "gtt3"  "echo Grenade Trajectory Timer 5  sec;sv_grenade_trajectory_time 5;	alias gtt gtt4"
alias  "gtt4"  "echo Grenade Trajectory Timer 15 sec;sv_grenade_trajectory_time 15;alias gtt gtt1"
alias  "gtt"   "gtt1"

//time scale options
alias  "tso1"  "echo Time Scale 15x Faster;host_timescale 15; alias +tso tso2"
alias  "tso2"  "echo Time Scale 30x Faster;host_timescale 30; alias +tso tso1"
alias  "+tso"  "tso1"
alias  "-tso"  "host_timescale 1"

alias "nvm1" "echo Did you mean to change viewmodel |fov 65,x2,y2,z-2|; alias nvm nvm2"
alias "nvm2" "echo Custom Viewmodel ---ON---; viewmodel_fov 65;viewmodel_offset_x 2;viewmodel_offset_y 2;viewmodel_offset_z -2; alias nvm nvm1"
alias nvm nvm1

alias "+jumpthrow" "+jump;-attack"
alias "-jumpthrow" "-jump"

alias +tp "exec tppos.log"
alias -tp "exec tppos2.log"

alias +noclip "noclip 1"
alias -noclip "noclip 0"

//download flashvscript from Mythic adreN dropbox [ https://www.youtube.com/watch?v=B9hB2gICopw ]
script_execute nadetraining
script nadeSetup()
script pauseScript()
alias thrownade "thrownade_on"
alias thrownade_on "script pauseScript();script nadeSavePos(); alias thrownade "thrownade_off""
alias thrownade_off "script pauseScript(); alias thrownade "thrownade_on""


alias "binds1" "clear;echo;echo;say NUM ENTER - shows keybindings and clears console _________________________________________________________;echo;echo NUM ENTER - shows keybindings and clears console;echo;echo;echo HOW TO USE: Nade Position/Lineup binds;echo Rshift - Choose Map, Lineups For Next Maps;echo Rctrl - Map optionals/not yet implemented;echo;echo Uparrow - T nades: Smoke, Molotov, Flash;echo Downarrow - CT nades: Smoke, Molotov, Flash"
alias "binds2" "echo Leftarrow - Next Nade Lineups;echo Rightarrow - Previous Nade Lineups;echo NUM insert	- Secondary Position for Current Lineup;echo;echo;echo INS - places bot at crosshair;echo DEL - kicks all botsecho HOME - makes bot crouch;echo END - bot mimics you;echo PGUP - adds t bot;echo PGDN - adds ct bot;echo;echo;echo HOW TO USE: Crosshair Color Changer;echo 7 - Choose Crosshair Color Preset 1-5;echo"
alias "binds3" "echo 8 - hold to select red, release to save tent to Selected Preset;echo 9 - hold to select blue, release to save tent to Selected Preset;echo 0 - hold to select green, release to save tent to Selected Preset;echo - - darken curret color/tent;echo =	- lighen current color/tent;echo;echo;echo Y - grenade trajectory timers;echo U - the player become invulnerable;echo I - infinite ammo;echo O - see players through walls"
alias "binds4" "echo P - auto bunny hopping;echo [ - shows bullet hits;echo ] - shows impacts;echo \ - draws player/nade, map clippings;echo;echo;echo H - removes airborn grenades;echo J - throws recorded nade, need flashscript www.youtube.com/watch?v=B9hB2gICopw;echo K - gives all grenades;echo L - outlines where bomb can be planted;echo : - draw line/ray;echo ' - stops developer text in upper left corner;echo;echo;echo N - disable particles i.e. smoke"
alias "binds5" "echo M - teleport to logged positions/hold for second position;echo , - log position 1;echo . - log position 2;echo /	- changes viewmodel;echo;echo;echo Tab - toggles Buy anywhere;echo F - inspects weapon and clears blood/bullet holes;echo Capslock - Jump Throw Nade;echo;echo;echo alt - fly/noclip;echo Ralt - increase game speed 10x;echo;echo"

bind "kp_enter" "binds1;binds2;binds3;binds4;binds5"

bind "Rshift" 	"nm"
//bind "Rctrl"	"cmo"

bind "INS"		"bot_place"
bind "DEL"		"bot_kick all"
bind "HOME"		"toggle bot_crouch 1 0"
bind "END"		"toggle bot_mimic 1 0"
bind "PGUP"		"bot_add_t"
bind "PGDN"		"bot_add_ct"

bind "7"		"chcp"
bind "8"		"+chcb"
bind "9"		"+chcg"
bind "0"		"+chcr"
 
bind "Y"		"gtt"
bind "U"		"gods"
bind "I"		"toggle sv_infinite_ammo 1 0"
bind "O"		"toggle r_drawothermodels 2 1"
bind "P"		"toggle sv_autobunnyhopping 1 0;toggle cl_showpos 1 0"
bind "["		"toggle sv_showbullethits 1 0"
bind "]"		"toggle sv_showimpacts 1 0"
bind "\"		"toggle r_drawclipbrushes 0 2"

bind "H" 		"ent_fire smokegrenade_projectile kill;ent_fire flashbang_projectile kill;ent_fire hegrenade_projectile kill;ent_fire decoy_projectile kill"
bind "J"		"thrownade"
bind "K" 		"give weapon_hegrenade;give weapon_flashbang;give weapon_smokegrenade;give weapon_molotov"
bind "L"		"showtriggers_toggle"
bind ";"		"cast_ray"
bind "'"		"toggle developer 1 0"

bind "N"		"toggle r_drawparticles 0 1"
bind "M" 		"+tp"
bind "," 		"con_logfile cfg/tppos.log; getpos_exact; con_logfile 0"
bind "." 		"con_logfile cfg/tppos2.log; getpos; con_logfile 0"
//bind "/"		"nvm"

bind "tab"  	"+showscores; toggle mp_buy_anywhere 1 0"
bind "capslock" "+jumpthrow"
bind "F"		"r_cleardecals;+lookatweapon"

bind "ALT"		"+noclip"
bind "ralt"		"+tso"



say	  "NUM ENTER	 - shows keybindings and clears console _________________________________________________________"
clear
echo  " "
echo  "NUM ENTER	 - shows keybindings and clears console"
echo  " "
echo  " "
echo  "HOW TO USE: Nade Position/Lineup binds"
echo  "Rshift	 - Choose Map, Lineups For Next Maps"
echo  "Rctrl	 - Map optionals /not yet implemented"
echo  " "
echo  "Uparrow		 - T nades: Smoke, Molotov, Flash"
echo  "Downarrow	 - CT nades: Smoke, Molotov, Flash"
echo  "Leftarrow	 - Next Nade Lineups"
echo  "Rightarrow	 - Previous Nade Lineups"
echo  "NUM insert	 - Secondary Position for Current Lineup"
echo  " "
echo  " "
echo  "INS 		 - places bot at crosshair"
echo  "DEL 	 	 - kicks all bots"
echo  "HOME		 - makes bot crouch"
echo  "END 	 	 - bot mimics you"
echo  "PGUP		 - adds t bot"
echo  "PGDN		 - adds ct bot"
echo  " "
echo  " "
echo  "HOW TO USE: Crosshair Color Changer"
echo  "7		 - Choose Crosshair Color Preset 1-5"
echo  " "
echo  "8		 - hold to select red, release to save tent to Selected Preset"
echo  "9		 - hold to select blue, release to save tent to Selected Preset"
echo  "0		 - hold to select green, release to save tent to Selected Preset"
echo  "-		 - darken curret color/tent"
echo  "=		 - lighen current color/tent"
echo  " "
echo  " "
echo  "Y	 	 - grenade trajectory timers"
echo  "U		 - the player become invulnerable"
echo  "I		 - infinite ammo"
echo  "O		 - see players through walls"
echo  "P		 - auto bunny hopping"
echo  "[	 	 - shows bullet hits"
echo  "]		 - shows impacts"
echo  "\		 - draws player/nade, map clippings"
echo  " "
echo  " "
echo  "H		 - removes airborn grenades"
echo  "J		 - throws recorded nade, need flashscript https://www.youtube.com/watch?v=B9hB2gICopw"
echo  "K		 - gives all grenades"
echo  "L		 - outlines where bomb can be planted"
echo  ";	 	 - draw line/ray"
echo  "'		 - stops developer text in upper left corner"
echo  " "
echo  " "
echo  "N		 - disable particles i.e. smoke"
echo  "M 		 - teleport to logged positions/hold for second position"
echo  ",		 - log position 1"
echo  ".		 - log position 2"
echo  "/		 - changes viewmodel"
echo  " "
echo  " "
echo  "Tab		 - toggles Buy anywhere"
echo  "F		 - inspects weapon and clears blood/bullet holes"
echo  "Capslock	 - Jump Throw Nade
echo  " "
echo  " "
echo  "alt		 - fly/noclip"
echo  "Ralt		 - increase game speed 10x"
echo  " "
echo  "________________________________________________________"

	//LIST OF MAYBES
//bind backspace to clear crosshair preset .log file? even possible with console only? or maybe just clear console
//Smoke Z FROm big truck old cache
//extra help button? leads to a how to edit the code video?	 how to use config video?  general tutorial?
//rctrl - jump boost positions, nades to take a/b, callouts, god tier nades, jump bind nades, one way smokes?
//bot that jump, walk, run crouch past/peak set locations on each map?

	//LIST OF TODO'S
//Overpass, nuke, Vertigo, new cache, cobblestone. -in that order-
//optimize, to much code could break cfg when new map linups added.
