---
Title: "218-DJ-Controller 3d Design"
Author: "Mohamed Assem"
Description: "A DIY DJ controller"
Created_at: "2026-09-20"
---

# Septemper 20 : 
total time spent 11.1 hrs <br>

lapse links: part1: https://lapse.hackclub.com/timelapse/nAk_ChLudF3S <br>
part 2 : https://lapse.hackclub.com/timelapse/eGmrk4pUCh6i

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

then the rotary & slider potentiometers to the faders of the volume and these stuff but for the jog wheels we used the rotary encoders that can rotate 360 degrees wihtout any specific range like the rotary potentiometer.
WS2812 whcih is a led module that can be controlled by the MCU controlling the light inetindty and colors so it was actully pretty expensive but i sac this to this nice try.
used a wall adapter 5 v as the main Power supply unit to the DJ as it will not be enough connecting it by usb to laptob. also used a bearing that will be responsible to the rotation of the jog wheels as it offer frictionless motion. some wires and breadboard to help in the connection of all the project. right now I'm tryning to decrease the cost and search for extra materials we will need. and here is the link of excel sheet : https://docs.google.com/spreadsheets/d/1D9nlrNGDWYnSP95DjBncR3g8EgScZhrTWujonI9YDiM/edit?usp=sharing
each element written beside it the price in usd dollars and has the link to the website. Then the main body of the DJ will be made of acrlyic as if we will print it it will be very expansive and hard to find some printers in Egypt with this same size unless cutting it into many parts so using acrylic is a good choice although I didn't make each face to be alone its just like a foldable box. so  how will be used in terms of the acrylic by heat will lean it and make the acrylic bends and make different degrees, so i mad a 3 min diagram to the dimensions on the painter to visualize all of it. <br><br><br>
<img width="565" height="212" alt="image" src="https://github.com/user-attachments/assets/1b932c82-0d62-458b-bb5b-3519f2a8de5c" />
<br><br><br>
so an example for the acrylic rotation i've made an acrylic sheet to make like a vortex motion to the water <br><br><br>
<img width="488" height="318" alt="image" src="https://github.com/user-attachments/assets/bf5f0477-0fe1-4aa1-a050-b89def0a4605" />
<br><br><br>
this was made by nearing a hot flame to the acrylic then leave it to cool done after reshaping it the acrylic sheet will be 6mm thickness and cut on a local cnc router machine. I designed it on onshape with dimension of 500*290 mm for the whole project then i started to draw the buttons and faders based on a 2D image to keep everything in the correct position and the same ratio then after drawing a part i used the mirror entities to make sure it be centered and balanced all the shapes ranged between 17 to 30 mm in their dimensions, which is based on the potentiometers and the other things so after adding like 15 rotary potentiometer and 4 slide potentiometer. <br><br><br>
<img width="626" height="377" alt="Screenshot 2026-09-20 233505" src="https://github.com/user-attachments/assets/a4f6dfe8-2834-4d7b-b401-c36d389c8ba2" /><br><br><br>

and at the end of this design I just get the drawing file and exported it into dxf file, at first i was afraid from the spaces between each other but i relized that it will be relative the only factor is the opening is equal to the switch or not so i manged to make all of them measured and aligned together <br><br><br>
<img width="1015" height="636" alt="image" src="https://github.com/user-attachments/assets/42b21515-b74e-47b5-b3a0-50f6ce4aae30" /> <br> <br><br>
then at the final edit i added opening to the sockets of the female microphone/AUX also the power supply dc plug female and last thing to have a 2 usb ports to be easily connected to laptop and a speaker if wanted  
<br><br><br>
<img width="777" height="400" alt="image" src="https://github.com/user-attachments/assets/adb07817-fb2c-451e-a5aa-34b8b3a3ebba" /> <br><br><br>
then i started to optimize in the BOM File and decrease the amount of money was not that much but in next version can be reduced. and searched for the caps and performance pads instead of printing it as it will be much more expensive. havenot found alot and the only store found in it didnot have that much sizes so i just chosen the nearest one and I think it will be enough. <br><br><br>
<img width="607" height="366" alt="image" src="https://github.com/user-attachments/assets/4b7acca9-3326-476b-a8db-a3afaf95c1ad" /> <br><br><br>

also i've added all the ports we will need AUX 2 usb ports and the dc plug for the 5volt adapter for this version very good we still have to work on the firmware and finalize the assets like stls that 'll be printed and the dimensions are correct.
