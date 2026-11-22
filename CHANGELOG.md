# Changelog

## Version 2.7 – 22.11.2026
- Neu: 📺-Knopf unten links «Auf Bildschirm senden». «Cast-Bildschirm wählen» (Chrome mit Chromecast / Cast-fähigem Gerät) oder «Als Fenster öffnen» (für zweiten Bildschirm, z. B. Mac/Apple TV als Zusatzbildschirm, Samsung DeX). Umschalter «Getrennt» (Bildschirm zeigt die Beamer-Ansicht: Gruppen, Timer, gezogene Person) und «Gleich» (dasselbe wie du)

## Version 2.6 – 22.11.2026
- Neu: Gruppen mit Regeln. «Nicht zusammen» pro Klasse; die App versucht bis zu 400 Einteilungen und meldet, wenn eine Regel nicht erfüllbar ist
- Neu: Rollen in Gruppen (Standard: Moderation, Zeit, Schreiben, Präsentation; Liste änderbar), zufällig pro Gruppe verteilt
- Neu: Gruppen speichern und später laden (bis 20 pro Klasse, mit der Klasse gesichert)
- Neu: Gruppen als Bild (PNG) speichern oder drucken / als PDF
- Neu: Beamer-Ansicht in grosser Schrift (Gruppen und Timer), schliesst mit ✕, Esc oder Zurück-Geste
- Neu: Reiter «Würfel · Münze · Timer» (1–3 Würfel, W10, W20, Münze, Timer mit Signalton)

## Version 2.5 – 21.11.2026
- Neu: Zurück-Geste / Zurück-Taste schliesst offene Fenster (Hilfe, Konto, Klasse bearbeiten) statt die App zu schliessen.

## Version 2.4 – 21.11.2026
- Neuer Knopf «Feedback» in der Kopfzeile: öffnet ein anonymes Formular für Fehler, Inhaltsfehler und Wünsche. Version und Gerät werden automatisch mitgegeben; es werden keine Namen abgefragt.

## Version 2.3 – 18.11.2026
- Gast-Modus mit drei Demo-Klassen (Demo 1a: 18, Demo 2b: 22, Demo 3c: 20 Fantasienamen).

## Version 2.2 – 18.11.2026
- Einzelperson ziehen: drei Varianten mit ?-Erklärung statt «Ohne Wiederholung»:
  Zufällig · Alle einmal (danach «Alle waren dran», nächster Klick startet neu) · Endlos (sofort neue Runde, letzte Person nicht gleich wieder zuerst).
  Anzeige «x von y waren dran».
- Gruppen bilden: Knöpfe statt Dropdown – Max. Teamgrösse 2–8 und Anzahl Gruppen (nur Zahlen, die ohne 1er-Gruppe möglich sind). Ein Klick bildet die Gruppen sofort, nochmals klicken mischt neu.

## Version 2.1 – 17.11.2026
- Als App installierbar (Chrome auf Android, Tablet, Mac): Manifest, Service Worker (speichert nichts zwischen), Würfel-Icon.

## Version 2.0 – 17.11.2026
- Start mit Login-Seite; Registrierung entfernt (auch in Firebase gesperrt), «Passwort vergessen?» ergänzt.
- Gast-Modus «Als Gast ansehen» mit Demo-Klasse (Fantasienamen), speichert nichts.
- Fest codierte E-Mail, echte Beispielklassen und alter `sekSync`-Import entfernt.
- Gruppen: nie mehr 1er-Gruppen; Hinweis, wenn die Vorgabe nicht exakt aufgeht.
- Klassenwechsel leert den zuletzt gezogenen Namen.
- Gleiche Namen bleiben beim Bearbeiten getrennte Personen; Warnung bei doppelten Namen.
- Neuer Knopf «Alle weg».
- Sicherungen: tägliche Cloud-Sicherung (30 Tage, Wiederherstellen mit einem Klick), Backup-Datei herunterladen/einspielen, Erinnerung nach 7 Tagen.
- Zoom wirkt auf den ganzen Arbeitsbereich und wird gemerkt; Icons fest versioniert; Zufall mit crypto.getRandomValues.

## Version 1
- Erste Version (Archiv unter `versions/v1/`, ohne echte Klassenlisten).
