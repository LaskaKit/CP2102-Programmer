![LaskaKit CP2102 Programmer](https://github.com/LaskaKit/CP2102-Programmer/raw/main/img/LaskaKit-CP2102-Programmer-1.jpg)

# Versatile CP2102 programmer with USB-UART convertor used for upload of firmware to ESP32, ESP8266 and Arduino development boards

If you are looking for a cheap programmer - USB-UART convertor - which you may use for our and yours ESP32, ESP8266 development board, you should check this programmer. 
This programmer may be used also for Arduino Mini and Mini Pro thanks to switch for 5V and 3.3V power supply which is on-board.

The programmer is based on the CP2102 USB-UART convertor. The board also include switch, where you choose which voltagelevel will be on VCC pin and also for logic level of BUS - 3.3V or 5V. Here is one more switch for disconnection of power on VCC pin of programmer.

![LaskaKit CP2102 Programmer](https://github.com/LaskaKit/CP2102-Programmer/raw/main/img/LaskaKit-CP2102-Programmer-3.jpg)

CP2102 programmer includes two types of USB connectors - microUSB and USB-C. You just use the cable which you have on the table. 

The pinout of programmer is the same as have our development boards which are programable in Arduino IDE. But it is not necessary to use it with our boards, you can also use it for oficial development boards with ESP32, ESP8266, Arduino Mini or Mini Pro. 

The programmer includes 3 status LEDs - one as indication of power supply, the rest for communication of TX, RX lines of UART bus.

The maximum current for 3.3V is 500mA , what is enough current for power of Arduino Uno to board with ESP8266 or ESP32. 

The output connector includes switchable power supply (3.3V or 5V), UART and DTR & RTS pins which are used for switch to bootloader mode.

Driver is available on https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers

It is available on https://www.laskakit.cz/prevodnik-6pin-microusb-ttl-uart--cp2102--dtr-pin/