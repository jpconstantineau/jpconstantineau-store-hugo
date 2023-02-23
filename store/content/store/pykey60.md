---
title: "PyKey60 - RGB Keyboard PCB with a RP2040"
subtitle: "A 60% RGB Keyboard PCB with Hot Swap Sockets, running CircuitPython on a RP2040"
date: 2023-02-22T16:15:02-06:00
draft: false
weight: 310
quantity: 2
price: 50
paypalid: "paypalid"
paypalbuttonid: "paypalbuttonid"
tindieid: 24940
categories: "Keyboard"
tags: [Arduino, CircuitPython, Keyboard, RP2040, 60Percent, MX Switches]
image: "pykey60.jpg"
---

#### What is it?

The PyKey60 is a custom programmable mechanical keyboard with a standard ANSI 60% keyboard layout compatible with any cases made for the GH60. The PyKey60 uses mechanical switches (Cherry MX type). The keys are hot-swap socketed and have an individual underglow RGB LED which can be turned on.  The PCB was designed for use with PCB-mount stabilizers.

Since this is a Hot Swappable Switches keyboard, you can choose the MX switches as well as the keycaps you prefer.  You can even mix and match switches for the ultimate customization.

Just like CircuitPython, this keyboard is targeted for beginners.  The design keeps the matrix definition simple to 14 columns and 5 rows instead of using a GPIO-optimized matrix of 8 columns and 8 rows.  Neopixel order is also in line with key numbers.  This keeps the complexity of coding a keyboard firmware to a minimum.

#### What makes it special?
This is a fully programmable keyboard which doesn't require any tooling or special software to change its programming!

#### Features
* Powered by the Raspberry Pi RP2040 Microcontroller
* Per key RGB LEDs (NeoPixels)
* Kailh hot-swap switch sockets (for Cherry MX-compatible switches)
* Included buzzer for audio feedback
* Powered and programmable via USB-C
* Supports the [KMK Firmware](https://github.com/KMKfw/kmk_firmware)

#### About the RP2040
The RP2040 microcontroller is a dual core ARM Cortex M0+ running at up to 133Mhz. It bundles in 264kB of SRAM, 30 multifunction GPIO pins (including a four channel 12-bit ADC), a heap of standard peripherals (I2C, SPI, UART, PWM, clocks, etc), and USB support.

#### What's included?

* 1 PyKey60 PCB

#### Notes:

* Standard order does not come with switches, stabilizers, switch plate case or keycaps. You will need to obtain these yourself.
* Some assembly is required, no soldering of the switches is needed.
* Switches must be installed with the PCB on a flat surface, so as to not damage the hot swap sockets. Pushing the switches in while holding the PCB in midair may cause the hot swap sockets to come off.
* Due to the hot swap sockets and the USB C connector some cases may not be compatible without modification.
* Depending on the case you use, USB-C cables with large connector "heads" may have trouble reaching to the connector on the PCB without modifying the case.