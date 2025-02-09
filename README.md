# Digirig-Lite : USB Radio Interface

# Original design
The original design by Softcomplex can be found [here](https://github.com/softcomplex/Digirig-Lite).

# Why forking the original design?
1. Improve noise immunity both on USB and on HT-side
2. Improve power integrity
3. Replacing the Digirig 3.5mm pinout by the [NucleoTNC](https://mobilinkd.s3.amazonaws.com/TNC4/MobilinkdTNC4.pdf) and [Unsigned.io OpenModem](https://raw.githubusercontent.com/markqvist/OpenModem/master/documentation/OpenModem_Manual.pdf) pinout.
4. Using aluminium enclosure instead of plastic, because it's easier to get.
5. Adding LEDs to show TX and RX status.
6. Converting the design from KiCad to Altium, because that's my preferred PCB design software.
7. Add assembly option to use analog audio instead of digital audio over USB.  That will allow you to use the analog audio port from your laptop or desktop computer to connect to the radio.

# Use case
Providing a USB interface for a HT or mobile radio to connect to a computer for digital modes like APRS, Packet Radio, etc.
This device doesn't provide CAT control, only audio in/out and PTT.

# Commercial
I have no intention of selling these devices.  All the design data will be made open source which will allow others to recreate it without too much effort or cost.


