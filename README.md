## Klippersteuerung mit Raspberry Pi 5 und NVMe

Dieses Projekt ermöglicht die Steuerung eines 3D-Druckers unter Verwendung der Klipper-Firmware auf einem Raspberry Pi 5, zusammen mit einer NVMe-Speichererweiterung und verschiedenen Sensoren und Relais.

## Funktionen

- Verwendung der Klipper-Firmware für eine verbesserte 3D-Druckersteuerung und -performance.
- Anschluss einer NVMe-Speichererweiterung für schnellen Zugriff auf Druckdateien und verbesserte Druckzeiten.
- Integration von Sensoren für eine genauere Überwachung des Druckprozesses:
  - 2x DS18B20-Temperatursensoren: Einer im Druckraum und einer im Filamentlager zur Überwachung der Temperatur.
  - Ansteckbarer ADXL345-Beschleunigungssensor zur Messung von Beschleunigung und Resonanz während des Drucks.
- 2 Relais zur Steuerung der LED-Beleuchtung im Druckraum und im Filamentlager, die einzeln schaltbar sind.
- 5-Zoll DSI Touch Display zur Anzeige von Klipper-Statusinformationen und Bedienung des Druckers.
- Raspberry Pi-Kamera zur Überwachung des Druckvorgangs.

## Hardware-Anforderungen

- Raspberry Pi 5 oder kompatibler Einplatinencomputer
- NVMe-Speichererweiterung
- 2x DS18B20-Temperatursensoren
- Ansteckbarer ADXL345-Beschleunigungssensor
- 2 Relais
- 5-Zoll DSI Touch Display
- Raspberry Pi-Kamera

## Installation und Konfiguration

1. Lade die Klipper-Firmware herunter und folge den Anweisungen auf deren GitHub-Repository für die Installation.
2. Schließe die NVMe-Speichererweiterung, Sensoren, das 5-Zoll DSI Touch Display und die Raspberry Pi-Kamera gemäß den Anweisungen des Herstellers an den Raspberry Pi an.
3. Konfiguriere die Klipper-Firmware, um die Sensoren, Relais und das Display zu erkennen und zu steuern. Eine Beispielkonfiguration ist im Repository enthalten.
4. Verbinde deinen 3D-Drucker mit dem Raspberry Pi und teste die Funktionalität.

## Beiträge

Beiträge sind immer willkommen! Wenn du Verbesserungen vornehmen möchtest, eine Funktion hinzufügen möchtest oder ein Problem beheben möchtest, öffne bitte ein Issue oder sende einen Pull-Request.

## Unterstützung

Wenn dir dieses Projekt gefällt und du mich unterstützen möchtest, kannst du gerne [![Perry Design]](https://www.buymeacoffee.com/perrydesign) kaufen!
<script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="PerryDesign" data-color="#FFDD00" data-emoji=""  data-font="Cookie" data-text="Buy me a coffee" data-outline-color="#000000" data-font-color="#000000" data-coffee-color="#ffffff" ></script>
## Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert. Weitere Informationen findest du in der Datei `LICENSE`.
