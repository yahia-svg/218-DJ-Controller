# 218-DJ-Controller
A fully DIY DJ controller. 

**Introduction**
---
`A brief intro about the project and the repository.`
<br>
This is a fully DIY DJ Controller. This repository includes the general 3D design of the DJ controller, some unique independent components, the firmware that runs the device, and the schematic showing the circuit connections that power the DJ Controller. 
**Note:** This project is not complete yet. As a result, you may find missing components and designs still under development.

**Project Status**
---
`This section describes the status of the project and the progress made so far, as it is yet to be completed.`
- The project is still under development; the current version only includes the initial designs and operating systems.
- As expected, a working prototype has not been built
- Currently, the full 3D design and the schematic diagram.


**Materials Table**
---
`This section has a table including all the data about the electronic components needed for building this DJ Controller. The table lists the number of pieces needed for each component (quantity); the type of component/actuator (Type); the exact model name for the component (Module); the total amount of money spent to buy the full quantity of the component (price) aka if we're buying 20 buttons, the "price" is the total money needed to buy all 20 buttons; and finally the link address where you can buy this exact component online (Link).`
| Quantity | Type | Module | Price | Link |
|----------|------|:-------:|------|------|
|1|Microcontroller|Teensy 4.1 Microcontroller|57 USD|https://devboardsmarket.com/products/teensy-4-1|
|2|Multiplixer|74HC4067 16-Channel Analog Digital Multiplexer|3 USD|https://www.ram-e-shop.com/shop/kit-multiplexer-744067-74hc4067-16-channel-analog-digital-multiplexer-breakout-board-8009|
|15|Rotary Potentiometer|R0902N rotary potentiometer 10kohm|5 USD|https://ar.aliexpress.com/item/1005007976451892.html?gatewayAdapt=glo2ara|
|6|Slide Potentiometer|b103 rotary potentiometer 10kohm|6 USD|https://microohm-eg.com/linear-slide-pot-10k-103-mixer-style-88-mm-body-3-electrical-pins-2-mounting-lugs/|
|4|Rotary Encoder|EC11 Rotary Encoder|2 USD|https://www.ram-e-shop.com/shop/pot-ec11-rotary-5pin-20mm-ec11-rotary-encoder-with-push-button-switch-5pin-20mm-silver-9624?srsltid=AU7gw4X7FVfdkLHMxx39-0TqMu4-kT5Zp2LIeBuxGGReUEAjG0sGj-GZ|
|2|Bearing|608ZZ Shielded Miniature Ball Bearing|0.5 USD|https://ampere-electronics.com/product/608zz-shielded-miniature-ball-bearing-8x22x7mm/|
|20|LEDs|NeoPixel 1-bit WS2812 5050 RGB LED Driver|13.4 USD|https://www.ram-e-shop.com/shop/kit-ws2812-single-neopixel-1-bit-ws2812-5050-rgb-led-driver-development-board-8258?srsltid=AU7gw4VgLywzAkNsH-dn0ZJxllWlD6Ye3m8D_xr_mt_QzIFbYNpsm9BW|
|50|Resistors|10 kohm Carbon Resistance 1/4W|0.5 USD|https://www.ram-e-shop.com/shop/carbon-resistance-1-4w-price-per-4-resistors-9506#attr=314|
|50|Resistors|220 Carbon Resistance 1/4W|0.5 USD|https://www.ram-e-shop.com/shop/carbon-resistance-1-4w-price-per-4-resistors-9506#attr=314|
|20|Capacitor|Ceramic Capacitor 100nF - 400V (104J400V) Disc 10mm|3 USD|https://ampere-electronics.com/product/ceramic-capacitor-100nf-400v-104j400v-disc-10mm/|
|10|Capacitor|Ceramic Capacitor 1uF - 630v (105J630V) Disc 20mm|1.5 USD|https://ampere-electronics.com/product/ceramic-capacitor-1uf-630v-105j630v-disc-20mm/|
|5|Capacitor|Electrolytic Capacitor 100uF - 50V|0.1 USD|https://ampere-electronics.com/product/electrolytic-capacitor-100uf-50v/|
|5|Capacitor|Electrolytic Capacitor 100uF - 50V|0.1 USD|https://ampere-electronics.com/product/electrolytic-capacitor-10uf-50v/|
|1|Power Supply|Wall Power Adapter 5Vdc 3A|5 USD|https://www.ram-e-shop.com/shop/rpi4-adaptor-onoff-wall-power-adapter-usb-type-c-output-5vdc-3a-with-on-off-switch-7840|
|4|Wires|2mm Electric Copper Wire 11 AWG, 1 Meter ElSewedy Electric|3 USD|https://fluxelectronix.com/shop/electric-copper-wire-2mm-15-awg-1-meter-el-sewedy-electric/|
|1|Screws|Bolt +M3x08 mm (100 Screws/bag)|1 USD|https://www.ram-e-shop.com/shop/nail-3x08mm-bolt-m3x08-mm-100-screws-bag-6546|
|2|Connector|Pin Header Male 1x40|0.1 USD|https://www.ram-e-shop.com/shop/ph1-1x40-male-ph1-pin-header-male-1x40-straight-2-54mm-5808|
|2|...|Breadboard 830|1.2 USD|https://www.ram-e-shop.com/shop/bb01-bread-board-bb-01-breadboard-830-tie-point-6143|
|43|Buttons|DS-430 Push Button Momentary Switch Square Shape 2 Pin|4 USD|https://makerselectronics.com/product/ds-430-push-button-momentary-switch-square-shape-2-pin/|
|1|Connector|Dupont Crimp Connector Kit - 310 Pcs|2.5 USD|https://fluxelectronix.com/shop/dupont-crimp-connector-kit-310pcs/|
|1|Socket|Audio Microphone Female Socket|0.1 USD|https://lampatronics.com/product/audio-microphone-female-socket-jack-japan-6-35mm-6pin-stereo-pj-609?srsltid=AU7gw4XiA7R56UENAIxl4PDR0Mzh5HVzqPs_Ftcq0OPw0dya_bEFeapk|
|1|Switch|Metal Switch On/Off 12mm|1.5 USD|https://lampatronics.com/product/audio-microphone-female-socket-jack-japan-6-35mm-6pin-stereo-pj-609?srsltid=AU7gw4XiA7R56UENAIxl4PDR0Mzh5HVzqPs_Ftcq0OPw0dya_bEFeapk|
|1|Cable|Micro USB Cable for Arduino|0.5 USD|https://fluxelectronix.com/shop/micro-usb-cable-for-arduino-30cm-length/|
|2|Connector|Female USB Connector Type(A) DIP|0.1 USD|https://fluxelectronix.com/shop/female-usb-connector-type-a-dip/|
|1|Connector|Female DC Power Plug to 2-Pin|0.1 USD|https://fluxelectronix.com/shop/female-dc-power-plug-to-2-pin-screw-terminal/|
|1|Connector|AUX 3.5mm Female Jack|0.1 USD|https://makerselectronics.com/product/aux-3-5mm-female-jack-solder-connector/|
|2|Magnetic Rotary Position|as5047d|14 USD|https://www.alibaba.com/product-detail/AS5047D-AS5047P-Encoder-Adapter-Board-SimpleFOC_60824124421.html?xp=CjwKCAjwiL7VBhA-EiwAhZi9EPFAbgCuHDgqsBXgO3WVVnwhHE37JqkiqNlWaf1b_Q_aOUigJJRrVBoCLakQAvD_BwEsMbeanHAIqwcTEART57S-&cps_sk=q5c7g489&bm=cps&src=saf&pid=ga2dsa&tp1=CjwKCAjwiL7VBhA-EiwAhZi9EPFAbgCuHDgqsBXgO3WVVnwhHE37JqkiqNlWaf1b_Q_aOUigJJRrVBoCLakQAvD_BwE&gad_source=1&gad_campaignid=24185825227&gbraid=0AAAABD4gRWE6hLx6Puv_ZA-zHFVsF1zu0&gclid=CjwKCAjwiL7VBhA-EiwAhZi9EPFAbgCuHDgqsBXgO3WVVnwhHE37JqkiqNlWaf1b_Q_aOUigJJRrVBoCLakQAvD_BwE|
**Extra Services Used**
---
`This section mentions the extra services or technologies that you will need to utilize to build the project and how/why/for what you will use them.`
| Type | Usage |
|------|-------|
|3D printing|Joy Wheels and Performance Pads' Caps|
|CNC Cutting|Cutting the acrylic to form the body of the DJ ControllerZ

