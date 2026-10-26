CHALLENGE ROULETTE V19 – HALLOWEEN HIDE & SEEK TEST

WICHTIG:
Diese Version ist eine Testversion für den komplett neuen Halloween-Modus.
Standard und Geburtstag bleiben weiterhin enthalten.

NEUER HALLOWEEN-START:
- Statt Stunden/Minuten/Sekunden stellst du eine UHRZEIT ein, z.B. 22:00.
- Das Spiel berechnet automatisch die Zeit bis zur nächsten 22:00 Uhr und zählt herunter.
- Nach Ablauf erscheint "JETZT STARTEN".

HIDE & SEEK:
1. JETZT STARTEN
2. "HALLOWEEN EVENT GESTARTET"
3. "HIDE & SEEK"
4. Namensrad wählt einen Sucher
5. PC zeigt den Sucher + eigenen Seeker-QR
6. Weiter → gemeinsamer Hider-QR
7. Jeder Hider scannt und wählt seinen Namen
8. Der Sucher ist bei der Hider-Namensauswahl ausgeschlossen
9. Hider erlauben Standort und drücken READY / BIN VERSTECKT
10. Seeker-Seite zeigt live READY / nicht READY
11. Sind alle READY, erscheint beim Sucher "ALLE SIND VERSTECKT"
12. Sucher drückt "JETZT SUCHEN"
13. Eingestellte Suchzeit startet
14. Sucher kann jeden Hider über "GEFUNDEN" markieren
15. Wenn alle gefunden sind oder die Zeit abläuft, endet das Spiel

LIVE GPS:
- PC/Leinwand: Live-Map mit Sucher + allen Hidern
- Hider-Handys: Live-Map mit Sucher + allen Hidern
- Sucher-Handy: KEINE Karte der Hider
- Gefundene Hider werden grau markiert
- GPS-Genauigkeit wird angezeigt
- Standortdaten werden nur in der laufenden Browser-Spiel-Sitzung verwendet

NEUE DATEIEN:
- index.html       PC / Leinwand
- host.html        normale Handy-Hoststeuerung
- seeker.html      Seite für den ausgewählten Sucher
- hider.html       Seite für alle Hider

TECHNIK:
- GitHub Pages / HTTPS erforderlich
- PeerJS/WebRTC für Live-Synchronisierung
- Browser-Geolocation für GPS
- Leaflet + OpenStreetMap für die Live-Karte
- Handys sollten die jeweilige Seite während des Spiels offen lassen

GITHUB:
ALLE 4 HTML-DATEIEN hochladen/ersetzen:
index.html
host.html
seeker.html
hider.html
