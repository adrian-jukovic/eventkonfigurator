# Jukert Party & Eventservice — Homepage

Live: https://adrian-jukovic.github.io/eventkonfigurator/

Deployt automatisch über GitHub Pages bei jedem `git push` auf `master` — kein separater Deploy-Schritt mehr nötig, kein Credit-System, keine Ratenbremse. Repo ist dafür öffentlich (Code enthält keine Zugangsdaten).

Alte Adresse (Netlify, bleibt vorerst als Backup bestehen): https://jukert-party-homepage.netlify.app

- `index.html` — Startseite (Start/Leistungen/Über uns/Kontakt), verlinkt oben in der Navigation auf den Eventkonfigurator.
- `konfigurator.html` — lädt `eventkonfigurator.html` und zeigt es als eigene Unterseite an.
- `eventkonfigurator.html` — die eigentliche Quelle des Konfigurator-Widgets (Style + Markup + Script). Falls die Seite doch bei IONOS bleibt: das ist der Code, der 1:1 in das IONOS HTML-Modul eingefügt wird.
