[![Build Status](https://travis-ci.com/doudz/homeassistant-myjdownloader.svg?branch=master)](https://travis-ci.com/doudz/homeassistant-myjdownloader)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/kenoog)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-green.svg)](https://github.com/custom-components/hacs)

A simple sensor for MyJDownloader state

# Configuration

``` YAML
sensor:
  - platform: myjdownloader_kog
    email: myname@email.com
    password: mypassword
    name: JDownloader@keno # optional, if not provided all JDownloader devices will be generated.
    scan_interval: 5 # optional - default is 60
```

The name can be found via the MyJDownloader web interface <https://my.jdownloader.org/index.html>

