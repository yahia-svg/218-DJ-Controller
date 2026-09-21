---
title: "218-DJ-Controller 3d Design"
author: "Yahya"
description: "A fully DIY DJ controller"
created_at: "2026-09-20"
---

# September 20: 

**total time spent 10.25 hours** <br />
[lapse](https://lapse.hackclub.com/timelapse/QtJcBVnucqxT)

Okay so first and foremost, I need to identify the Design style for this project so I gain a general understanding of how I want this project to look like. <br />
The first design style that came to my mind is a mix between 80s tech and futuristic tech because I find the mix between modern electronics and old machinery very intriguing. <br />
This kind of reminds me of the movie "back to the future" which blended 80's engineering with futuristic tech for the delorian.<br />
Actually, speaking of back to the future, I remembered the flux capacitor for the Delorian, and I could use that as the base feature for the controller and design the whole controller over that. <br /> 
<img width="1920" height="1080" alt="testconcept1" src="https://github.com/user-attachments/assets/2e7ab88f-5582-4563-a2c0-ff37c4ee6dbf" />
I made this 3d basic design on blender with a flux capacitor in the middle to better explain the concept I was talking about. <br /> 
I think it's definitely an interesting concept and I find that it looks cool, but right now it just looks super unfinished and boring<br /> 
Overall, I really like the LEDS but I'm thinking of taking more inspiration from old tech when it comes to assembly and technical features because I want to give this an accurate skeuomorphic design, so I need to familiarize myself with older even obsolete design principles <br />  

First I want to research different models of DJ controllers in order to choose the layout that I find most appealing. <br />
<img width="1208" height="642" alt="image" src="https://github.com/user-attachments/assets/6433cf19-fa4f-493a-ad5a-5bf9b016590e" />
okay so after browsing for some time I think it's best to follow the same general layout as the DDJ FLX 4 so I will base the next designs on it. <br /> 

As I was researching old tech I found this: <br />
<img width="1400" height="1068" alt="image" src="https://github.com/user-attachments/assets/b971b3c4-21b2-410b-ba98-6c5903f01583" />
the speaker design really caught my eye, I will probably add horizontal lines like that around the jog wheels <br />
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/848f3f08-069a-4c38-9e07-6c075e933cb5" />
I also found this old boombox and I really like how the design almost entirely consists of square panels and slightly beveled cubes so I will also probably try to emulate this in my design <br />

For the color palette I want a cream color an orange color and a light grey and a light blue for the led's and more modern features <br />
<img width="1221" height="427" alt="image" src="https://github.com/user-attachments/assets/4214f0a3-ae67-404e-a29f-3a43d46ebc91" />
I found this color palette on [colorany](https://colorany.com/color-palettes/retro-computer-color-palettes/) It's inspired by Windows 3.1 Color palette <br />

Texture is also very important <br />

<img width="974" height="595" alt="image" src="https://github.com/user-attachments/assets/fd347b7e-aa62-43ed-a20e-70f3195e1c6c" />

based on this chart I think I will use fuzzy skin 0.1 mm thickness with classic noise <br />

i will now draw a couple of very basic sketches on krita that incorporate these design features based on this layout made by my teammate michael <br />

So my teammate michael made this layout initially:
<img width="1022" height="595" alt="Screenshot 2026-09-20 173943" src="https://github.com/user-attachments/assets/572c5df2-d044-433e-9b39-4ad202d6b43a" />
However, I thought that the middle section was very messy so i started first with the part on the left and i made a very basic sketch to help imagine what the 3d model would look like <img width="1140" height="710" alt="image" src="https://github.com/user-attachments/assets/ccccf2be-09dc-416f-99f8-8242684ad182" /> I didn't finish it though because I felt like I could dive into the 3d straight away and save time so I made this:
<img width="626" height="669" alt="Screenshot 2026-09-20 210952" src="https://github.com/user-attachments/assets/589d2120-ed31-4744-bfb1-21f642212753" />
I tried to really focus on having many squares so I turned the round on/off and cue buttons to squares and i placed them slightly outside the area where the hot cues were. I also split the jog wheel into two wheels a large inner wheel and a more precise outer wheel and i added these extrusions on the sides so that it would be easier to move for precise movements.
I also used the same modular design from the forementioned boombox where each set of buttons are in their own square island. and I created 3 main islands. and for this to be just a little more futuristic I decided to add small LEDS in the in and out loop buttons and to give them a more unique shape. As for the slider, I mostly stuck to the same design as the one in the boombox. 
By the time I've finished this design my teammate Michael has already made an improved version of the layout with much more symmetrical features:
<img width="1056" height="608" alt="Screenshot 2026-09-20 213025" src="https://github.com/user-attachments/assets/f3eb65cb-9c4d-4c3c-a684-a7ddf439feed" />
Therefore, I moved onto designing the features in the middle but before I copied the layout I decided to change the position of the "mic on" button by shifting it up one position so it match the position of the fx select and fx on buttons since they were also square thereby making the design more symmetrical overall. After that I created this design:
<img width="1095" height="585" alt="Screenshot 2026-09-20 222609" src="https://github.com/user-attachments/assets/d9133ecf-1645-409c-bef6-30cd56102484" />
I ended up changing the layout again but this time I removed the right cue button since it ruined the symmetry, and I extended the length of the sliders on the bottom so they would match the sliders on the top because the size in the layout was out of stock, I also shrunk down the crossfade and smart fade buttons so they would take less space since the middle was extremely crowded, I made sure to match their widths with the width of the cue buttons for better uniformity throughout the design. Finally I removed 2 of the cfx buttons because they were duplicated.
I was really proud of this design and when I showed it to my teammates, they also liked it a lot. At the time, I thought It had the perfect balance between sophistication and readability. But little did I know the Solid shading view tends to be very misleading in terms of expressing detail. 
Now for texturing and colors, I've decided to apply the color palette to the Layout my teammate gave me which was pretty easy since he color coded buttons based on similarity in function and visual distinction. I used the orange and blue for special buttons and I gave the basic controls like the jog wheel and hot cue buttons a very basic grey color and I gave very common buttons and the inside of the sliders in the navy blue color I've previously chosen because it creates very strong contrast with the beige background of the controller which makes these buttons easier to spot. For the texture I decided to go mostly with normal smooth 3d printed walls for almost the entire controller except for the island under the jog wheels where I used a rubber texture to represent fuzzy skin 3d printed pieces at a 0.1 mm thickness to create additional visual depth. and this is what that looked like.
<img width="1006" height="612" alt="Screenshot 2026-09-20 233827" src="https://github.com/user-attachments/assets/feecaa66-3bba-4748-aa6c-bed8d734084f" />
This is when I realized that this design was incredibly bland and boring, so I've decided to add a lot more details until I came up with this:
<img width="1920" height="1080" alt="toprender" src="https://github.com/user-attachments/assets/61556375-fcc4-4346-9217-13a7db12545e" />
One thing I wish I could've added is translucent buttons like this 
<img width="300" height="136" alt="image" src="https://github.com/user-attachments/assets/541593ab-9cb0-438d-bc6f-860a623b0174" />
I tried really hard to achieve this but my version wasn't smooth like the picture 
<img width="583" height="357" alt="Screenshot 2026-09-21 014324" src="https://github.com/user-attachments/assets/b2b5d9ba-3352-4d52-b92b-4948a4cc028c" />
Finally I have to say I'm really proud of this design and my teammates like it to so we've decided we're going to use it. 

