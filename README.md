# Explotary-data-analysis-
Exploring MOSFET Transistor characteristics using dataset collected from advanced circuit simulators. This dataset is collected using advanced micro-electronics simulator called Spectre Provided by Cadence. The device used in this analysis is BSIM3 models for a typical 180-nm CMOS process. 

Key Findings: 

Interestingly, PMOS devices output current has opposite polarity to NMOS devices. This is an expected behaviour regarding device internal strucure. What is more important though is that maximum value for NMOS current roughly about 3 to 4 times corresponding PMOS value. This is due to the fact that electrons mobility to conduct current is about 3-4 times holes mobility which are the underhood mechanisms of conducting current in both NMOS, PMOS devices respectively.

𝑔𝑚 increase linearly in case of long channel for both NMOS, PMOS becasue Mosfet in pinch-off saturation resulting in quadratic relationship between ID, VGS. Taking the first derivative yielding a linear transconductance in this case. In short channel device NMOS exihibits velocity saturation effect resulting in linearizing current against VGS which yield constant transconductance against VGS.
