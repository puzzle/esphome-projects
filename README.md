# Puzzle ESPHome Projects

This repository contains the documentation and code for building a "beer button", a "beer light" and more using [NodeMCUs (ESP8266)](https://www.bastelgarage.ch/esp8266-esp32/esp-boards/esp8266-nodemcu-v3-kompatibles-development-board) and [ESPHome](https://esphome.io). 


## Flashing a NodeMCU

1. Go to [the ESPHome page](https://esphome.puzzle.ch/) and open the correct config.
2. Hit `INSTALL`->`Manual Download`. The firmware gets compiled and the binary downloaded to your computer.
3. Connect the ESP to your computer using *a data capable* USB cable.
4. Go to [ESP Web Tools](https://web.esphome.io/).
5. Hit `connect`, select your ESP.
6. Upload the binary that just got downloaded to your PC and flash it.

If the Wi-Fi network the ESP gets connected to can mDNS to the Host running the ESPHome page,
the ESP can now be flashed over-the-air and does not need to be connected via USB to the computer anymore.


## The wiring and soldering part

Beer button schema:

![Beer Button Schema](/images/beerbutton.png)

Beer light schema:

![Beer Light Schema](/images/beerlight.png)
