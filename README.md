# FASat_charlie macropad
This is a macropad in the shape of the chilean satelite FASat-CHARLIE. It has 6 keys with a rotary encoder, 16 SK6812MINI-E leds on the edges of its pcb and uses kmk firmware.

I made this macropad to help me open the websites I need for school instantly, to record as well as mute! (Since I costantly forget the keybinds for those).

## Features: 
- 16 SK6812MINI-E leds, all used for as a "glow" that the macropad emanates in the dark!
- EC11 Rotary encoder /w switch for adjusting led colors and brightness
- 6 keys
- Shape of the FASat-CHARLIE satelite

## CAD
The entire case uses 6 M3x16mm bolts and M3 headseat inserts (4mm deep). 4 are screwed from under the case and the other 2 are used to join the "flag".

The case has 3 separate 3d printed pieces. The bottom, which has a 16 degree inclination so it can face me once I lay it flat on a surface. It also has info. about the satelite on the back. 
The top exposes the pcb so the leds can be seen and has a circular hole where the buttons and rotary encoder will be. 
Lastly, the flag is just a decorative piece that contains acknowlegements.

![alt text](https://github.com/ElGOATFilipino/fasat_charlie/blob/main/Images/Full_macro.png)

Here's how it'll all fit together

![alt text](https://github.com/ElGOATFilipino/fasat_charlie/blob/main/Images/Overview.png)

*All made in Fusion 360, the model is too big so I had to compress it into a zip file.

## PCB
The pcb was made in KiCAD! I had a lot of fun using this software for my pcb, I think i'll be using it for future projects!

Schematic
![alt text](https://github.com/ElGOATFilipino/fasat_charlie/blob/main/Images/Schematic.png)

PCB (It contains a lot of errors, since the DRC thinks that the edge.cuts on the leds is not supposed to be there, but it is).
![alt text](https://github.com/ElGOATFilipino/fasat_charlie/blob/main/Images/PCB.png)

## Firmware features (not required, but still good to add!)
- Rotary encoder can adjust the brightness of leds. If the button is pressed it turn the leds red, orange, yellow, green, blue, purple, make them do a rainbow animation and finally, off. (Example: if I press the button 3 times, the leds turn green.)
- Four of the keys open Turbo.ai, Canva, Word, Google classroom. The other two start recording on my computer and mute volume.

## BOM
Here are all the parts needed to make my macropad!

- x6 MX-Style switches (Cherry)
- x6 DSA keycaps (1u)
- x6 M3x16mm SHCS bolts
- x4 M3x5x4 headseat inserts
- x16 SK6812MINI-E LEDs
- x1 EC11 Rotary Encoder
- x1 XIAO RP2040-DIP
- x1 Case (3 3d printed parts)

## Fun facts:
- It was supposed to be in the shape of the sojourner rover (which took me 2 weeks to complete), but it was to big and ugly.
- I was inspired to make it in the shape of the FASat-CHARLIE when I saw a replica of it at Santiago's National Museum of Aeronautics and space.



