# HF qrp directional wattmeter
A compact directional wattmeter for portable operation. Forward and reflected power is shown simultaneously for easy antenna tuning.
Power sensing is done with a tandem match wound on a BN43-202 core. The microcontroller is a ATmega32u4.

**Things worth knowing**

1. Schematic and BOM show The Qorvo TQP369182 as the MMIC. TQP369180 was actually used on the first board. The extra gain of the 182 seems unnecessary when driven with a 5V square wave and it may cause oscillation based on past experience. Bias resistors remain at 91Ω. Upgrade at your own risk and let me know how it goes if you try it or any other MMIC.
1. P
   
Attenuator table for 1% resistors
Attn. |R2 | R1, R3
------------ | ------------- | ---------
3 dB| 17.8Ω | 294Ω
6 dB| 37.4Ω | 150Ω
10 dB | 71.5Ω | 95.3Ω

[Attenuator Calc](https://www.pasternack.com/t-calculator-pi-attn.aspx)

[Schematic](https://github.com/kf4mot/10mhz_distributor/blob/master/hardware/10mhz_distributor_r1.pdf)

[Licensed under CERN-OHL-S V2. Julian White, 2020](https://www.ohwr.org/project/cernohl/wikis/home)

![Complete](https://github.com/kf4mot/10mhz_distributor/blob/master/images/finished-gpsdo.jpg "Complete")

![BoardTop](https://github.com/kf4mot/10mhz_distributor/blob/master/images/board-assy-top.jpg "Board Top")

![BoardTop 3D](https://github.com/kf4mot/10mhz_distributor/blob/master/images/10mhz_distributor-3d-view.jpg "Board Top 3D")

![](https://github.com/kf4mot/10mhz_distributor/blob/master/images/scope-in-out-10mhz.jpg "Input vs. Output")
