Update 09.05.2024

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
- (Raspberry Pi-Kamera)
   Raspberry Pi OS-Images, die auf Debian 12 (Codename 'bookworm') basieren, verwenden derzeit einen anderen Zweig des Kamera-Streamers! Der Raspberry Pi 5 unterstützt nur 
   ustreamer! Dies liegt an den fehlenden JPEG- und H264-Hardware-Encodern.

- mit USB Cam ist ok..


## Installation und Konfiguration

1. Lade die Klipper-Firmware herunter und folge den Anweisungen auf deren GitHub-Repository für die Installation.
2. Schließe die NVMe-Speichererweiterung, Sensoren, das 5-Zoll DSI Touch Display und die USB-Kamera gemäß den Anweisungen des Herstellers an den Raspberry Pi an.
3. Konfiguriere die Klipper-Firmware, um die Sensoren, Relais und das Display zu erkennen und zu steuern. Eine Beispielkonfiguration ist im Repository enthalten.
4. Verbinde deinen 3D-Drucker mit dem Raspberry Pi und teste die Funktionalität.

   KIAUH -- Klipper Installation And Update Helper
       (https://github.com/dw-0/kiauh)

        sudo apt-get update && sudo apt-get install git -y

        cd ~ && git clone https://github.com/dw-0/kiauh.git

        ./kiauh/kiauh.sh

 


## Beiträge

Beiträge sind immer willkommen! Wenn du Verbesserungen vornehmen möchtest, eine Funktion hinzufügen möchtest oder ein Problem beheben möchtest, öffne bitte ein Issue oder sende einen Pull-Request.

## Unterstützung

Wenn dir dieses Projekt gefällt und du mich unterstützen möchtest, kannst du gerne <a href="https://www.buymeacoffee.com/PerryDesign" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a> kaufen!

Dieses Projekt ist unter der MIT-Lizenz lizenziert. Weitere Informationen findest du in der Datei `LICENSE`.

#################
Gehäuse ist ein Remix of "Raspberry Pi 4 & 5 Mini Server Rack Case" 
https://makerworld.com/models/180806
 by @jonthemiller
################


Hardwarelinks


Raspberry Pi 5

Pimoroni NVMe Basis										 	--> https://www.amazon.de/dp/B0CTK1RLN5

Pi 5 Kamera Kabel Csi Display Dis Kabel 22pin bis 15 Pin	--> https://s.click.aliexpress.com/e/_Dn23HRj

Pi 5 Null-Kamera kabel 15 30 cm Farbband 					--> https://s.click.aliexpress.com/e/_Deio6RJ

ffc flexible kabel adapter platine 							--> https://s.click.al0express.com/e/_DE63QrP

Raspberry pi 4 kamera 5mp 									--> https://s.click.aliexpress.com/e/_DkESS4p

Sensor adxl345 digitale dreiachsige Beschleunigung 			--> https://s.click.aliexpress.com/e/_DCgDxRF

USB-CAM                                       --> https://s.click.aliexpress.com/e/_DmlUNZp

