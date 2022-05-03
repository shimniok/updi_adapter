# 6-Pin Serial to UPDI Adapter

A simple adapter board that converts any 6-pin USB to serial adapter to an Atmel AVR UPDI programmer with the use of [pymcuprog](https://pypi.org/project/pymcuprog/).

To program your tinyAVR 0/1/2 series device with Arduino IDE, you'll want to use Spence Konde's excellent [megaTinyCore](https://github.com/SpenceKonde/megaTinyCore).

Examples of 6-pin USB to serial adapters are typically based on [FTDI FT232](https://ftdichip.com/products/ft232rl/), [Silicon Labs CP210x](https://www.silabs.com/interface/usb-bridges/classic/device.cp2102), or [WCH CH340](http://www.wch-ic.com/products/CH340.html?from=list) integrated circuits.

My recommendations:

* [Sparkfun Basic Breakout, USB C / CH340](https://www.sparkfun.com/products/15096)
* [Sparkfun Basic Breakout, 5V FTDI](https://www.sparkfun.com/products/9716)
* [Adafruit FTDI Friend](https://www.adafruit.com/product/284)

Although you can find cheap versions on eBay, AliExpress, Amazon, etc., you might run into issues. For potential pitfalls and other guidance, refer to [Spence Konde's UPDI guide](https://github.com/SpenceKonde/AVR-Guidance/blob/master/UPDI/jtag2updi.md)
