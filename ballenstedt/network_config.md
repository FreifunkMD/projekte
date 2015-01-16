#Network Configuration
## VLAN
* VLAN23: Management
* VLAN24: Richtfunk 5GHz
* VLAN25: Freifunk 2.4GHz

## IP Range
###Switches:

IP-Adresse | Hostname | Standort  | Modell | Ports | Bemerkung
:---|:---| :--- | :--- | :--- | :---
172.16.100.10 | Switch01 | Schlossturm |Tough Switch PoE TS-5-POE | Port 1: Uplink <br> Port 2: wdr3600 | am wdr3600 sind 2x NSM2
172.16.100.11 | Switch02 | Schloss |Tough Switch PoE TS-8-POE | Port 1: Uplink<br> Port 2: NSM5 <br>Port 3: NSM5<br>Port 4: NSM5<br> Port 8: wdr3600 | am wdr3600 sind 3x NSM2
172.16.100.12 | Switch03 | Stadtmuseum |Tough Switch PoE TS-5-POE | Port 2: NSM5 <br>Port 5: wdr3600 | am wdr3600 sind 3x NSM2
172.16.100.13 | Switch04 | Touristinformation |Tough Switch PoE TS-5-POE | Port 1: Uplink <br>Port 2: NSM5 <br>Port 5: wdr3600 | am wdr3600 sind 1x NSM2 und 1x Bullet M2
172.16.100.14 | Switch05 | Rathaus |Tough Switch PoE TS-8-POE | Port 1: Uplink<br> Port 2: NSM5 <br>Port 3: NSM5<br>Port 4: NSM5<br> Port 8: wdr3600 | am wdr3600 sind 3x NSM2
172.16.100.15 | Switch06 | Obererturm |Tough Switch PoE TS-5-POE | Port 2: NSM5 <br>Port 5: wdr3600 | am wdr3600 sind 4x NSM2
172.16.100.16 | Switch07 | Marktturm |Tough Switch PoE TS-5-POE | Port 2: NSM5 <br>Port 5: wdr3600 | am wdr3600 sind 4x NSM2



###Nanostation M5:

IP-Adresse | Hostname | Ziel-Hostname |  Standort  | Modus | Bemerkung
:---|:---| :--- | :--- | :--- | :---
172.16.100.50 |Schloss1 |  Rathaus1 | Schloss Ost | AP
172.16.100.51 | Rathaus1 | Schloss1| Rathaus |  Client
172.16.100.52 | Schloss2 | Stadtmuseum1 | Schloss Ost | AP
172.16.100.53 | Stadtmuseum1 | Schloss2 | Stadtmuseum | Client
172.16.100.54 | Schloss3 | Touristinformation1 | Schlossturm Ost | AP
172.16.100.55 | Touristinformation1 | Schloss3 | Touristinformation | Client
172.16.100.56 | Rathaus2 | Oberer_Turm1| Rathaus |  AP
172.16.100.57 | Oberer_Turm1 | Rathaus 2 | Oberer Turm |  Client
172.16.100.58 | Rathaus3 | Markturm1| Rathaus |  AP
172.16.100.59 | Markturm1 | Rathaus3| Markturm |  Client