---


**Mechanical Analysis**
---
`This section showcases the 3D design of the whole device, allowing you to accurately analyze the mechanical sid of the project.`
<img width="1095" height="585" alt="image" src="https://github.com/user-attachments/assets/10468b47-021e-4887-8fba-e73ebc577483" />
This is the 3D model visualizing the design for the DJ Controller. The design showcases the different pads, potentiometers, and encoders.

**Electrical Analysis**
---
`This section includes a detailed analysis of the electrical side of the project through the multitude of schematic designs provided in the section, showcasing the wiring of the circuit and component placement (in the context of circuit connections`
<img width="1130" height="808" alt="image" src="https://github.com/user-attachments/assets/01981f25-0b0d-4481-8633-de892ff26785" />
This shows the schematic diagram for the circuit powering the DJ Controller

<img width="1136" height="802" alt="image" src="https://github.com/user-attachments/assets/9ee6462e-07c2-493b-9d94-f34ec5ee5ab1" />
This shows the schematic diagram for the buttons used in the circuit powering the DJ Controller.

<img width="1131" height="805" alt="image" src="https://github.com/user-attachments/assets/26e867d9-5cb9-4ef4-810f-3b2609e8cbd2" />
This shows the schematic diagram for the LEDs used in the circuit powering the DJ Controller.

