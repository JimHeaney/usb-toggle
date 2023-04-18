# USB Toggle

## Summary
Every day, we interact with dozens, if not hundreds, of USB-powered devices. Interacting with these in an Arduino or other hobbyist electronics project, though, can be difficult. Therefore, I developed the USB Toggle, an easy inline breakout board that allows you to control the power going to a USB from a host of other devices.

The USB Toggle interrupts the VBUS rail of the USB port, preserving the ground connection and signal lines. This allows for a USB device to be seperated from power, such as to run on its own internal batteries, but still communicate with the host computer. On this VBUS rail, USB compliant bulk capacitance is added to ensure proper device operaiton.

The toggle signal for the power, internally pulled to the ON position, is handled through an optocoupler. This allows for the device toggling the USB port to be fully isolated from the USB device, and also allows the switch to be actuated with devices operating on a very wide voltage range. Signals as low as 1.2v (Theoretical Value, Testing Pending) can be used to turn off the switch, and signals as high as 24v (Theoretical Value, Testing Pending) can be used without any additional components. This enables direct interfacing with hgher-voltage and/or noiser voltage sources, such as a car's electrical system. 

In addition to acting as a toggle switch, the USB Toggle has an optional current limiter. By default, the module limits current to 500mA. With an external jumper, this can be increased to 1A, or a programming resistor can be used to set a specific current limit.

### More information can be found on the [GitHub Wiki](https://github.com/JimHeaney/usb-toggle/wiki).


## Current Release
There are no stable versions for release. The latest WIP is Version 1.1

## Current State
Version 1.1 is currently in testing.

## Instructions & Further Documentation
[See the wiki on GitHub!](https://github.com/JimHeaney/usb-toggle/wiki) 

## Photos & Media
Coming Soon!

## Support Me
You can buy me a coffee [here](https://www.buymeacoffee.com/jimheaney)!

## License
This project is licensed under the Creative Commons 4.0 Attribution-NonCommercial-ShareAlike. For more information, click [here](https://creativecommons.org/licenses/by-nc-sa/4.0/).

If you are interested in using this project under a different license (e.g. for commercial use), please contact me. 

