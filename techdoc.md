# Notes from [CM108 Sound Fob Modifications for use with TxCR](https://www.nednet.org.uk/how_to/CM108_mod)
* No biasing on MIC-input
* 10ohm, 10µF RC filtering for AVDD
* See RB-RIM-Lite2 for IO-line filtering

# Notes from [AllScan How To - Build a High-Quality Full-Duplex AllStar Node for Under $150](https://allscan.info/docs/diy-node.php)
* [URI150-v1.11 schematic](https://allscan.info/images/URI150/URI150-v1.11-sch.png)
* USB ferrite clamp : Laird 28A0350-0B2
* HT-cable ferrite clamp : Fair-Rite 0446173951
* On power supply :  Laird 28A2029-0A2

# Pinout
TRRS – 3.5mm TRRS audio connector for Radio.
1. Tip = Speaker (audio input to TNC)
2. Ring 1 = PTT (Simplex PTT mode)
3. Ring 2 = Mic (and PTT in Multiplexed PTT mode)
4. Sleeve = GND/Common

# Enclosure
* [80x50x20mm](https://www.aliexpress.com/item/1005006828585850.html) : €1.96/pce
* [25x40x80mm](https://www.aliexpress.com/item/1005007115490142.html) : size 3, group A : €5.21/pce

# LED-indicators
It's not fully clear from the CM108B datasheet what the status of the GPIO and LEDs is.  Moreover, because of the narrow package, it's not easy to add some LEDs on the front and the back on the same PCB.  An FFC-connector will be added, allowing for great flexibility in the design of the front and back panel.

# References
1. [Online KiCad view of original Digirig-Lite design](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fsoftcomplex%2FDigirig-Lite%2Ftree%2Fmain%2Felectric)
2. [CM108 Sound Fob Modifications for use with TxCR](https://www.nednet.org.uk/how_to/CM108_mod)
3. [AllScan How To - Build a High-Quality Full-Duplex AllStar Node for Under $150](https://allscan.info/docs/diy-node.php)
4. [TK5EP: USB audio interface](https://www.egloff.eu/index.php?option=com_content&view=article&id=233:interface-audio-usb&catid=8&Itemid=1861&lang=en): describes a kill-switch circuit for the PTT, we'll not add it in this design, because the radio has it already built in.
5. [RB_RIM_Lite_v2](https://www.repeater-builder.com/products/RIM_pdfs/RB_RIM_Lite_v2.pdf)
6. [A CM108-based Allstar USB FOB](http://www.garydion.com/projects/usb_fob/) : nice picture of CM108 fob