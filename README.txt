VDZ Arnhem TeamTracker

Bestanden:
- index.html: app
- manifest.webmanifest: PWA-instellingen
- sw.js: offline ondersteuning
- icon-192.png / icon-512.png / apple-touch-icon.png: app-iconen

Installeren als PWA:
De map moet via HTTPS op een webserver staan. Alleen openen vanuit een ZIP of Google Drive is niet voldoende voor volledige PWA-installatie/service-workerfunctionaliteit.

iPhone: open de HTTPS-link in Safari > Deel > Zet op beginscherm.
Android: open de HTTPS-link in Chrome > menu > App installeren / Toevoegen aan startscherm.

Google Sheet:
De app bevat een vaste knop naar het opgegeven Google Sheet. Automatisch schrijven naar die Sheet vereist Google OAuth/API-configuratie en is niet ingebouwd in deze lokale versie.

Data:
Appdata wordt lokaal in de browser opgeslagen. Gebruik Data & Drive > Backup appdata voor een JSON-backup. CSV-exporten kunnen direct in Excel worden geopend en in Drive worden opgeslagen.
