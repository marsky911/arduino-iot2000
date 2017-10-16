**Install Win7 usb driver for IOT2000**

1. Copy driver filese from folder ***usb_driver***
1. Plug micro usb cable on IOT2000 and PC
1. Open Device Manager
1. In Other devices you see ***CDC Serial*** or ***Unknown device***
1. Right click and select ***Update Driver Software...***
1. Select **Browse my computer for driver software***
1. Select ***Let me pick from a list of device drivers on my computer***
1. Press ***Next*** Button
1. Press ***Have Disk...*** Button
1. Press ***Browse...*** and set to driver folder
1. Select ***linux-cdc-acm.inf*** file and press ***Open*** button
1. Press ***OK***
1. Press ***Next***
1. Ignore warnings
1. On Device manager under Ports (COM & LPT) you must see the driver for IOT2000
1. In Arduino IDE select this Port
