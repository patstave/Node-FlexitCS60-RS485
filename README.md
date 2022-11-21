# Node-FlexitCS60-RS485
Communicate with Flexit CS60 (e.g. UNI2) controller unit using a standard RS485 cable.

<h4> PINOUT RJ12 connector: </h4>

1. GND
2. GND
3. RS485 A+
4. RS485 B-
5. +12V
6. +12V

<h4> Serial communication parameters: </h4>

- Baudrate: 115,2 KBaud.
- Data bits: 8
- Parity: None
- Stop bits: 1
- Protocol: RS485 UART proprietary protocol (not Modbus!)

<h4> Suggested communication equipment: </h4>

- Standard RS485-USB cable (e.g. USB-RS485-WE-1800-BT)
- Elfin EW11 (RS485 - WiFi). This unit allows for a very elegant installation since the RJ12 connector also provides power supply. Works nicely with all default settings (all you have to set is WiFi SSID / key).
