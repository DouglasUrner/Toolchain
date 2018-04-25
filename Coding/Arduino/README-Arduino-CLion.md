# OSX-Arduino-CLion-Toolchain

Notes on setting up an Arduino development environment with JetBrains CLion on a Mac.

My personal preference would be to use the command line toolchain (gcc-avr, avrdude, etc.) and "normal" C++ but
another piece of the motivation for taking this on is to have a relatively straight-forward way to work with the
mechatronics classes at my school and they are using the Arduino IDE, so I'd like to see if I can find a way to
use .ino files as well.

I'd also like to use IntelliJ rather than CLion (because there isn't a CLion community edition), but there aren't
any currently supported plugins.

## Approach

### Alternatives

## Bits & Pieces

* [CMake](https://cmake.org) -
* [PlatformIO](https://platformio.org) -
* [Serial Port Monitor](https://plugins.jetbrains.com/plugin/8031-serial-port-monitor) - CLion plugin

## Steps

1. brew install platformio
