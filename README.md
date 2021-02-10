<!-- Please do not change this logo with link -->
[![MCHP](images/microchip.png)](https://www.microchip.com)

# Touch Example using QT7 and AVR128DA48 Curiosity Nano

This example demonstrates touch application on AVR128DA48 Curiosity Nano, Curiosity Nano Touch Adapter Kit and QT7 extension board. The example project provides user feedback to touch using the QT7 onboard LEDS, and via a PC running Microchip MPLAB® Data Visualizer. 

## Related Documentation

- AVR128DA48 Curiosity Nano user guide [(DS50002971B)](https://ww1.microchip.com/downloads/en/DeviceDoc/AVR128DA48-Curiosity-Nano-UG-DS50002971B.pdf)
- Curiosity Nano Touch Adapter Kit user guide [(DS40002191A)](https://ww1.microchip.com/downloads/en/DeviceDoc/40002191A.pdf)
- QT7 Xplained Pro user guide [(DS50002725A)](https://ww1.microchip.com/downloads/en/DeviceDoc/QT7%20Xplained%20Pro%20User%20Guide%2050002725A.pdf)
- MPLAB® Data Visualizer user guide [(Data Visualizer user guide)](https://www.microchip.com/content/dam/mchp/documents/DEV/ProductDocuments/UserGuides/MPLAB_Data_Visualizer_50003001A.pdf)

## Software Used

- Microchip Studio 7 7.0.2542 or later [(microchip-studio-for-avr-and-sam-devices)](https://www.microchip.com/en-us/development-tools-tools-and-software/microchip-studio-for-avr-and-sam-devices)
- AVR-GCC 3.62 or newer toolchain [(Toolchains for AVR)](https://www.microchip.com/en-us/development-tools-tools-and-software/gcc-compilers-avr-and-arm)
- AVR-Dx_DFP (1.6.76) or later [(packs.download.microchip.com)](https://packs.download.microchip.com/)
- MPLAB® Data Visualizer [(Data Visualizer)](https://www.microchip.com/en-us/development-tools-tools-and-software/embedded-software-center/mplab-data-visualizer)

## Hardware Used

- AVR128DA48 Curiosity Nano [(DM164151)](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/DM164151)
- Curiosity Nano Touch Adapter Kit [(AC80T88A)](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/AC80T88A)
- QT7 Xplained Pro Extension Kit [(atqt7-xpro)](https://www.microchip.com/developmenttools/ProductDetails/atqt7-xpro)

## Setup

1. Connect QT7 to Curiosity Nano Touch Adapter Kit (EXT1).
2. Connect Curiosity Nano Touch Adapter Kit to AVR128DA48 Curiosity Nano.
3. Connect PC to the MCU board Debug USB port.

![data-visualizer](images/data-visualizer.png)


1. Open the .atsln file in Microchip Studio.
2. Build the solution and program the device.
3. Open MPLAB® Data Visualizer and configure Serial Port Control Panel (above):
   - Autodetect Protocols = true 
   - Show Config path = true
4. Connect.

![datastreamer-folder](images/datastreamer-folder.png)

5. When prompted, navigate to "\avr128da48-qt7-touch-example-studio\qtouch\datastreamer" and select folder (above)

## Summary

This example has illustrated how to use the AVR128DA48 Curiosity Nano with QT7 extension board.
