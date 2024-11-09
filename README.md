# LANA TNY
## LANA
LANA is a small development board based around the [WCH CH32V203](https://www.wch-ic.com/products/CH32V203.html) RISC-V microcontroller.

## Where can I get one?
Currently you can get your hands on the LANA_TNY [in our Lectronz store](https://lectronz.com/products/lana-tny) or [through Adafruit](https://www.adafruit.com/product/6042).

## Programming

### Writing code
Various options are available.
- [Embeetle](https://embeetle.com/)
	- [Officially supported by Embeetle](https://embeetle.com/#supported-hardware/wch/boards/lana-tny-01)
- [Arduino core](https://github.com/openwch/arduino_core_ch32)
	- SPI and I²C Master support since version 1.0.2
- [Platform.io](https://github.com/Community-PIO-CH32V/platform-ch32v)
	- Requires your WCH-Link firmware to be updated to the latest version
- [CH32V003fun](https://github.com/cnlohr/ch32v003fun)
	- Experimental support for the CH32V203 at the time of writing
- [MounRiver Studio](https://www.mounriver.com/)
	- The official IDE supported by WCH, based on Eclipse.
- [WCH Toolchain for Mac](https://github.com/robinjanssens/WCH-Toolchain)
	- This toolchain has official support for LANA

### Loading code
The CH32V203 has an USB Bootloader which can be activated by holding down the button when plugging in the USB cable. Alternatively you could opt to use a [WCH-Link programmer and debugger](https://www.wch.cn/products/WCH-Link.html) to connect to the exposed SWD pins.

## TNY ?
TNY is our take on the [Adafruit QT Py](https://www.adafruit.com/category/595) and [Seeed studio XIAO](https://wiki.seeedstudio.com/Seeeduino-XIAO/) specifications but with added SMD pins for optional extra IO capabilities and a built in WS2811 compatible LED output.

## Pinout
![LANA TNY 01 pinout](media/pinout.png)

## LANA REV 01
![LANA TNY 01 LED](media/LANA_01_DEFAULT.gif)

![LANA TNY 01](media/LANA_01.png)
