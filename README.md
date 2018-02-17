# EmbeddedLinpack

[![Build Status](https://travis-ci.org/VioletGiraffe/EmbeddedLinpack.svg?branch=master)](https://travis-ci.org/VioletGiraffe/EmbeddedLinpack)

Linpack benchmark for embedded systems (Arduino, ESP32 et. al.). Adapted from https://gist.github.com/projectgus/8279947

This is a project for @platformIO. But you can also open the .ino file in the Arduino IDE and not have a care in the world about what PlatformIO is.

Tested on:

* Arduino Due @ 84 MHz - 0.38 double-precision MFLOPS, 0.62 single-precision
* Espressif ESP32 @ 160 MHz - 1.98 double-precision MFLOPS, 13.4 single-precision
* Arduino Uno R3 @ 16 MHz - 0.077 MFLOPS single precision (double-precision not available on the 8-bit AVR platfrom)