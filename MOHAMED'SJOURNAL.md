---
Title: "218-DJ-Controller 3d Design"
Author: "Mohamed Assem"
Description: "A DIY DJ controller"
Created_at: "2026-09-20"
---

# Septemper 20 : 

At first I had to search about every thing about these DJs that are spread around the world right now, focusing on models that are having good features with keeping the cost as a variable like DDJ FLX4.
I watched some videos explaining each button and each feature with explaining the way it works and importance. So I started to decide our DJ features taking some common features and added some like the cue button and the 16 performance pads with leds changing their intensity and colors. 
I had to document all my search in a notion file so the team can continue on it, so was documenting part by part. Documenting things like a piece of schematic diagram to a mixing module. <br><br><br>
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/80d46c3e-a6a3-469b-8dde-34c4d4933a6b" /> <br><br><br>
then started to search about same DIY projects that my help and they were pretty good start for the materials. Credits:
https://github.com/mandiclab/djc-diy <br>
https://github.com/jueta/DIY_DJ_Controller


then I had to start the BOM and started with the microo controller whcih here i used some of chat gpt to find a merchant to the teensy 4.1 in egypt as it was hard searc, as after alittle bit searching i've fornd that the teensy 4.1 is very suitable microcontroller to this project as it was espicially made for real time audio processing.<br><br><br>
<img width="475" height="312" alt="image" src="https://github.com/user-attachments/assets/40464741-adb2-4d76-9997-f8adbfbcd5d1" /> <br><br><br>
I started writing the BOM which was a little bit challenging at first to know what should be added and which module, but i knew the required things like rotary potentiometer and the slider ones by thier quantities from the 2d design imagination for it as it was too helpful to imagine the 3d designa nad the materials by thier quantines.
then i had 2 multiplexer that would connect all of this potentiometer to control it. MOst of the materials was selected from egyptian merchants to control the prices and keep it cost effecient as it is one of our goals.

then the rotary & slider potentiometers to the faders of the volume and these stuff but for the jog wheels we used the rotary encoders that can rotate 360 wihtout any specific range unlike the rotary potentiometer.
WS2812 whcih is a led module that can be controlled by the MCU controlling the light inetindty and colors so it was actully pretty expensive but i sacc this to this nice try.
used a wall adapter 5 v as the main Power supply unit to the DJ as it will not be enough connecting it by usb to laptob. also used a bearing that will be responsible to the rotation of the jog wheels as it offer frictionless motion. some wires and breadboard to help in the connection of all the project. right now I'm tryning to decrease the cost and search for extra materials we will need. and here is the link of excel sheet : https://docs.google.com/spreadsheets/d/1D9nlrNGDWYnSP95DjBncR3g8EgScZhrTWujonI9YDiM/edit?usp=sharing
each element written beside it the price in usd dollars and has the link to the website

