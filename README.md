# Bodycam Overlay

Ein minimalistisches Overlay für Obs -> zeigt REC-Status, Gerät, Benutzer, Callsign, Datum, Uhrzeit und Zeitzone.

## Features
- Blinkender REC-Punkt
- Anzeige von Gerät, Benutzername & Callsign
- Echtzeit Datum & Uhrzeit mit Sekunden
- Zeitzone automatisch
- Transparentes Overlay, Schrift: Share Tech Mono

## Konfiguration
Im `<script>`-Block:

```javascript
const CONFIG = {
    player: "David Laker |",
    callsign: "[12-200]",
    deviceName: "Axon Body 3"
};
