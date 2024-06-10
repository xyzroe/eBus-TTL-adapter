---
layout: page
hide_title: true
hide: true                          
---
### About
This adapter is designed to connect an eBus compatible boiler to any TTL port (TTL-USB, ESP8266, ESP32, Arduino, etc).  

Same size as popular RS485-TTL module for more compatibility.  

As a software part, you can use [ebusd](https://github.com/john30/ebusd) with different connection types:
- **TTL-UART** - you need converter that doesn't buffer too much data (CP2102 or FTDI based (like FT232)) 👍  
- **ESP8266 / ESP32** enhanced ebusd protocol using [ebusd-esp](https://github.com/john30/ebusd-esp/) firmware (only Wi-Fi connection now) 🎉  
- **Raspberry Pi** internal UART port can be used with [some preparations](https://github.com/john30/ebusd/wiki/eBus-with-Raspberry-Pi-Serial),  
  but I recommend [ttyebus kernel module](https://github.com/eBUS/ttyebus) which is with the lowest latency possible 🚀  
- **ser2net** compatible firmware (ESPEasy, ESP-Link, ESPHome, Tasmota, etc) or hardware converter
  *with some restrictions (Receive - OK; Transmit - may be errors)* 🤔

Also available HA [integration](https://www.home-assistant.io/integrations/ebusd/) between [ebusd](https://github.com/john30/ebusd) daemon and Home Assistant 🏚

### Overview
<div align="center">
<img width="40%" src="https://raw.githubusercontent.com/xyzroe/eBus-TTL-adapter/images/top.png">
<img width="40%" src="https://raw.githubusercontent.com/xyzroe/eBus-TTL-adapter/images/bottom.png">
</div>

### Photos
<div align="center">
<img width="70%" src="https://raw.githubusercontent.com/xyzroe/eBus-TTL-adapter/master/images/1.jpeg">
<img width="70%" src="https://raw.githubusercontent.com/xyzroe/eBus-TTL-adapter/master/images/2.jpeg">
</div>

### Schematic
![Schematic](https://raw.githubusercontent.com/xyzroe/eBus-TTL-adapter/images/Schematic.png)

### Where to buy?
<a href="https://www.tindie.com/stores/mind/?ref=offsite_badges&utm_source=sellers_xyzroe&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" height="120"></a>

### DIY
- [iBOM page](./files/iBOM.html) 🌍
- [Gerber zip](./files/Gerber_v0.3.zip) 🗂

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>

### Like ♥️?
[![badges](https://badges.aleen42.com/src/buymeacoffee.svg)](https://www.buymeacoffee.com/xyzroe) 
[![badges](https://badges.aleen42.com/src/github.svg)](https://github.com/sponsors/xyzroe)
[![badges](https://badges.aleen42.com/src/paypal.svg)](http://paypal.me/xyzroe) 

### Inspired by
- [eBUS wiki](https://ebus-wiki.org/doku.php)  
- [FHEM wiki](https://wiki.fhem.de/wiki/EBUS)  
- [john30/ebusd](https://github.com/john30/ebusd)  
- [eBUS adapter 2](https://ebus.github.io/adapter/index.en.html)  
- [eBuzzz adapter](https://gitlab.com/fromeijn/ebuzzz-adapter)  
- [Floris Romeijn - Connected Vaillant to Home Assistant](https://fromeijn.nl/connected-vaillant-to-home-assistant/)
