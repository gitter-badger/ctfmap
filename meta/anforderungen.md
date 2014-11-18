# Client
##Anforderungen - Leistungen
### Anzeige
- Spiel in Vorbereitung, Spiel begonnen, Spiel zuende
- Spiel�bersicht
	- Infos zu Flaggen und Spielern beider Teams
  - Ist der Spieler frei(offensiv/defensiv) / gefangen / mit Flagge unterwegs / disconnected
	- Steht die Flagge, ist sie gerade gestohlen oder sogar schon verloren?
- Karte
	- Positionen von Spielern und Flaggen (nur eigenes Team, gefangene Gegner, gestohlene&gesichtete Flaggen)
	- Die letzten x Meter, die ein Spieler gelaufen ist als Spur anzeigen
	- Durch Icons Spielerstatus anzeigen
	  - Frei, Gefangen, Mit Flagge, Disconnected
	- Strategische Markierungen
### Eingabe
- Spielerstatus �ndern (Frei, Gefangen, Mit/ohne Flagge)
- Strategische Markierungen
  - Gegner/Flagge hier gesehen
	- Linien ziehen/malen -> Multipurpose
#### Eingabemethoden
- Button - davon m�glichst wenige, da sie den Kartenausschnitt verkleinern
- Ringmen�, durch Touch aktivierbar
	
## Anforderungen - Hardware/Software
- Smartphone, Tablet, Smartwatch, Smartglasses
- Als WebApp auf diversen Ger�ten nutzbar
- HTML5 Browser, GPS, Touchdisplay, Internetverbindung



# Server
## Anforderungen - Leistungen
- Sammeln und speichern der Daten von den Clients
- Verteilen der entsprechenden Daten an Clients
### Visuell
- �bersicht �ber Spielverlauf, Statistiken
## Hard/Software
- Datenbank, PHP/Python Interpreter, ...

#Skizzen
Die Anzeige des Clients k�nnte (ohne Eingabebuttons) etwa so aussehen:
![](ctfmap_skizze.png)
Ringmen� Bsp.
![Ringmen�](ringmenu.jpg "http://technikfaultier.com/wp-content/uploads/2013/06/Android-4.3-Kamera-App.jpg")