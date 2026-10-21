# legal

Öffentliche Seiten (GitHub Pages) für private Anwendungen von mgera: Startseite mit Offenlegung, Datenschutzerklärung, Nutzungsbedingungen. Gebraucht für die App-Registrierung bei Oura (`tasks-privat#17`), WHOOP (`#18`) und Withings (`#19`).

- CI: V3 (Quelle brand-Commit `beaf827`, tasks#22; `brand.css` und die drei Logos stimmen am 2026-10-22 byteweise mit `brand/dist` überein, `brand.css` bis auf den Schriftpfad). `assets/brand.css`, `favicon.svg`, `logo-on-dark.svg`, `logo-on-light.svg` sind Kopien aus `brand/dist` (`brand.css`, `logo/`), nicht von Hand ändern, bei CI-Änderung neu kopieren. Die Schriften (Inter, Inter Tight, JetBrains Mono, OFL) liegen unter `assets/fonts/`; beim Kopieren von `brand.css` den Pfad `/brand/v3/fonts/` durch `fonts/` ersetzen (GitHub Pages erreicht assets.mgera.io nicht). `theme-color`: dunkel `#0E0C0D`, hell `#F4EEE3`.
- Keine externen Ressourcen, keine Cookies, kein Tracking.
- Struktur: `index.html`, `privacy.html`, `terms.html` (Datenschutz und Nutzungsbedingungen Deutsch mit englischem Abschnitt `#en`), `assets/` (`brand.css`, `site.css`, Logos, Schriften). Veröffentlichung über GitHub Pages. Die juristischen Inhalte ändert nur Marc bzw. nach seinem Auftrag.
