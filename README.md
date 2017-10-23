# Simatic IOT2000 board support and libraries

## Installation

1. Install [Arduino IDE](https://www.arduino.cc/en/main/software)
1. Start Arduino IDE 
1. In Arduino IDE select ***File->Preferences***
1. Enter or copy-paste text in field ***Additional Borad Manager URL's:***
https://raw.githubusercontent.com/sblyolcubal/arduino-iot2000/master/package_iot2000_index.json
1. Close Preferences
1. In Arduino IDE select ***Tools->Board xx->Boards Manager..***
1. Select Type: **Contributed**
1. Select ***Simatic IOT2000 Devices by Siemens AG version x.x.x***
1. Press **Install** button

For transfer sketch over USB:
1. Plug IOT2000 on usb port (use micro usb on IOT2000)
1. [Install driver](DRIVERWIN7.md)  from folder ***usb_driver*** (only for Windows 7)
1. Select ****Simatic IOT2000*** device
1. Select Port
1. Upload sketch

For transfer sketch over LAN:

***IOT2000 must have IP 192.168.200.1 user root and no password***
1. Select ***Simatic IOT2000 Net***device
1. Upload sketch

## Copyright and license

Copyright 2017 Sbl. Yolcubal. under [the Apache 2.0 license](LICENSE).

Forked from: https://github.com/01org/corelibs-galileo
 
## Changelog

Version [changelog](CHANGELOG.md).

Library [description](LIBRARY.md).

**Simatic** and **Simatic IOT2000** are trademark of Siemens AG.
