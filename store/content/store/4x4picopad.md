---
title: "Raspberry Pi Pico 4x4 Macropad"
subtitle: "A simple Raspberry Pi Pico Macropad for use with CircuitPython or MicroPython"
date: 2023-02-22T16:15:18-06:00
draft: false
weight: 110
quantity: 2
price: 11
paypalid: "paypalid"
paypalbuttonid: "paypalbuttonid"
tindieid: 24918
categories: "Macropad"
tags: [Arduino, CircuitPython, RP2040, Macropad, Raspberry Pi Pico, MX Switches]
image: "4x4pico.jpg"
---


#### What is it?
This is a 4x4 Keyboard/keypad/macropad kit for you to build a 16 key macropad with a Raspberry Pi Pico. All you need are 16 MX mechanical switches and keycaps and about an hour for assembly.

#### What makes it special?
It's designed so that you can solder in a Raspberry Pi Pico and put it to good use!  

The kit includes (V1/V2 differences indicated):

- 4X4 Backpack RPI Pico PCB with the following pre-soldered:
  - 1 reset button
  - 1 WS2812B RGB LED
  - 1 capacitor
  - 1 Red LED (V1 Only)
  - 1 Blue LED (V1 Only)
  - 2 1k Resistors (V1 Only)


- 4x4 switch plate PCB

The Kit also includes the following for you to solder:

- 16 diodes (V1 Only)
- pins and sockets for connecting the 2 PCBs

Here is where the GPIOs of V1 are connected to:

- Rows: GPIO 0,1,2,3
- Columns: GPIO 4,5,6,7
- Red LED: GPIO 20
- Blue LED: GPIO 21
- Green LED (On Pico): GPIO 25
- Neopixel (WS2812B): GPIO 22

The GPIOs of V2 are directly connected to GPIOs instead of a key matrix.

- Green LED (On Pico): GPIO 25
- Neopixel (WS2812B): GPIO 28
- Keys: GPIO 3-10,15-22

Notes

- This is a solder-in kit and does not support hot-swap sockets for switches.
- This is a DIY keyboard kit which requires assembly and additional parts (switches and keycaps).
- Find the shortcuts of your favorite software at [defkey](https://defkey.com/rankings/most-popular-programs).
