# HF qrp directional wattmeter
A compact directional wattmeter for portable operation. Forward and reflected power is shown simultaneously with 2 LED bargraphs for easy antenna tuning.
Power sensing is done with a tandem match wound on a BN43-202 core. The microcontroller is a ATmega32u4 with USB interface for firmware uploading and serial data out.


**Things worth knowing**

1. **Firmware is incomplete**. I've been able to do basic hardware checks, but actual power measurement and calibration isn't done.
1. 
   
Attenuator table for 1% resistors
Attn. |R2 | R1, R3
------------ | ------------- | ---------
3 dB| 17.8Ω | 294Ω
6 dB| 37.4Ω | 150Ω
10 dB | 71.5Ω | 95.3Ω

[Attenuator Calc](https://www.pasternack.com/t-calculator-pi-attn.aspx)

[Schematic](https://github.com/kf4mot/qrp-wattmeter/blob/master/hardware/qrp_wattmeter.pdf)

![Complete](https://github.com/kf4mot/10mhz_distributor/blob/master/images/finished-gpsdo.jpg "Complete")

![BoardTop](https://github.com/kf4mot/10mhz_distributor/blob/master/images/board-assy-top.jpg "Board Top")

![BoardTop 3D](https://github.com/kf4mot/10mhz_distributor/blob/master/images/10mhz_distributor-3d-view.jpg "Board Top 3D")

![](https://github.com/kf4mot/10mhz_distributor/blob/master/images/scope-in-out-10mhz.jpg "Input vs. Output")

[Licensed under CERN-OHL-S V2. Julian White, 2020](https://www.ohwr.org/project/cernohl/wikis/home)
