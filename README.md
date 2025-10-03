# TAKathon 2025

## Intro

TBD


## Rekommenderade enheter

All utveckling av plug-ins och liknande skall ske mot Android-baserade telefoner. 
_For small phone-sized devices, hardware equivalent to a Samsung S5 or newer is required. For tablet-sized devices, the Samsung Tab S or newer is recommended. To ensure an optimal experience, it’s advised to use at least Samsung S9-equivalent hardware or newer for phones, and a Samsung Tab S2 or newer for tablets._

### TAK-server
Vid behov kan en docker image tillhandahållas, alternativt skapas själv. TAK.gov tillhandahåller ett beta-verktyg för att skapa developer docker images : https://tak.gov/tak_server_configurator/container_operating_system



## Community
https://www.reddit.com/r/ATAK/wiki/index/  


## Plugin utveckling

https://www.civtak.org/2024/12/04/atak-plugin-development-tutorial/. 
> Part 1 https://www.youtube.com/watch?v=3qSsMcYXrvI  
Part 2 https://www.youtube.com/watch?v=LgzLesTKWcc

https://www.riis.com/blog/atak-plugins-part-1  
https://www.riis.com/blog/plugins-with-atak-civ-sdk-5-5  


### Plugins (docs & samples)

https://github.com/Toyon/LearnATAK

## Datakällor 

### Weather

https://opendatadocs.dmi.govcloud.dk/DMIOpenData


### Comms
https://github.com/meshtastic/pluginmeshtastic

### Map & topography 
* Elevation data : https://github.com/ollighost/DTED-LVL2-4-TAK
* Sverige/Norge/Finland : https://mega.nz/file/2aQzGaCZ#s4z0fhLXmSiaDUwoPISGkfWIQ2AY4G1upsgMAro2QL0
* Topo maps (Finland) : https://www.gofferje.net/it-stuff/set-up-offline-mapserver/
* Collection : https://github.com/joshuafuller/ATAK-Maps


### Conflict map (Ukraine)
* https://deepstatemap.live/#6/49.4383200/32.0526800
* API : https://deepstatemap.live/api/history/last

### Airplane data
* https://globe.airplanes.live
* https://github.com/ADSB-One/api/blob/main/README.md
* ADSB-ID mapping https://github.com/sgofferj/TAK-ADSB-ID


## Server feeders 

A feeder pulls data, converts the current events to CoT messages and sends them to a TAK server. ATAK, WinTAK and WebTAK will show the events with icons corresponding to the type of event and the severity (WinTAK doesn't show the color, though).


* Ukraine  https://github.com/sgofferj/tak-feeder-deepstate  (server feeder)
* Global disaster data (GDACS) : https://github.com/sgofferj/tak-feeder-gdacs (server feeder)
* Finnish weather https://github.com/sgofferj/tak-feeder-weather-fmi (server feeder)

## Övrigt

* Garmin watch integration : https://github.com/TDF-PL/TAKWatch/
* Traffic cameras : https://github.com/ScriptTactics/ATAK-CoT-Converters


