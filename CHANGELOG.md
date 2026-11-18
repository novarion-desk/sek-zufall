# Changelog

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
