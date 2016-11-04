##\*uino-328th

The \*uino-328th was designed for my son Mathew. As a mostly though-hole design, it should be easy to assemble even for a beginner.  The only surface mount component is the micro USB connector. Personally I much prefer micro USB over the full sixed or mini connector. Unfortunately I was unable to find a through-hole micro USB.  Having the one surface mounted component was a compromise I was willing to take.

The board includes a USB serial bridge based on the PIC16F1454.  Not only is the PIC16F1454 available as a 14 pin though-hole device, it is also considerably less expensive then an ATmega8U2, for example.  

Initially I intend on using the [jgeisler0303/PIC16F1454_USB2Serial](https://github.com/jgeisler0303/PIC16F1454_USB2Serial)  firmware, but ultimately I hope to use the Open Source [signal11/m-stack](https://github.com/signal11/m-stack) as USB serial brdiger firmware.

The \*uino-328th is intended to operate at 3.3V.  There are two possible clock sources for the ATmega328P, a dedicated resonator, or the clock output of the PIC16F1454.

###Important Note

PCB have been ordered from SeeedStudio FusionPCB service. There is no working sample yet.

###Licensing

This work is licensed under a Creative Commons Attribution-ShareAlike 3.0 Unported License, CC BY-SA.

You are free to copy, distribute and transmit the work. You must attribute the work in the manner specified by the author or licensor (but not in any way that suggests that they endorse you or your use of the work). you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.  

Please refer to [http://creativecommons.org/licenses/by-sa/3.0/] for the license.

###Credit

The *uino-328th is derived from previous work done by:

- The Frienduino [jgeisler0303/Frienduino](https://github.com/jgeisler0303/Frienduino)
- The [Innovation Board](http://make.unl.edu/innovation-board/)
