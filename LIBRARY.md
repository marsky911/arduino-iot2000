# Simatic IOT2000 arduino library

## Addition to standart arduino library:

Serial Ports:

* ***Serial3 (X30) and Serial4 (X31)***

***RS232:***
``` c++	
	Serial3.begin(<baudrate>);
	Serial4.begin(<baudrate>);
```
***RS422:***
``` c++	
	Serial3.begin(<baudrate>, "rs422");
	Serial4.begin(<baudrate>, "rs422");
```
***RS422:***
``` c++	
	Serial3.begin(<baudrate>, "rs485");
	Serial4.begin(<baudrate>, "rs485");
```

***Line Termination:***
``` c++	
	Serial3.begin(<baudrate>, "rs422", true);
	Serial4.begin(<baudrate>, "rs485", true);
```

* ***SerialUsb1 (X60)***
``` c++	
	SerialUsb1.begin(<baudrate>);
```

Ethernet Ports:

* ***Ethernet (X1) and Ethernet1 (X2)***

	see Ethernet libray example

User Led:

* ***UserLed***

	see ***UserLed*** libray example

User Button:

* ***UserButton***

	see ***UserButton*** libray example

