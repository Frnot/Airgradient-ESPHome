# Airgradient-ESPHome
ESPHome config file for AirGradient ONE

Requries a secret.yaml containing the following items:
```
wifi_ssid: ""
wifi_password: ""
# true/false
hidden_ssid:
```

TODO:
* list references (https://github.com/MallocArray/airgradient_esphome)
* select better font
* Make display match stock AG1 firmware
* add switch for PM2.5 units
* invert OLED display toggle
* disable webserver
* re-add support for uploading to airgradient cloud without bricking on networks lacking internet access
* re-evaluate AQI calculations
* consider disabling PMS5003 intermittently to extend life of the unit (but probably shorten the fan's)
