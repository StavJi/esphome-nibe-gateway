# ESPHome NIBE Gateway

This project allows you to integrate your NIBE SMO40 and other NIBE heat pumps with **[ProDino ESP32 Ethernet](https://kmpelectronics.eu/shop/prodino-esp32-ethernet/)**, running `gateway.yaml` as a gateway, similar to the original NIBE MOSBUS40 accessory. It works with official [Home Assistant integration](https://www.home-assistant.io/integrations/nibe_heatpump).

---

## Setup Instructions

1. Get a **ProDino ESP32 Ethernet** board.
2. In Home Assistant ESPHome Builder, add a **new device**.
3. Choose **empty configuration**.
4. Give your device a descriptive **name**.
5. Copy the contents of `gateway.yaml` from this repository into your new device configuration.
6. Replace the **API encryption key** with your own.
7. Replace the **OTA password** with your own.
8. Replace the **Home Assistant IP address** with your own.

> Tip: Make sure your `secrets.yaml` is properly configured to avoid errors during compilation.

---

## Acknowledgements

This project is **based on the original work by [elupus](https://github.com/elupus/esphome-nibe)**.  
Many thanks for sharing the original ESPHome NIBE integration — this repository extends it for the ProDino ESP32 Ethernet board.

