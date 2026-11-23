# AIRONAUT – DIY Air Quality Monitor

**AIRONAUT** is a customizable, ESP32-S3-based indoor air quality monitor with a 3.5-inch touchscreen, RGB status LED, speaker and 3D-printed enclosure (**Hardware Rev. 1.0**). It's an independent, free-to-print DIY alternative to projects such as Project Aura.

**Links:** [MakerWorld enclosure](https://makerworld.com/de/models/3672269-aironaut-diy-air-quality-monitor-esp32-s3#profileId-4216118) [Flash Website](https://markussus.github.io/Aironaut/)

## Features

- **12 measurements/indicators:** PM1.0 / PM2.5 / PM4.0 / PM10, CO₂, VOC Index, NOx Index, HCHO, temperature, humidity, air pressure and a relative gas indicator.
- **Touch UI (LVGL 9.5):** customizable tiles, history graphs (15 min–24 h), German/English, light/dark themes.
- **Alerts:** configurable thresholds, RGB LED and audio notifications, including frost alerts.
- **Connectivity:** Wi-Fi, local hotspot (`Aironaut-AP`), live web dashboard, JSON API, weather and pollen data.
- **Storage:** microSD logging and file downloads; automatic NTP time sync.

> **Status:** Firmware is under active development. Available features depend on the installed release.

## Hardware – Bill of Materials

| Component | Qty. | Link |
|---|---:|---|
| Waveshare ESP32-S3-Touch-LCD-3.5 **with speaker** (without case/camera) | 1 | [Waveshare](https://www.waveshare.com/product/esp32-s3-touch-lcd-3.5.htm) |
| microSD card, 16 GB | 1 | Standard |
| Sensirion SEN69C | 1 | [Sensirion](https://sensirion.com/products/catalog/SEN69C) |
| Adafruit SEN6x breakout | 1 | [#6331](https://www.adafruit.com/product/6331) |
| Adafruit SHT45 | 1 | [#5665](https://www.adafruit.com/product/5665) |
| Adafruit BMP581 | 1 | [#6407](https://www.adafruit.com/product/6407) |
| Adafruit MiCS-5524 breakout | 1 | [#3199](https://www.adafruit.com/product/3199) |
| DFRobot DFR0239 RGB LED | 1 | [DFRobot](https://www.dfrobot.com/product-901.html) |
| STEMMA QT/Qwiic cable, 50 mm | 2 | [#4399](https://www.adafruit.com/product/4399) |
| STEMMA QT to male header, 150 mm | 1 | [#4209](https://www.adafruit.com/product/4209) |
| JST-GH 6-pin SEN6x cable, 100 mm | 1 | [#5754](https://www.adafruit.com/product/5754) |
| 10 kΩ and 15 kΩ resistors, ¼ W | 1 each | Standard |
| 100 nF ceramic capacitor | 1 | Optional, recommended |
| Female-to-male Dupont wires | 8 | Standard |
| USB-C cable | 1 | Standard |
| M2×4 countersunk screws | 16 | Standard |
| M2×6 countersunk screws | 3 | Standard |
| M2×10 screws | 8 | Standard |
| Printed AIRONAUT enclosure Rev. 1.0 | 1 set | [MakerWorld](https://makerworld.com/de/models/3672269-aironaut-diy-air-quality-monitor-esp32-s3#profileId-4216118) |

**Optional:** compatible RTC backup battery. The printed set includes the gasket and rubber feet. The ESP32-S3 is already part of the Waveshare display board.

## Assembly & firmware

Download the enclosure from MakerWorld and follow the [illustrated assembly guide](docs/AIRONAUT_Rev1.0_Assembly_Guide.pdf), including its pinout and voltage-divider diagram. Firmware and installation instructions are published through this repository's releases as they become available.

## License

- **Repository content (where owned by the AIRONAUT authors):** [CC BY-NC 4.0](LICENSE) – non-commercial use and sharing with attribution; commercial use requires separate permission.
- **3D-printable CAD files:** distributed via MakerWorld under its **Exclusive License**; private, non-commercial use only under the platform terms. They are **not** covered by this repository's CC license.
- Third-party components retain their own licenses.

**AIRONAUT — Built for makers, shared with the community.**
