# EDFZ-custom-scenery
Mainz Finthen is a rather busy airfield located in south-western Germany. 

08/26: Departing and landing runway for motorised planes.
08R/26L grass: Used for glider operations and UL-practice (UltraLight).
Traffic patterns are flown south of the airport. Means:
        From 08: Left turns
        From 26: Right turns
        Altitude: 1500ft - max. 3000ft MSL
Airspace C borders at 3500ft MSL, be sure to not enter it.
~2 nm to the east of the field airspace D begins (GND - 1500ft) and a C (1500ft - FL100). Try to stay out of there unless you obtain a clearance from DFS.
(which FG pilots usually have, don't we ? :D)

This custom scenery contains: 
            a complete new groundnet of the field
            shared models and the original tower building and hangars
            multiple parking positions
            osm-2-city-buildings for the city of Mainz (Installation described below)
            coming up soon: a fgfp and procedure for traffic pattern and to nearby airports
            

INSTALLATION: Add the folder /EDFZ-custom-scenery/osm2city/ and /EDFZ-custom-scenery to your FG_SCENERY (very first page of FG-Wizard launcher) 
or add the following when starting FG via commandline:

 --fg-scenery=/YOUR_SCENERY_PATH/EDFZ-custom-scenery   /YOUR_SCENERY_PATH/EDFZ-custom-scenery/osm2city
                                        =                                       =
                                Mainz Finthen Airport               osm2city buildings (optional)
YOUR_SCENERY_PATH can just be a random directory where you extracted the downloaded scenery!

NOTICE: osm2city may decreases framerate... If this is the case, remove the /osm2city folder from FG_SCENERY (prefered) or delete it.

INSTALLATION OF AI TOWPLANE (new):

Go to /AI/AI_towplane and copy the /AI folder into your $FGROOT directory.
It contains the towplane (/Aircraft/c177), the FlightPlan for the tow (/FlightPans/EDFZ_towing26.xml) and the main XML (EDFZ-Mainz_towing.xml).
All the files must be copied or moved to the proper directories in your $FGROOT (Linux: /usr/share/games/flightgear/)!
For the final tow see the documentation in /AI...        Have fun!

See the corresponding discussion in the official flightgear forum: 
https://forum.flightgear.org/viewtopic.php?f=5&t=30349


Credits:    Many thanks to D-ECHO for modelling an awesome realistic tower building and some hangar buildings!
            Thanks to D-3-m for his exellent critics and his useful suggestions!
            Thanks to d-laser for turning the poor generic taxiway structure in a gorgeous layout like in RL!
            Thanks to Herbert Wagner (alias HerbyW) for improving the towplane action and improving the c177 for it!
            
