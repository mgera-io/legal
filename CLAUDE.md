# legal – öffentliche Seiten für private Anwendungen

**cortex Zentrale** (`DEC-cortex-zentrale`): Aufträge laufen über Root, nur Root committet. Helfer folgen den Regeln hier; jede andere Sitzung liest nur.

Statische Seiten (GitHub Pages): Startseite mit Offenlegung, Datenschutzerklärung, Nutzungsbedingungen, gebraucht für App-Registrierungen bei Oura, WHOOP, Withings. Details: `README.md`.

## Aufbau

- `index.html`, `privacy.html`, `terms.html` (Deutsch, englischer Abschnitt `#en`).
- `assets/`: `brand.css`, `favicon.svg`, `logo-on-dark.svg`, `logo-on-light.svg` sind Kopien aus `brand/dist`, nicht von Hand ändern. `site.css` ist eigen, Schriften unter `assets/fonts/`.

## Testen

- Es gibt keine automatischen Tests (Annahme: kein Build, reines HTML/CSS).
- Prüfen: `git diff`, Links und Pfade nachsehen, keine externen Ressourcen, keine Cookies, kein Tracking. Bei CI-Änderung `brand.css` neu kopieren und den Schriftpfad `/brand/v3/fonts/` durch `fonts/` ersetzen.

## Grenzen

- **Vertraulich:** Das Repo ist öffentlich, die Inhalte sind juristisch. Die juristischen Texte ändert nur Marc bzw. nach seinem Auftrag, Helfer ändern sie nicht eigenmächtig.
- Keine Inhalte der Seiten oder persönliche Angaben in Issues, Kommentare, Logs oder Berichte kopieren, dort nur Dateinamen und Abschnittsnamen nennen.
- Keine Secrets, keine internen Hostnamen oder IPs.
