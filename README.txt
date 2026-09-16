MORROW MONEY – PWA TEST PACKAGE V2

Enthalten:
- index.html (aktuelle Morrow Money Step-4-App)
- manifest.json
- sw.js
- icon-192x192.png
- icon-512x512.png

Cloudflare Pages:
- statische Site
- kein Build Command nötig
- Ordner mit index.html als Output/Root verwenden

iPhone Test:
1. Live-URL in Safari öffnen
2. Teilen
3. Zum Home-Bildschirm
4. Morrow Money vom Homescreen starten

Offline-Verhalten:
- lokale App-Dateien werden beim Service-Worker-Install gecacht
- externe CDN-Ressourcen werden nach erfolgreichem Laden dynamisch gecacht
- für eine finale Etsy-Version sollten Tailwind, Alpine, Lucide und Chart.js später lokal gebündelt werden