--- 

**Component Analysis**
---
`This section consists of a table that showcases the unique components we used for our project (components); the unique feature available in our project that these components bring (function); and how these components operate or what process they follow to provide these unique features.`
| Component | Function | Operation|
|-----------|----------|----------|
|Jog Wheel|Mainly used to control playback|Rotation sends movement data|
|Tempo Fader|Can change track speed + BPM|Moving the slide controls the tempo percentage sent to the software|
|SYNC|Used to match decks easily and automatically|Software adjusts deck based on BPM Analysis|
|Play/Pause|Starts or stops playback|Rotation sends movement data|
|CUE|Sets a cue point and allows return to that point|Button controls sofware actions such as abilities preview|
|Loop IN|Sets starting point for a loop|Marks the beggining of a loop|
|Loop OUT|Sets ending point for a loop|Marks the end of a loop|
|Loop ON/OFF|Used to activate or deactivate loops|Toggles the current loop|
|Loop Size -/+|Used to control or change loop length|Button Changes beats|
|TRIM|Able to control input level|Changes chanell gain|
|HI|Able to control high frequencies|Boosts or cuts treble|
|MID|Able to control middle frequencies|Boosts or cuts vocals|
|LOW|Able to control low frequencies|Boosts or cuts bass|
|Channel Fader|Able to control deck volume|Vertical movement changes volume for chosen channel|
|Channel CUE|Able to preview a deck through headphones|Routes deck to headphones|
|Crossfader|Used to blend both decks (deck 1 and deck 2, aka right side and left side deck)|Controls both decks|
|Master Level|Controls output|Changes final volume|
|Headphone Level|Controls volume of what is heard through headphones|Adjusts headphone volume|
|Master Mix|Controls what is heard through headphones|Assigns each section different values|
|Beat FX Select|Choose effects|Cycle through effects|
|FX Parameter|Controls Effect Intensity|Turning changes parameters for effects|
|Beat -/+|Changes effect timing|Changes effect beat|
|FX ON|Used to activate effects|Toggles the selected effect|
|Smart CFX|Used to apply combined effects|Simoltaneous change of multiple effects|
|Smart Fader|Used as a helping mechanism to automate transitions|Performs changes while transitioning between decks|
|Smart Fader AUTO|Allows automatic transition activation|Excutes Smart Fader Behavior|
|MIC INPUT|Connect Microphone|Audio enters the computer interface|
|MIC LEVEL|Microphone level|Change microphone level|
|MIC ON/OFF|Enables Microphone|Mutes microphone|
|HOT CUE|Used to store playbook points|Works with predefined positions (CUE Positions)|
|PAD FX|Operates effects from pads|Each pad is used to activate a specific effect|
|BEAT JUMP|Used to jump through tracks|Move playback forward and backward based on beat amounts|
|Sampler|Used to play samples|Utilizes stored sounds|
|Performance Pads|Allows Multifunction controls|Behavior changes with selected mode|

