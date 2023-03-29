Arduino Shield to control the BuckPuck High Power LEDs driver 3023-D-E-700 for optogenetic stimulation

based on :

<img width="755" alt="image" src="https://user-images.githubusercontent.com/120011964/228504280-018073b1-df81-4f12-a93a-2833953bc28e.png">

Supplementary Figure 1, (e) Electric circuit diagram for the LED controller. This circuit was built on a custom Arduino shield. With the Arduino program (downloadable from the online version of this paper), this electric circuit controls high power LEDs. Intensity, pulse width, pulse frequency, length of pulse train, and the number of and interval between repeated pulse trains are controllable for up to 8 of 700 mA LEDs in parallel.
nagaki, H., Jung, Y., Hoopfer, E. et al. Optogenetic control of Drosophila using a red-shifted channelrhodopsin reveals experience-dependent influences on courtship. Nat Methods 11, 325–332 (2014). https://doi.org/10.1038/nmeth.2765


Components: 
PNP transistor : DXT3906-13 (SOT-89-3)

Diodes : VS-20L15TSTRL-M3 (TO-263AB)

IR LED : SFH 4050-Z (0603)

Resistors and capacitors : 100Ohm, 1KOhm, 1uF (1206)


v1: 
SRM20 + oven at 140/60/150/120 + drilling of 1.1, rivets of 0.8mm 
The isolation traces are very thin, and the thermal pad of the diodes is too small. It is impossible to solder the diodes.
![image](https://user-images.githubusercontent.com/120011964/228507912-acc39ccc-b89b-4222-9b2f-12867a87efda.png)
![image](https://user-images.githubusercontent.com/120011964/228507999-b2427315-cd98-4dab-90a0-909c78b09bbc.png)

v1.1:
Isolation traces are doubled, forced isolation between pads, and additional isolation contour around pads. 
The pads are bigger. The components can be soldered easily.
But the dircuit does not work. The leds are on all the time. I don't know if it comes from the circuit itself or from the power supply that drops at 3V all the time (should stay at 24V).
![image](https://user-images.githubusercontent.com/120011964/228508407-90aee28e-523c-471e-9a29-cec8d79798d2.png)
![image](https://user-images.githubusercontent.com/120011964/228508467-3fca4303-45b1-4061-844e-4adcda2f4ffa.png)

