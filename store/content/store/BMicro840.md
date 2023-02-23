---
title: "BlueMicro840 V1.x Fully Assembled and Tested"
subtitle: "A single BlueMicro for use with LiPo batteries. USB-C Connector and a nRF52840 chip. Same footprint as the Arduino Pro Micro"
date: 2023-02-21T15:03:50-06:00
draft: false
weight: 90
quantity: 0
price: 33.00
paypalid: "BMicro840"
paypalbuttonid: "JXQ9KMJQXQNRE"
tindieid: 21640
categories: "Wireless Controller"
tags: [Arduino, CircuitPython, nRF52, nRF52840, Controller, ProMicro, BLE]
image: "BlueMicro840_Small.jpg"
---

#### What is it?
The BlueMicro840 is a nRF52840 controller inspired on the Adafruit nRF52840 feather but with the footprint of an Arduino Pro Micro.  It can be programmed using standard Arduino tooling and supports the Adafruit nRF52 libraries.

#### Why did you make it?
Many DIY keyboards use the Arduino Pro Micro or the Arduino Micro as their microcontroller.  These don't support BLE communications natively.   Because the nRF52 chips have a 32-bit ARM Cortex-M4F processor, they have plenty of processing power compared to the traditional AVR chips. The BlueMicro boards were inspired from the Adafruit nrf52 feathers but made to be used directly in DIY keyboards as a replacement for the atmega32u4 based controllers.

#### What makes it special?
The BlueMicro840 has the same footprint as the Arduino Pro Micro. As such, it makes available 18 GPIOs for your own use.  This board is great for upgrading pro micro based keyboards.

The BlueMicro840 has the following features:

* LiPo battery charger on board. 
* USB-C Connector 
* nRF52840 processor. 
* Adafruit nRF52 Bootloader has been flashed. 
* All 18 GPIOs were tested and a simple test firmware flashed.

#### CircuitPython
The BlueMicro840 now supports CircuitPython!  To get started, get the latest [download](https://circuitpython.org/board/bluemicro840/) from the official [CircuitPython.org](https://circuitpython.org/) site, "double-reset" the BlueMicro840 and drop in the UF2.  On rebooting, the BlueMicro840 will show up as "CIRCUITPY" drive on your computer.

#### Notes on Availability
Due to the chip shortage, the availability of E73-2G4M08S1C modules (with chip antennas) has been very difficult and their costs have increased significantly (if they can be found).  E73-2G4M08S1CX modules are more readily available directly from the manufacturer but require an external antenna (included).