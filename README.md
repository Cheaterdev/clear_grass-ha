# clear_glass-ha
Xiaomi ClearGlass Air Detector integration into HA

Based on:
https://github.com/rytilahti/python-miio/blob/master/miio/airqualitymonitor.py
https://github.com/syssi/xiaomi_airqualitymonitor/blob/develop/custom_components/sensor/xiaomi_miio.py

## WARNING
This integration is not official. There will be official support in HA(i believe).

## Features
- PM2.5
- CO2
- TVOC
- Temperature
- Humidity

## Setup

Merge custom_components folder

```yaml
# configuration.yaml


# Same as Xiaomi Air Quality Monitor
sensor:
  - platform: xiaomi_miio
    name: Xiaomi ClearGlass Air Detector
    host: 192.168.130.73
    token: YOUR_TOKEN
    
```

To retreive TOKEN use this instructions: 
https://www.home-assistant.io/components/vacuum.xiaomi_miio/#retrieving-the-access-token

## Disclaimer
This software is supplied "AS IS" without any warranties and support.