---

**Assembly Guide**
---
`You can think of this section as a "Methods" section. Basically, it gives a general guide on how to build this project.`
<br>
**1. Get the electronic components that you will need**
You will need to get all the electronic components that we listed in the materials table above. In addition, it is really important that you get the same number of pieces if you wish to implement this project at the same scale we did.

**2. 3D printing and CNC cutting**
After getting the electronic components, you will be missing some pieces. You will have to get some parts printed first. These are the caps used for the pads and potentiometers. Sure, you could avoid using caps at all, and with that you won't have to print any parts, but having these caps significantly changes how your device looks visually (to the better, of course). Then, it is necessary that you build the body for the controller. We chose to build it using acrylic. If you wish to do the same, then relying on CNC Cutting is the most efficient method to build that body. After cutting the Acrylic into the desired shape, you will probably need to use heating mechanisms to shape into the final required shape.

**3. Placement and Wiring**
Now, you're finally ready to start building; all the things you need are ready. What you need to do now is get the body you're using and place the electronics in their designated places/locations as per the full 3D model provided above. Then, you should start wiring and connecting all the components with the help of the schematic diagrams we provided above.


**Repo Layout**
---
`This section gives you a quick and brief walkthrough of all these files you see in the GitHub repository and what you can expect to see in each file.`
<br>
-Mohamed'sJournal.md contains Mohamed's work and contributions to the device, which include feature selection, BOM, and 3D design of the device's body.

-YAHYA'SJOURNAL.md contains Yahya's contributions, which are mainly focused on the 3D design of the main body, including multiple rendering processes.

-Michael's-Journal.md contains Michael's contributions to the project, which include the initial 2D sketch of the device and writing this README for you to read.

-Moaz's Journal contains Moaz's contributions to the project, which mainly revolve around designing the electronic circuit powering the device by drawing a schematic diagram (like the ones provided above).

-Schem is a folder within the repository that contains all the schematic-related files.

-Zine 1 and Zine 2 are two visual methods of representing the project.

-Acrylic cuts is a folder that contains the acrylic sheet cuts that will be used in the device.
**Plans for next week**
---
`This section gives a brief idea of what we plan to do and accomplish within the next week.`
- Develop firmware
- Finalize Designs for 3D-printed components
- Run final tests to make sure the device is running and operating correctly.

**Expected Project Status**
---
`This section describes the results that we expect to achieve within the time span of the next week, after fulfilling our goals/plans described in the above section (Plans for next week)`
- 3D-printed components' design: Complete
- Circuit analysis: Complete and fully operational
- Project Progress Overall: Complete
- Next Step: IRL Prototype Building


**FAQs**
---
`This section includes the answers to the most commonly discussed topics within or ouside of your main community discussion topics.`
**Why build a DIY DJ Controller?**
<br>
If you love music, it's definitely a great investment. You will get to tune, mix, and use as many effects as you want on your favourite songs/music. In addition, you can just try and explore new stuff using this new device. Now, if you don't love music, it's still really fun to just play with it and do random stuff. Also, it's really cool; just imagine how cool it would be to play DJ for your friends when they come over or just give them the opportunity to play with it for a while. It's just super fun.

**I don't have much experience building stuff. Can I still build this?**
<br>
Definitely yes. We didn't have that much experience ourselves. In fact, I think that this is my first or one of my first ever hardware/electronics projects to work on. So, to answer your question, yes, you can build this yourselves (THis is not an overly optimistic future; it's actually totally realistic.
