---
title: "BlueMicro nRF52832"
subtitle: "A nRF52832 breakout board with the pinout of a Pro Micro"
date: 2023-02-22T16:05:42-06:00
draft: false
Weight: 80
quantity: 32
price: 25
paypalid: "paypalid"
paypalbuttonid: "paypalbuttonid"
tindieid: 28575
categories: "Wireless Controller"
tags: [Arduino, CircuitPython, nRF52, nRF52832, Controller, ProMicro, BLE]
image: "Bluemicro832.jpg"
---
#### What is it?

The BlueMicro is a simple breakout board for the Ebyte E73-2G4M04S1B module (nRF52832) so that the pinout matches that of the [Pro Micro](https://www.sparkfun.com/products/12640). The BlueMicro was created to enable wireless functionality for DIY keyboards that uses the Pro Micro. This is why the pinout matches that of the [Pro Micro](https://www.sparkfun.com/products/12640) from Sparkfun.

The BlueMicro V2.1 expands on the BlueMicro V1.x and V2.0 by adding a serial chip to the breakout board for the Ebyte E73-2G4M04S1B module (nRF52832). This serial chip allows for programming the BlueMicro without the need for any additional hardware and simplifies the process since the serial chip is also connected to the reset circuitry. The charger is still powered by connecting a standard micro-usb cable to a computer or regular 5V charger. The pinout still matches that of the Arduino Pro Micro. The Raw pin is meant to be connected to the LiPo battery for powering on the BlueMicro.

Since the serial GPIOs are directly connected to the serial chip, the pinout differs slightly from the BlueMicro v2.0 and v1.0.

#### Bootloader and Arduino Compatibility

The [Adafruit nRF52 Bootloader](https://github.com/adafruit/Adafruit_nRF52_Bootloader) has been flashed. All GPIOs accessible to the pins were tested.
Since the BlueMicro is based on the [Adafruit Feather nRF52 Bluefruit LE](https://www.adafruit.com/product/3406?u&gclid=Cj0KCQiAveebBhD_ARIsAFaAvrHJLRL2vrVSZWe-63ouwzF5PZpKax_xekf4hH8y2RndOBNI60DLTl8aAidgEALw_wcB), most Arduino libraries compatible with the Feather nRF52832 are compatible with the BlueMicro.  The only thing to account for are the GPIOs/Pins used by the programs.

For programming, simply select the **Adafruit Feather nRF52832** from the **Adafruit nRF52 Boards**, select the appropriate serial port and upload your program.  Note that the serial chip used is the CH340. Some computers need a driver for handling this serial chip.  Follow these [instructions](https://learn.sparkfun.com/tutorials/how-to-install-ch340-drivers/all) if your computer does not detect the serial port when connecting the BlueMicro to your computer.

