# EDFZ-custom-scenery
Mainz Finthen is a busy airfield located in south-western Germany. 

08/26: Departing and landing runway for motorised planes.
08R/26L grass: Used for glider operations and UltraLight-practice.
Traffic patterns are flown south of the airport. Means:
        From 08: Right turns
        From 26: Left turns
        Altitude: 1700ft Above Sea Level - 1500ft MSL for Ultralight

Airspace structure:
Airspace C (Frankfurt) borders at 3500ft MSL. Airspace D(HX) Wiesbaden borders about ~1nm east of the field.
Clearance by ATC necessary!
(which FG pilots usually have, don't we ? :D)

This custom scenery contains: 
            a complete new groundnet of the field
            shared models, the original tower building and hangars
            multiple parking positions
            osm-2-city-buildings for the city of Mainz (Installation described below)
            For gliders: AI-Towplane-scenario from 26L + AI-thermals for crosscountry-flights

INSTALLATION: Add the folder /EDFZ-custom-scenery/osm2city/ (optional) and /EDFZ-custom-scenery/ to your FG_SCENERY 
or add the following when starting FG via commandline:

 --fg-scenery=/YOUR_SCENERY_PATH/EDFZ-custom-scenery            --> Main scenery
 --fg-scenery=/YOUR_SCENERY_PATH/EDFZ-custom-scenery/osm2city   --> osm2city-buildings (optional)

YOUR_SCENERY_PATH can just be a random directory where you extracted the downloaded scenery!

NOTICE: osm2city may decrease framerate... If this is the case, remove the /osm2city folder from FG_SCENERY (prefered) or delete it.

INSTALLATION OF AI TOWPLANE:

Go to /AI/AI_towplane and copy the /AI folder into your $FGROOT directory.
It contains the towplane (/Aircraft/c177), the FlightPlan for the tow (/FlightPans/EDFZ_towing26.xml) and the main XML (EDFZ-Mainz_towing.xml).
All the files must be copied or moved to the proper directories in your $FGROOT (Linux: /usr/share/games/flightgear/)!

INSTALLATION OF AI THERMALS:

Go to /AI/AI_thermals and copy the /AI folder into your $FGROOT directory.
It contains the thermal clouds (/Models/Geometry) and the thermal positions (/AI/EDFZ_thermals.xml), which you may want to change.
All the files must be copied or moved to the proper directories in your $FGROOT (Linux: /usr/share/games/flightgear/)!

See the corresponding discussion in the official flightgear forum: 
https://forum.flightgear.org/viewtopic.php?f=5&t=30349


Credits:    Many thanks to D-ECHO for modelling an awesome realistic tower building and some hangar buildings!
            Thanks to D-3-m for his exellent critics and his useful suggestions!
            Thanks to d-laser for turning the poor generic taxiway structure in a gorgeous layout like in RL!
            Thanks to Herbert Wagner (alias HerbyW) for improving the towplane action and improving the c177 for it!
