# Bierpong-Turnier 🍻

**Live:** https://sofiixi.github.io/bierpong/

Turnierverwaltung für Bierpong-Turniere.
Eine einzige HTML-Datei, läuft offline im Browser – ohne Account, ohne Server.

## Funktionen

- **Teams:** ein Team pro Zeile eintragen, Gruppen automatisch auslosen
- **Gruppenphase:** jeder gegen jeden, getroffene Becher pro Team eintragen, Tabelle rechnet live
  (Sieg 3 Punkte, Gleichstand nach Zeit 1 Punkt, danach Becherdifferenz)
- **K.-o.-Runde:** Turnierbaum aus den Gruppenbesten, Freilose bei ungerader Anzahl, Nachwurf bei Gleichstand
- **Beamer-Anzeige:** großer Rundentimer (Standard 10 Min), grünes „Los geht's“ beim Start,
  rotes Blinken bei Timeout, optional mit Ton

## Benutzung

1. `index.html` im Browser öffnen (Chrome oder Edge empfohlen, nicht im Inkognito-Modus).
2. Beamer als **erweiterten** Bildschirm anschließen und die Datei in zwei Fenstern öffnen:
   - Fenster 1 → „Beamer-Anzeige ▶“, auf den Beamer ziehen, Vollbild + Ton aktivieren
   - Fenster 2 → Steuerung: Ergebnisse eintragen, Timer starten
3. Beide Fenster gleichen sich automatisch ab. Der Stand wird im Browser gespeichert.

Hinweis: Beide Fenster müssen auf demselben Gerät im selben Browser laufen.
