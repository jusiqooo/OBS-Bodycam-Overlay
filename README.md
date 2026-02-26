# Bodycam Overlay

Ein minimalistisches Overlay für Obs -> zeigt REC-Status, Gerät, Benutzer, Callsign, Datum, Uhrzeit und Zeitzone.

### Features
- Blinkender REC-Punkt
- Anzeige von Gerät, Benutzername & Callsign
- Echtzeit Datum & Uhrzeit mit Sekunden
- Zeitzone automatisch
- Transparentes Overlay, Schrift: Share Tech Mono

### Konfiguration
Im `<script>`-Block:

```javascript
const CONFIG = {
    player: "David Laker |",
    callsign: "[12-200]",
    deviceName: "Axon Body 3"
};
````
## Usage (OBS Einbindung)

### 1. Datei speichern
Speichere den Code  besten in einem festen Ordner, den du nicht verschiebst.

### 2. In OBS einbinden
1. OBS öffnen
2. Szene auswählen
3. Bei **Quellen** auf **+** klicken
4. **Browser** auswählen
5. Namen vergeben (z.B. Bodycam Overlay)
6. **Lokale Datei** aktivieren
7. Deine `bodycam.html` auswählen
8. Größe anpassen

## Preview
![Overlay Preview](preview.png)
