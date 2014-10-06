#Projekt Freifunk Ballenstedt
#Karte
[Link zur OSM Karte](http://osmtools.de/easymap/temp/map1233693250.html)
![Map](https://raw.githubusercontent.com/FreifunkMD/projekte/master/ballenstedt/easymap_2014-10-06.png)

![Topographische Map](https://raw.githubusercontent.com/FreifunkMD/projekte/master/ballenstedt/ballenstedt-profil.jpg)
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

[Einkaufsliste](http://geizhals.de/eu/?cat=WL-469198) (Freifunk Knoten + Switches) 

Name	 | Anzahl  [-]| Einzelpreis [€] | Gesamt [€]
:---| :--- | :--- | :---
Ubiquiti Nanostation M2 | 22 | 80| 1760
Ubiquiti Nanostation M5| 8| 80| 640
TP-Link WDR4300 | 1 |50 | 50
Bullet M2 HP |1 |70 |70
Antenne TRENDnet TEW-AO12O, 12dBi, 2.4GHz (für Bullet M2)  |1 | 70| 70
Ubiquiti Tough Switch PoE TS-5-POE	 |5 |90 |450
Ubiquiti Tough Switch PoE TS-8-PRO	 | 2 | 150 |300
[Halterung Ubiquiti Ubibracket](https://shop.omg.de/ubiquiti-networks/nanobracket/ubiquiti-ubibracket-universal-justierbares-bracket-fuer-wand-und-mast/a-7348/)|30 |10|  300
LAN Kabel Flach 5M | 28 | 5 | 140 |
LAN Kabel Flach 10M |4 |5 |20
LAN Kabel 50M |1 |20 |20
Summe| | |3820



##Standorte

###A: Schlossturm
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |3 | Abdeckung u.A. Schlosspark, West, Nord-West, Nord-Ost
Halterung Ubiquiti Ubibracket | 3 | Infrastruktur
Ubiquiti Tough Switch PoE TS-5-POE	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel Flach 5M | 3 | Infrastruktur
LAN Kabel ca. 50M zum Standort Schloss Ostseite  | 1 | Infrastruktur
###B: Schloss Ostseite (Nordflügel, Ercker)
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |3 | Abdeckung Schlossplatz, Schlosspark
Ubiquiti Nanostation M5 |2 | Richtfunk zum Rathausturm <br>Richtfunk zum Museum
Halterung Ubiquiti Ubibracket | 5 | Infrastruktur
Ubiquiti Tough Switch PoE TS-8-PRO	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel Flach 5M | 5 | Infrastruktur

###C: Stadtmuseum
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |3 | Abdeckung Schlossplatz, Schlosspark
Ubiquiti Nanostation M5 |1 | Richtfunk zum Richtfunk zum Schloss (Ostseite)
Halterung Ubiquiti Ubibracket | 4 | Infrastruktur
Ubiquiti Tough Switch PoE TS-5-POE	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel Flach 5M | 5 | Infrastruktur
LAN Kabel Flach 10M |2 | Infrastruktur

###D: Touristinformation
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |2 | Abdeckung Allee, Füßgängerzone
Ubiquiti Bullet M2 HP |1 | Abdeckung Anhalter Platz
Antenne TRENDnet TEW-AO12O, 12dBi, 2.4GHz   |1 | Rundstrahlantenne für Bullet M2
Halterung Ubiquiti Ubibracket | 2 | Infrastruktur
Ubiquiti Tough Switch PoE TS-5-POE	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel Flach 5M | 5 | Infrastruktur

###E: Oberer Turm
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |4 | Abdeckung Platz vor Oberer Turm
Ubiquiti Nanostation M5 |1 | Richtfunk zum Rathausturm
Halterung Ubiquiti Ubibracket | 5 | Infrastruktur
Ubiquiti Tough Switch PoE TS-5-POE	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel Flach 5M | 5 | Infrastruktur

###F: Rathausturm
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |3 | Abdeckung Rathausvorplatz, West, Süd, Ost
Ubiquiti Nanostation M5 |3 | Richtfunk zum Schloss (Ostseite)<br> Richtfunk zum Oberer Turm <br>Richtfunk zum Markturm
Halterung Ubiquiti Ubibracket | 6 | Infrastruktur
Ubiquiti Tough Switch PoE TS-8-PRO	 | 1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel Flach 5M | 6 | Infrastruktur
LAN Kabel Flach 10M | 2 | Infrastruktur

###G: Markturm
Name | Anzahl | Zweck
:---|:---|:--
Ubiquiti Nanostation M2 |4 | Abdeckung Platz vor Marktturm
Ubiquiti Nanostation M5 |1 | Richtfunk zum Rathausturm
Halterung Ubiquiti Ubibracket | 5 | Infrastruktur
Ubiquiti Tough Switch PoE TS-5-POE	 |1 | Stromversorgung, Backbone Infrastruktur
LAN Kabel Flach 5M | 5 | Infrastruktur

###H: Bibliothek
Name | Anzahl | Zweck
:---|:---|:--
TP-Link WDR4300 | 1 | Abdeckung Innenbereich