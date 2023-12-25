# Airgradient-ESPHome
ESPHome config file for AirGradient ONE

Requries a secret.yaml containing the following items:
```
wifi_ssid: ""
wifi_password: ""
# true/false
hidden_ssid:
```

Fonts from:
https://github.com/olikraus/u8g2/tree/master

TODO:
* list references (https://github.com/MallocArray/airgradient_esphome)
* enable logging
* disable webserver
* re-add support for uploading to airgradient cloud without bricking on networks lacking internet access
* re-evaluate AQI calculations
* consider disabling PMS5003 intermittently to extend life of the unit (but probably shorten the fan's)
