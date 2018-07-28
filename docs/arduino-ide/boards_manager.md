Installation instructions using Arduino IDE Boards Manager
==========================================================

Starting with 1.6.4, Arduino allows installation of third-party platform packages using Boards Manager. We have packages available for Windows, Mac OS, and Linux (32 and 64 bit).

- Install the current upstream Arduino IDE at the 1.8 level or later. The current version is at the [Arduino website](http://www.arduino.cc/en/main/software).
- Start Arduino and open Preferences window.
- Enter ```https://dl.espressif.com/dl/package_esp32_index.json``` into *Additional Board Manager URLs* field. You can add multiple URLs, separating them with commas.
- Open Boards Manager from Tools > Board menu and install *esp32* platform (and don't forget to select your ESP32 board from Tools > Board menu after installation).

#### [Latest stable release ![Release Version](https://img.shields.io/github/release/espressif/arduino-esp32.svg?style=plastic) ![Release Date](https://img.shields.io/github/release-date/espressif/arduino-esp32.svg?style=plastic)](https://github.com/espressif/arduino-esp32/releases/latest/)
Stable release link: `https://dl.espressif.com/dl/package_esp32_index.json`

#### [Latest development release ![Development Version](https://img.shields.io/github/release/espressif/arduino-esp32/all.svg?style=plastic) ![Development Date](https://img.shields.io/github/release-date-pre/espressif/arduino-esp32.svg?style=plastic)](https://github.com/espressif/arduino-esp32/releases/latest/)
Development release link: `https://dl.espressif.com/dl/package_esp32_dev_index.json`