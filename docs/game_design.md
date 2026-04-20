# Game Design: Storm Breakout

## Spielidee

Ein klassisches Breakout Spiel bei dem der Spieler mit einem Paddle
einen Ball steuert um Blöcke zu zerstören. Wir wollen das Grundprinzip
von Breakout umsetzen und nach und nach erweitern.

## Spielmechaniken

**Paddle**
- Bewegt sich horizontal am unteren Bildschirmrand
- Steuerung über Pfeiltasten oder A/D
- Prallt den Ball in die entsprechende Richtung ab

**Ball**
- Startet von der Mitte des Paddles
- Einfallswinkel = Ausfallswinkel beim Abprallen
- Wenn der Ball unten rausfällt verliert der Spieler ein Leben

**Blöcke**
- Am oberen Bereich des Spielfelds angeordnet
- Werden beim Treffer zerstört und geben Punkte
- Verschiedene Farben möglich (verschiedene Punkte)

**Leben**
- Spieler startet mit 3 Leben
- Bei 0 Leben: Game Over Bildschirm

**Punkte**
- Für jeden zerstörten Block gibt es Punkte
- Punktestand wird oben angezeigt

## Spielzustände

- Main Menu → Spieler drückt Start
- In Game → Spieler spielt
- Pause → Spieler drückt Pause
- Game Over → alle Leben verloren
- Win → alle Blöcke zerstört

Siehe activity_diagram.svg für den genauen Spielablauf.

## Technisches

- Framework: libGDX
- Sprache: Java
- Plattform: Desktop (lwjgl3)
- Ziel FPS: 60

## Offene Fragen

- Wie viele Blockreihen soll es geben?
- Soll die Ballgeschwindigkeit mit der Zeit zunehmen?
- Wollen wir Power-Ups einbauen?
