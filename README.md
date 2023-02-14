# tuyaLight - replacement firmware for TuYa LED controllers
This project intended to replace fitmware in TuYa TS0501B, TS0504B (and possible others) LED controllers.

## Why?
Because TuYa firmware sucks, that's why :)
But, seriously, not counting common drawbacks of TuYa devices firmware like manufacturer dependent messages and overall strange approach to zigbee standat, this devices have very annoying bug: sometimes, then device receive On command, it turn on light for few seconds and turned off. I was unable to find exact condition to trigger this bug, but it happens from time to time.
So, this project was born.

# Compilation
See [docs/installation.md](docs/sdk_installation.md)

# Flashing
TBD

# Technical details
TuYa Zigbee LED controllers can be bought cheapely on Aliexpress. for example, [Here](https://www.aliexpress.com/item/1005005196855536.html). From hardware point of view, they all the same, at least TS0501B and TS0504B, and differs only by firmware and external connector to LED strip.
Known devices and status:
- TS0501B single Work in progress, mostly working
- TS0502B CCT Not started
- TS0503B RGB Not started
- TS0504B RGBW Work in progress
- TS0505B RGB/CCT Not started
