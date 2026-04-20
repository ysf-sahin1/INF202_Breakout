# Anforderungsanalyse: Storm Breakout

In der ersten Projektwoche haben wir als Gruppe überlegt was unser Spiel
können soll. Hier sind die Anforderungen die wir gesammelt haben:

### Funktionale Anforderungen

* **F01 (Paddle Steuerung):** Der Spieler soll das Paddle mit den Pfeiltasten
  oder A/D Tasten nach links und rechts bewegen können.
* **F02 (Ball):** Der Ball soll realistisch abprallen, also Einfallswinkel
  gleich Ausfallswinkel. Er prallt an Wänden und am Paddle ab.
* **F03 (Blöcke & Punkte):** Wenn der Ball einen Block trifft wird der Block
  zerstört und der Spieler kriegt Punkte dafür.
* **F04 (Leben System):** Der Spieler startet mit 3 Leben. Fällt der Ball
  unten raus verliert er ein Leben. Bei 0 Leben ist das Spiel vorbei.
* **F05 (Gewinn Bedingung):** Wenn alle Blöcke zerstört sind hat der Spieler
  gewonnen und bekommt eine Gewinn-Nachricht angezeigt.

### Nicht-Funktionale Anforderungen

* **NF01 (Performance):** Das Spiel soll ohne Ruckler laufen, also möglichst
  60 FPS halten.
* **NF02 (Code Qualität):** Der Code soll sauber strukturiert sein damit
  alle im Team gut damit arbeiten können. Wir wollen Coding Conventions
  einhalten die wir in der Vorlesung gelernt haben.
* **NF03 (Einfache Bedienung):** Das Spiel soll ohne große Erklärung
  verständlich sein.