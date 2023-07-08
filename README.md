# nokia-cube | ESP32 | PCD8544

## Overview

![image](https://www.voidstudios.com.au/_next/image?url=%2Fimg%2Fnokia-cube%2Fnc-header-img.jpg&w=1080&q=75)

Small ESP32 powered Nokia PCD8544 program for displaying usefull information.

[More info](https://www.voidstudios.com.au/projects/nokia-cube-retro-desktop-notification-centre)

Update the sdkconfig and put in your SSID and PW for your wifi station:

```text
CONFIG_ESP_WIFI_SSID=""
CONFIG_ESP_WIFI_PASSWORD=""
```

# Env. Setup

Need to load in the esp-idf environment.

```bash
get_idf
```

# Compile

```bash
idf.py build
```

# Flash

```bash
idf.py -p <device> flash
```
