CHALLENGE ROULETTE V13 – ONLINE BROWSER HOST

DAS IST DIE VERSION OHNE PYTHON / BAT / LOKALEN SERVER.

SO FUNKTIONIERT ES:
1. Den Inhalt dieses Ordners auf einen normalen STATIC WEB HOST hochladen.
   Geeignet sind z.B. Netlify, GitHub Pages, Cloudflare Pages usw.
2. Die veröffentlichte index.html am PC öffnen.
3. Der PC erstellt automatisch eine neue Sitzung und zeigt einen QR-Code.
4. QR-Code mit dem Handy scannen.
5. Am Handy öffnet sich host.html und verbindet sich direkt mit dem Game.
6. Sobald das Handy verbunden ist, verschwindet der QR-Bildschirm am PC.
7. Alles läuft danach im Browser.

HOST-STEUERUNG:
- Jetzt starten / sofort starten
- Fertig
- Joker
- Strafe
- Countdown beenden
- Nächste Runde
- Neustart
- Spiel beenden
- Live-Anzeige von Spieler, Challenge, Timer, Punkten, Streak und Joker

TECHNIK:
- PeerJS / WebRTC
- PeerJS Cloud wird nur zum Vermitteln der Verbindung verwendet.
- Danach laufen die Daten zwischen den Browsern.
- QR-Code enthält eine zufällige Sitzung + ein zufälliges Token.
- Kein eigener Servercode, keine Datenbank und kein Python erforderlich.

WICHTIG:
- Die Dateien nur per Doppelklick lokal zu öffnen reicht für den QR-Link NICHT.
  Sie müssen einmal online auf einem HTTPS Static Host liegen.
- Internet ist für die Online-P2P-Version erforderlich.
- Manche sehr restriktiven Netzwerke/NAT-Konfigurationen können WebRTC blockieren.
  Dann funktioniert eine serverbasierte Variante zuverlässiger.

EINFACHSTE VERÖFFENTLICHUNG:
- ZIP entpacken.
- Den Ordner bei einem Static-Hosting-Dienst hochladen.
- Danach nur noch die erhaltene Website-Adresse merken.
