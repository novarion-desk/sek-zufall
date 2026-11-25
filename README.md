# Klassen-Zufallsgenerator & Gruppen-Tool (Sek A)

Live-App: https://novarion-desk.github.io/sek-zufall/

## Aufbau

| Pfad | Inhalt |
|---|---|
| `index.html` | Aktuelle Version der App |
| `manifest.webmanifest`, `sw.js`, `icons/` | Installierbar als App (Chrome: Menü → «App installieren») |
| `tailwind.css`, `vendor/` | Design, Icons, Firebase und Schrift lokal (offline-fähig). `tailwind.css` bei neuen Klassen neu bauen |
| `versions/vX/` | Archiv älterer Versionen – jede ist direkt aufrufbar |
| `CHANGELOG.md` | Was sich in welcher Version geändert hat |

## Zu einer älteren Version zurück

- Version 2.5: https://novarion-desk.github.io/sek-zufall/versions/v2.5/
- Version 2.4: https://novarion-desk.github.io/sek-zufall/versions/v2.4/
- Version 2.3: https://novarion-desk.github.io/sek-zufall/versions/v2.3/
- Version 2.2: https://novarion-desk.github.io/sek-zufall/versions/v2.2/
- Version 2.1: https://novarion-desk.github.io/sek-zufall/versions/v2/
- Version 1: https://novarion-desk.github.io/sek-zufall/versions/v1/

Funktioniert die aktuelle Version nicht, den Link der vorherigen Version öffnen und weiterarbeiten.
Danach Claude sagen, dass die alte Version wieder zur Hauptversion werden soll.

## Login

- Nur Anmeldung, keine Registrierung (in Firebase gesperrt).
- «Als Gast ansehen» zeigt drei Demo-Klassen mit Fantasienamen – nichts wird gespeichert.

## Daten & Sicherungen

- **Cloud:** Firebase-Projekt «Unterrichtscockpit» (ID `zufallsgenerator-209f3`), Firestore Region europe-west6 (Zürich).
  Daten unter `users/{uid}/data/appState`, nur für das eigene Konto lesbar.
- **Automatisch:** Tägliche Cloud-Sicherung unter `users/{uid}/backups`, die letzten 30 Tage –
  in der App unter «Konto» mit einem Klick wiederherstellbar. Vor jeder Wiederherstellung und jedem Import wird der aktuelle Stand zusätzlich gesichert.
- **Manuell:** «Konto» → «Backup herunterladen» (.json). Empfohlen 1× pro Woche (gelber Punkt nach 7 Tagen).
- Nur Vornamen erfassen.

## Feedback
Der Knopf «💬 Feedback» öffnet ein externes, anonymes Formular bei Tally (Fehler, Wünsche, Inhalte). Nur dann werden Angaben gesendet – zusammen mit App-Name, Version und Gerätetyp. Namen werden nicht abgefragt.
