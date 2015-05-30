# Cosa-AVR

This Cosa library is an implementation of the STK500 Communication
Protocol (V1.X) to allow Arduino to act as an ISP. Uses the Cosa
Programmer class to perform the actual programming of devices
(e.g. ATtiny).

# Install

To use this library you must download and install the [Arduino IDE] (http://www.arduino.cc/en/Main/Software) (or
GCC AVR toolchain) and [Cosa] (https://github.com/mikaelpatel/Cosa).

Download and unzip the Cosa-AVR library into your sketchbook
libraries directory. Rename from Cosa-AVR-master to AVR.

The AVR library and examples should be found in the Arduino IDE
File>Sketchbook menu. Open the CosaISP example sketch. Select
the Cosa core by selecting one of the Cosa boards in the Tools>Board
menu.

# References

1. AVR061: STK500 Communication Protocol, Application Note,
Rev. 2525B-AVR-04/03, http://www.atmel.com/Images/doc2525.pdf

