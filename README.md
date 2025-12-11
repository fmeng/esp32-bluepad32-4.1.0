# Bluepad32              4.1.0
https://github.com/ricardoquesada/esp32-arduino-lib-builder/releases

#### Bluepad32 4.1.0

#### BTstack 1.6.1

#### Esp32 Arduino Core 2.0.17

# Arduino-ESP32 Core     2.0.17  
https://github.com/espressif/arduino-esp32/releases/tag/2.0.17

#### The Arduino ESP32 version 2.0.17 is based on the ESP-IDF v4.4.7 (release notes) and is bug fix release for Arduino ESP32 Core version 2.X.X.

# PlatformIO             6.10.0
https://github.com/platformio/platform-espressif32/releases/tag/v6.10.0

#### Arduino - v2.0.17 (based on IDF v4.4.7)

# ESP-IDF                v4.4.7
https://github.com/espressif/esp-idf/releases/tag/v4.4.7

# platformio config demo

```ini
[env:wemos_d1_mini32]
platform = espressif32@6.10.0
board = wemos_d1_mini32
framework = arduino
platform_packages = framework-arduinoespressif32@https://github.com/fmeng/esp32-bluepad32-4.1.0/archive/refs/heads/main.zip
;platform_packages = framework-arduinoespressif32@file:///Users/fmeng/CLionProjects/esp32-bluepad32-4.1.0
```