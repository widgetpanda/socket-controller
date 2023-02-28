# ESP8266 (NodeMCU) Socket Controller

## Overview

ESP8266 only has a maximum of 6 ports that can be used seamlessly.
Available port for ESP8266:
- `GPIO16` (D0)
- `GPIO5` (D1)
- `GPIO4` (D2)
- `GPIO14` (D5)
- `GPIO12` (D6)
- `GPIO13` (D7)

## Scheme

???

## Programming

1. Install classic Arduino IDE, download from here https://www.arduino.cc/en/software/OldSoftwareReleases
2. Start Arduino and open the **Preferences** window.
3. Enter `https://arduino.esp8266.com/stable/package_esp8266com_index.json` into the **File > Preferences > Additional Boards Manager URLs** field of the Arduino IDE. You can add multiple URLs, separating them with commas.
4. Open **Boards Manager** from **Tools > Board** menu and install _esp8266_ platform (and don't forget to select your ESP8266 board from _Tools > Board_ menu after installation).
5. Copy all `code.ino` content and paste into your IDE.
6. Upload or flash the code.

## Reference

- Arduino (https://www.arduino.cc/en/software)
- ESP8266 (https://github.com/esp8266/Arduino)
- How To Program An ESP8266 With the Arduino IDE - YouTube (https://www.youtube.com/watch?v=AFUAMVFzpWw)

## Etc

- CP210x Driver (https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers)
- CH340G Driver (https://sparks.gogo.co.nz/ch340.html)