#ctfmap - Spielablauf von Capture The Flag und Schrittweises Umsetzung in ctfmap
Hier wird grob das Spielprinzip erläutert um dann auf Ablauf und Aktionen mit ctfmap einzugehen.

##Spielprinzip
Das Spielgelände ist ein zweigeteiltes Gebiet. Zwei Teams spielen gegeneinander,
jedem gehört je ein Teil. Zu Beginn verstecken sie ihre Flaggen in ihrem Teil.
Nun geht es darum, die feindlichen Flaggen zu erobern: Finden und über die Grenze bringen.
Dabei können die Spieler im eigenen Teil feindliche Spieler fangen - bzw. im anderen Teil gefangen/befreit werden.
Gefangene verbleiben an Ort und Stelle ohne bis zur Befreiung Informationen weiterzugeben.

##Spielablauf
- Matchmaking
- Vorbereitungen
- Das Spiel selber beginnt (Rundum-Mitteilung)

##Matchmaking
- Spiel durch Spielleiter erstellen
- Durch Spieler:
	1. Auswahl des Spiels
	2. Auswahl des Teams (oder Zuschauer)
- Start des Spiels durch Spielleiter

##Vorbereitungen
- Flaggen verstecken und per GPS eintragen

##Spiel selber
- Spieler suchen die versteckten Flaggen
- Spieler können im feindlichen Gebiet gefangen werden
	- Markieren sich als gefangen
	- Bleiben an Ort und Stelle
	- Warten auf Befreiung
		- Befreit ... Markieren als frei
- Spieler können die Flagge finden
	- Flaggenmarker als Hinweis für andere setzen
	- Flagge als aufgenommen markieren
		- Flagge als abgelegt markieren, wenn man sie irgendwo lässt
		- Flagge als erobert markieren, wenn man das eigene Gebiet erreicht (automatisch/gps ?)
- Spieler können andere Spieler im eigenen Gebiet fangen
	- Der gefangen Spieler hat darauf durch entsprechendes Event zu reagieren
