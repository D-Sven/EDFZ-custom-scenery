# EDFZ-custom-scenery
Mainz-Finthen is a beautiful airfield located near Frankfurt, Germany!

Runway usuage:
08/26: Departing and landing runway for motorised planes.
08R/26L grass: Used for glider operations and UltraLight-practice.
Traffic patterns are flown south of the airport:
        From 08: Right turns
        From 26: Left turns
        Altitude: 1700ft Above Sea Level - 1500ft MSL for Ultralight
        In your route-manager, you will find the traffic pattern by selecting SID "pattern"

Airspace structure:
Airspace C (Frankfurt) borders at 3500ft MSL. Airspace D(HX) Wiesbaden borders about ~1nm east of the field.
Clearance by ATC mandatory for entry!
(which FG pilots usually have, don't we ? :D)

This custom scenery contains: 
            a complete new groundnet of the field
            shared models, the original tower building and hangars
            multiple parking positions
            osm-2-city-buildings for the city of Mainz (Installation described below)
            For gliders: AI-Towplane-scenario from 26L + AI-thermals for crosscountry-flights

INSTALLATION: Add the folder /EDFZ-custom-scenery/ and /EDFZ-custom-scenery/osm2city/ (optional)
to your Add-ons "additional scenery folders" in FlightGear's new launcher;
or add the following when starting FG via commandline:

 --fg-scenery=/YOUR_SCENERY_PATH/EDFZ-custom-scenery            --> Main scenery
 --fg-scenery=/YOUR_SCENERY_PATH/EDFZ-custom-scenery/osm2city   --> osm2city-buildings (optional)

YOUR_SCENERY_PATH can just be a random directory where you extracted the downloaded scenery!

NOTICE: osm2city may decrease framerate... If this is the case, remove the /osm2city folder from FG_SCENERY (prefered) or delete it.

INSTALLATION OF AI TOWPLANE:
Go to /AI/AI_towplane and copy the /AI folder into your $FGROOT directory.
It contains the towplane (/Aircraft/c177), the FlightPlan for the tow (/FlightPans/EDFZ_towing26.xml) and the main XML (EDFZ-Mainz_towing.xml).
All the files must be copied or moved to the proper directories in your $FGROOT (Linux: /usr/share/games/flightgear/)!
Find more information and documentation in /DOCU/Aerotow-tutorial-en.pdf 

INSTALLATION OF AI THERMALS:
Go to /AI/AI_thermals and copy the /AI folder into your $FGROOT directory.
It contains the thermal clouds (/Models/Geometry) and the thermal positions (/AI/EDFZ_thermals.xml), which you may want to change.
All the files must be copied or moved to the proper directories in your $FGROOT (Linux: /usr/share/games/flightgear/)!
Find more information and documentation in /DOCU/Thermaling-tutorial-en.pdf 

See the corresponding discussion in the official flightgear forum: 
https://forum.flightgear.org/viewtopic.php?f=5&t=30349


Credits:    Many thanks to D-ECHO for modelling an awesome realistic tower building and some hangar buildings!
            Thanks to D-3-m and D-ABBA for their exellent critics and useful suggestions!
            Thanks to d-laser for turning the poor generic taxiway structure in a gorgeous layout like in RL!
            Thanks to Herbert Wagner (alias HerbyW) for improving the towplane action!
            

GERMAN README:

Mainz-Finthen EDFZ ist ein wunderschöner Verkehrslandeplatz nahe Frankfurt am Main.

Die zwei Pisten werden wie folgt genutzt:
        08/26: Start- und Landebahn für motorisierte Luftfahrzeuge.
        08R/26L grass: Hauptsächlich Segelflug(schulung) und vereinzelt Ultraleichtbetrieb.
        Die Platzrunde liegt im Süden des Platzes:
                Von 08 gesehen: Rechtskurven
                Von 26 gesehen: Linkskurven
                Platzrundenhöhe: 1700ft über Meereshöhe - UL: 1500ft MSL
        Im Route-Manager steht die Platzrunde für alle Pisten als SID "pattern" zu Verfügung

Luftraumstruktur:
        Achtung: Über dem gesamten Gebiet des Flugplatzes liegt ein Luftraum der Klasse C in 3500ft MSL. 
        Hier darf nur mit besonderer CVFR-Freigabe eingeflogen werden!
        Unmittelbar im Osten des Platzes liegt die Kontrollzone Wiesbaden (GND - 1500ft MSL). Einflug nur nach Genehmigung!
        (Allerdings haben wir FG-Piloten diese grundsätzlich, oder?)

Dieses Szenerie-Paket enthält: 
            alle Pisten/Rollwege/Abstellplätze
            neue Tower/Hangars/Lampen/Flugzeuge/Bäume und vieles mehr
            auswählbare Parkpositionen
            osm2city-Gebäude/Straßen/Brücken
            eine vorgefertigte Route der Platzrunde zum Üben
            Für Segelflieger: Ein F-Schlepp-Szenario von der 26L
            + Thermik-Szenarien für einfache Streckensegelflüge!

INSTALLATION: Fügt einfach die Ordner /EDFZ-custom-scenery und /EDFZ-custom-scenery/osm2city (optional) zu euerer
Add-ons-Liste im Launcher oder in der Konsole:


 --fg-scenery=/YOUR_SCENERY_PATH/EDFZ-custom-scenery    --fg-scenery=/YOUR_SCENERY_PATH/EDFZ-custom-scenery/osm2city
                        =                                                           =
                Flugplatz Mainz Finthen                                 osm2city Gebäude (optional)

YOUR_SCENERY_PATH ist hier der Pfad vom Hauptverzeichnis zum Download

NOTIZ: osm2city kann wegen der vielen Objecte Einfluss auf die Framerate haben. Falls euch das nicht gefällt könnt ihr den osm2city Ordner rausschmeißen oder evtl. löschen!

INSTALLATION DES F-SCHLEPP-SZENARIOS:

Kopiere einfach den Ordner /AI/ in AI/AI_towplane/ in dein $FGROOT-Verzeichnis. (Linux: /usr/share/games/flightgear/)
Es enthält das Schleppflugzeug (/Aircraft/c177), den sog. Flugplan des Szenarios (/FlightPans/EDFZ_towing26.xml) und die Haupt-xml (EDFZ-Mainz_towing.xml).
All diese Dateien müssen in den richtigen Verzeichnissen sein, damit das Szenario funktioniert!
Eine ausführliche Dokumentation zum F-Schlepp in FlightGear findest du in /DOCU/F-Schlepp-Anleitung-de.pdf

INSTALLATION DES THERMIK-SZENARIOS:

Kopiere einfach den AI-Ordner AI/AI_thermals/ in dein $FGROOT-Verzeichnis. (Linux: /usr/share/games/flightgear/)
Es enthält die passende Wolke (/Models/Geometry) und die .xml mit den Positionen der Wolken.
All diese Dateien müssen in den richtigen Verzeichnissen sein, damit das Szenario funktioniert!
Eine ausführliche Dokumentation zum Thermikflug in FlightGear findest du in /DOCU/Thermik-Anleitung-de.pdf

Hier der Link zum Forumeintrag:
https://forum.flightgear.org/viewtopic.php?f=5&t=30349


Danksagungen:   Vielen Dank an D-ECHO für den Tower und einige Hangars!
                Danke 3-m und D-ABBA für eure Kritik am Projekt.
                Danke an d-laser für das neue Groundnet. Sieht super aus!
                Danke Herby (alias HerbyW) für deine Arbeit an dem F-Schlepp-Szenario!
