# HF QRP directional wattmeter
A compact directional wattmeter for portable operation. Forward and reflected power is shown simultaneously with 2 LED bargraphs for easy antenna tuning.
Power sensing is done with a tandem match wound on a BN43-202 core. The microcontroller is a ATmega32u4 with USB interface for firmware uploading and serial data out (PC logging, debugging, etc).

[Created with KiCAD ver. 5.0.2](https://kicad-pcb.org)

**Things worth knowing**

1. **Firmware is incomplete**. I've been able to do basic hardware checks, but actual power measurement and calibration isn't done.
1. Diodes D1-2, D4-5, and D6-7 are for providing forward bias to the bridge to improve linearity and remove zero offset. 2 devices are shown in each position to give the builder the option of a PTH or SMD package.
1. Op-amps U1 and U2 have PTH and SMD package footprints.
1. The board was designed to fit the Polycase JB-35 enclosure. **Untested** https://www.polycase.com/jb-35 https://github.com/kf4mot/qrp-wattmeter/blob/master/docs/14531129045666870.pdf 

[Licensed under CERN-OHL-S V2. Julian White, 2020](https://www.ohwr.org/project/cernohl/wikis/home)

[Schematic](https://github.com/kf4mot/qrp-wattmeter/blob/master/hardware/qrp_wattmeter.pdf)

![Complete](https://github.com/kf4mot/qrp-wattmeter/blob/master/images/watt-i-know-top.jpg "Board Top")

![BoardTop](https://github.com/kf4mot/qrp-wattmeter/blob/master/images/watt-i-know-btm.jpg "Board Bottom")

![BoardTop 3D](https://github.com/kf4mot/qrp-wattmeter/blob/master/images/watt-i-know-front.jpg "Board Front")
