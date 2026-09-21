### 21-9

From all of the work that I can do in this project, I really wanted to make the schematic. It's a relatively new yet a familiar process, I love how intrigued it is, when you do the connections and try to optimize the space and how clear it is, and also I have some small experience with KiCad so it was easy to start working from the beginning. The bill of material wasn't my own mission, yet I helped in it a little bit. As our goal was to create a controller with physical controls and similar to professional ones, it was actually a last minute idea that came to me and my teammate yahia at the same time, so we had to do it.

---

I had multiple problems that involved different solutions even before I started  actually working. My friend decided theta Teensy 4.1 MCU is going to be te best for our use case, as it was used in different audio and music based projects. Having next to zero experience I was struck when I didn't find the symbol for the Teensy in the KiCad default symbol editor. I want on a ([docuemented][https://lapse.hackclub.com/timelapse/hXlyyBR2OCXZ]) run that was resolved by me finding about KiCad symbol libraries, and that I can find any symbol by examining open source, user made symbols, a one that was very useful was [this one][(https://github.com/blackketter/teensy.pretty)] which held the entire library for the Teensy. Also I had 2 options which was either using one large schematic sheets, at the beginning, I found that using multiple schematics is confusing, so I chose the large one, but after working for a while, the sheet was crowded that I had to use multiple ones.

---
I analyzed the BoM, looking at how many buttons, LEDs and everything we need, which helped me plan the "pin assignment", it is summed up in this table:
| Teensy pins | function |
| ------ | ----- |
| 0-6  | Button matrix rows |
| 7-12 | Button matrix columns |
|14 | MUX 1 |
| 15 | MUX2 |
|16-23 | four EC11 encoders |
|24-27 | 2 JOG wheels |
| 28 | LED Data |
| 29 | Button Matrix column |
|36 - 39 | MUX select |
| 3 | power stuff |
 
 ---
 So I had some (13) free pins, as it was related to onboarding.
 ---
 While making the schematic I used net-based connections, which are about using net labels rather than actually connecting the pins. That meant I could connect modules that were at opposite sides of the sheet.
 ---
 For the power section, it began by making a two-pin connector, it was made for external regulated 5V supply. I of course added capacitors for power filtering  and decoupling, as these errors could be fatal to the whole thing.

The controller has ore analog controls than the teensy has convenient analog inputs. Thus I had to use a technique called **multiplexing**, it is about running energy through a grid but only lighting one row at a time, if we had to make multiple rows light at once we would flicker them so fast that the eye won't notice.
To apply this without complex circuits I used analog multiplexers, I looked for multiple options but the 16-channel CD74HC4067.

---
MOst of the controls and inputs are based on potentiometers, mainly rotary and slide ones, these potents connected to the multiplexer channels trough the center correction or the wiper. While the common output goes to the Teensy analog input, of course capacitors were added for filtering.

Now, remember my example for how grids optimized the energy, this goes the same for a grid of buttons. thus, I used a 7x7 button matrix for all the button controls.

Each button received its own 1N4148 diode, these diodes helped prevent unwanted electrical paths, commonly called ghosting, when multiple inputs are registered.

The matrix positions were based on actual controller functions.
with these buttons including:
SYNC, PLAY, CUE, LOOP IN, LOOP OUT, LOOP ON, HOT CUE, PAD FX, BEAT JUMP, SAMPLER, MIC ON, FX ON, SMART Fader Auto, Beat FX +/-
Performance pads.

---

I used rotary encoders like the EC11 (four of them) to control some stuff like loops or FX Selection, and the teensy supported internal pull-ups for these ones which is nice.

---

Of course, there isn't a DJ without jog wheels, They were independent, with their own power and quartet control,

There were 25 addressable RGB LEDs, which are necessary for any good looking DJ. These indicate states, I had to get them their own bus buffer, which was a pain in the ass, For some reason the Symbol for the SN74AHCT 125, it was some weird triangle logic thingy and I hat to scour githubs to find the correct thing, which was even legacy (.lib).

But at last, I was able to add it and connect it to the system. The purpose of it is to translate the 3.3V to 5V logic signal. this completed the LED data interface.

I connected it to the LEDs in a daisy chain (or more morbidly a human centipede)

---
 That's all for now regarding the schematic.

---
I worked for a little on some other miscellaneous stuff, like the BoM by adding control caps and though about making a zine, brainstorming with my teammate.

---
After remembering ow stupid I am and that there is something called ERC in KiCad and found several problems with the old one, making it obsolete.
From stupid problems such as duplicate reference (U2) and shorting a 3.3V pin to GND in Teensy, to much more bigger problems such as not using global labels which disconnected all the sheets from each other, making them completely ineffective, and swapping the ground and logic supply for the entire LED grid. I also added more coupling and filtering to make this circuit more resembling to real life.

---
A final change for today, I replaced the rotary encoders, for the jog, with magnetic rotary position sensors which will increase efficiency. I also replaced the Teensy 4.0 in the schem with 4.1, I used 4.0 initially because it looked simpler.

---
Journal Links:
https://lapse.hackclub.com/timelapse/9HSuw6ijgOAE
https://lapse.hackclub.com/timelapse/OjnOfFxcyOtB
https://lapse.hackclub.com/timelapse/4eUOfzpiVSXv
https://lapse.hackclub.com/timelapse/dJgap3DlKfkE
https://lapse.hackclub.com/timelapse/16tVSgQC2hcQ
https://lapse.hackclub.com/timelapse/FWIT91Rc2bJZ
https://lapse.hackclub.com/timelapse/ID_0dAGPpfu-
https://lapse.hackclub.com/timelapse/Rr1lFko1LJV_
https://lapse.hackclub.com/timelapse/GRKJxnAV0saB
https://lapse.hackclub.com/timelapse/HdR1McedKOW6
https://lapse.hackclub.com/timelapse/hXlyyBR2OCXZ
