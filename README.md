# Puzzle ESPHome Projects

This repository contains the documentation and code for building a "beer button", a "beer light" and more using [NodeMCUs (ESP8266)](https://www.bastelgarage.ch/esp8266-esp32/esp-boards/esp8266-nodemcu-v3-kompatibles-development-board) and [ESPHome](https://esphome.io). 


## Flashing a NodeMCU

1. Provide a `secrets.yaml` file using `secrets.yaml.example` as a guideline
2. Clone this repository, `cd` into its directory
3. Connect a NodeMCU to your computer using a Micro USB cable
4. Flash the NodeMCU using the following command or one of [ESPHome](https://esphome.io)'s own Getting Started guides:

```bash
podman run --rm -v "${PWD}":/config:Z --device=/dev/ttyUSB0 -it esphome/esphome beer_button.yaml run
```

If everything worked correctly, the ESPHome can now be flashed over-the-air and does not need to be connected via USB to the computer anymore.


## The wiring and soldering part

Beer button schema:

![Beer Button Schema](/images/beerbutton.png)

Beer light schema:

![Beer Light Schema](/images/beerlight.png)
