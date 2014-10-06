#Projekt Freifunk Ballenstedt


[Link zur OSM Karte](http://osmtools.de/easymap/temp/map1233693250.html)
![Map](https://raw.githubusercontent.com/FreifunkMD/projekte/master/ballenstedt/osm-ballenstedt-richtfunk.jpg)

![Topographische Map](https://raw.githubusercontent.com/FreifunkMD/projekte/master/ballenstedt/ballenstedt-profil.jpg)

##Beschreibung

###Richtfunk

####GPS Koodinaten:

* Schlossturm: 11.217789888329 51.718827012027
* Schloss Ostseite 11,217789888329 51,718827012027 
* Stadtmuseum 11.220883816435 51.719074602436
* Touristinformation 11.234866172029 51.721028691247
* Rathaus 11,241094261358 51,720772803471 
* Marktturm 11.243155538993 51.720699692408
* Obererturm 11.238185405683 51.721188204972

####Entfernungen

Quelle: [bing maps](http://www.mg2.de/map.html)

Ort 1 | Ort 2 | Entfernung [km]
:--- | :--- | :---
Schloss Ostseite (B) | Rathaus (F) | 2,6
Schloss Ostseite (B) | Stadtmuseum (C) |  0,35
Schloss Ostseite (F) | Touristinformation (D)  | 1,91 
Rathaus (F) | Oberer Turm (E) | 0,33 
Rathaus (F) | Markturm (G) | 0,23 

##laufende Kosten 

Für den Betrieb einer eigenen Freifunk Infrastruktur ist eine redundante Auslegung der Backbone-Infrastruktur sinnvoll. Somit funktioniert das Freifunk Netzwerk auch bei dem Ausfall eines Gateways.

### Gatway-Infrastruktur
Name	 | Anzahl | Einzelpreis [€/Monat]| Gesamt [€/Monat]
:---| :--- | :--- | :---
Gateway [z.B. Netcup](https://www.netcup.de/bestellen/produkt.php?produkt=568) | 2 | ca. 20 | ca. 40 
VPN | 2 | 5 | 10
Gesamt | | |  50

###Stromkosten Freifunk Knoten

Name	 | Anzahl | Einzelpreis [€/Monat]| Gesamt [€/Monat]
:---| :--- | :--- | :---
Freifunk Knoten | 32 | 0,5 | 16

## Investitionskosten
###Materialliste

Aufgliederung der benötigten Hardware für den Betrieb von Freifunk an den gewünschten Standorten in Ballenstedt. Nicht berücksichtigt sind die benötigten Materialien für die Erschließung der jeweiligen Standorte mit Strom und Netzwerk.
Netzwerkkabel sollten selbst gecrimpt werden (eigene Auswahl von Kabel, Steckern und Knickschutz möglich).

[Einkaufsliste](http://geizhals.de/eu/?cat=WL-469198) (Freifunk Knoten + Switches) 

Name	 | Anzahl  [-]| Einzelpreis [€] | Gesamt [€]
:---| :--- | :--- | :---
Ubiquiti Nanostation M2 | 22 | 80| 1760
Ubiquiti Nanostation M5| 10| 80| 800
TP-Link WDR4300 | 1 |50 | 50
Bullet M2 HP |1 |70 |70
Antenne TRENDnet TEW-AO12O, 12dBi, 2.4GHz (für Bullet M2)  |1 | 70| 70
Ubiquiti Tough Switch PoE TS-5-POE	 |5 |90 |450
Ubiquiti Tough Switch PoE TS-8-PRO	 | 2 | 150 |300
[Halterung NanoBracket](http://varia-store.com/Zubehoer/Befestigungen/NanoBracket-Universal-Holder-for-NanoStation-other-CPEs::1228.html)|32 |10|  320
LAN Kabel 5M | 30 | 5 | 150 |
LAN Kabel 10M |4 |5 |20
LAN Kabel 50M |1 |20 |20
Summe| | |4010



##Standorte

###A: Schlossturm
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |3 | Abdeckung u.A. Schlosspark, West, Nord-West, Nord-Ost
Halterung NanoBracket | 3 | Infrastruktur
Ubiquiti Tough Switch PoE TS-5-POE	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel Flach 5M | 3 | Infrastruktur
LAN Kabel ca. 50M zum Standort Schloss Ostseite  | 1 | Infrastruktur
###B: Schloss Ostseite (Nordflügel, Ercker)
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |3 | Abdeckung Schlossplatz, Schlosspark
Ubiquiti Nanostation M5 |3 | Richtfunk zum Rathausturm <br>Richtfunk zum Museum<br> Richtfunk zur Touristinformation
Halterung NanoBracket | 6 | Infrastruktur
Ubiquiti Tough Switch PoE TS-8-PRO	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel 5M | 6 | Infrastruktur

###C: Stadtmuseum
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |3 | Abdeckung Schlossplatz, Schlosspark
Ubiquiti Nanostation M5 |1 | Richtfunk zum Richtfunk zum Schloss (Ostseite)
Halterung NanoBracket | 4 | Infrastruktur
Ubiquiti Tough Switch PoE TS-5-POE	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel 5M | 5 | Infrastruktur
LAN Kabel 10M |2 | Infrastruktur

###D: Touristinformation
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |2 | Abdeckung Allee, Füßgängerzone
Ubiquiti Nanostation M5 |1 | Richtfunk zum Richtfunk zum Schloss (Ostseite)
Ubiquiti Bullet M2 HP |1 | Abdeckung Anhalter Platz
Antenne TRENDnet TEW-AO12O, 12dBi, 2.4GHz   |1 | Rundstrahlantenne für Bullet M2
Halterung NanoBracket | 3 | Infrastruktur
Ubiquiti Tough Switch PoE TS-5-POE	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel 5M | 6 | Infrastruktur

###E: Oberer Turm
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |4 | Abdeckung Platz vor Oberer Turm
Ubiquiti Nanostation M5 |1 | Richtfunk zum Rathausturm
Halterung NanoBracket | 5 | Infrastruktur
Ubiquiti Tough Switch PoE TS-5-POE	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel 5M | 5 | Infrastruktur

###F: Rathausturm
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |3 | Abdeckung Rathausvorplatz, West, Süd, Ost
Ubiquiti Nanostation M5 |3 | Richtfunk zum Schloss (Ostseite)<br> Richtfunk zum Oberer Turm <br>Richtfunk zum Markturm
Halterung NanoBracket | 6 | Infrastruktur
Ubiquiti Tough Switch PoE TS-8-PRO	 | 1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel 5M | 6 | Infrastruktur
LAN Kabel 10M | 2 | Infrastruktur

###G: Markturm
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |4 | Abdeckung Platz vor Marktturm
Ubiquiti Nanostation M5 |1 | Richtfunk zum Rathausturm
Halterung NanoBracket | 5 | Infrastruktur
Ubiquiti Tough Switch PoE TS-5-POE	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel 5M | 5 | Infrastruktur

###H: Bibliothek
Name | Anzahl | Zweck
:---|:---|:--
TP-Link WDR4300 | 1 | Abdeckung Innenbereich


##Netzwerk Management
* V-LAN1: mesh vlan (2,4 GHz)
* V-LAN2: Richtfunk vlan (5 GHz)

### Kabel
Netzwerkkabel werden selbst gecrimpt.

Name | Anzahl | Zweck
:---|:---|:--
[RJ45-Stecker MP8(8) FS Cat.6A](http://www.telegaertner.com/de/info/katalog/datavoice/?IdTreeGroup=14254&IdProduct=9881) | 70 | Netzwerk
[Knickschutztüllen](http://www.telegaertner.com/de/info/katalog/datavoice/?IdTreeGroup=13964) | 6 blau<br> 44 gelb<br>6 grau<br>6 grün <br>6 rot <br>6 schwarz | Netzwerk
[LAN Kabel](http://www.highpatch.de/downloads/patchkabel/Draka-U-FTP-Cat6-UC400-S27.pdf) | 240m | Netzwerk, -20°C bis + 60°C

Name | Anzahl | Gesamtlänge
:---|:---|:--
LAN Kabel 5M | 30 | 150
LAN Kabel 10M |4 | 20
LAN Kabel 50M |1 |50
