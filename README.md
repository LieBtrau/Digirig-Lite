# Digirig-Lite

# Original design
The original design by Softcomplex can be found [here](https://github.com/softcomplex/Digirig-Lite).

# Why forking the original design?
1. Improve noise immunity both on USB and on HT-side
2. Improve power integrity
3. Replacing the Digirig 3.5mm pinout by the [NucleoTNC](https://mobilinkd.s3.amazonaws.com/TNC4/MobilinkdTNC4.pdf) and [Unsigned.io OpenModem](https://raw.githubusercontent.com/markqvist/OpenModem/master/documentation/OpenModem_Manual.pdf) pinout.
4. Using aluminium enclosure instead of plastic, because it's easier to get.
5. Adding LEDs to show TX and RX status.
6. Converting the design from KiCad to Altium, because that's my preferred PCB design software.

# Use case

# Commercial
I have no intention of selling these devices.  All the design data will be made open source which will allow others to recreate it without too much effort or cost.

# References
1. [Online KiCad view of original Digirig-Lite design](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fsoftcomplex%2FDigirig-Lite%2Ftree%2Fmain%2Felectric)
2. [CM108 Sound Fob Modifications for use with TxCR](https://www.nednet.org.uk/how_to/CM108_mod)
3. [AllScan How To - Build a High-Quality Full-Duplex AllStar Node for Under $150](https://allscan.info/docs/diy-node.php)
4. [TK5EP: USB audio interface](https://www.egloff.eu/index.php?option=com_content&view=article&id=233:interface-audio-usb&catid=8&Itemid=1861&lang=en): describes a kill-switch circuit for the PTT, we'll not add it in this design, because the radio has it already built in.
5. [RB_RIM_Lite_v2](https://www.repeater-builder.com/products/RIM_pdfs/RB_RIM_Lite_v2.pdf)
6. [A CM108-based Allstar USB FOB](http://www.garydion.com/projects/usb_fob/) : nice picture of CM108 fob

# Notes
* No biasing on MIC-input
* 10ohm, 10µF RC filtering for AVDD and DVDD
