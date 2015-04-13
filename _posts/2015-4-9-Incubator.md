---
layout: post
title: Incubator
---

The first piece of equipment that I'm building for the Biohack Academy is an incubator. For a novice in micro-controllers and electronic circuits like me, this diy incubator has its fair set of challenges and in the process I've learnt a lot. 

###Laser cutter
I've been working on my meat barcoding experiment for a year now in the Wetlab, which is separated from the Fablab by just a door, but this was the first time that I've ventured into the Fablab. The purpose was using the laser cutter to cut the mdf wood based on the svg sketches provided by Pieter. After the initial moments while the software, the equipment, the instructions are not familiar, things start to make sense and one starts to agree with the shared opinion that using the laser cutter is like using a printer. "Just remember to turn this lever or the machine will catch fire!" And 2 to 3 hours later I had all the pieces needed to build the box for the incubator nicely cut, with a faint scent of burnt wood and ready to be assembled. This was my favourite part by the way - putting together the various panels - it was just like assembling a puzzle.

###3D drawing tools
Software-wise SketchUp and Inkscape made a very good impression on me. Inkscape in particular, as it has a very easy learning curve and helped me prepare a presentation for work recently. I'm a big believer in the saying that an image is worth a thousand words, and when I had to explain how one application is a node and then how to group nodes, install nodes on machines, how 20 machines make a cluster and how finally we need to manage several clusters in both course and fine detail, well, let's just say that using a vector drawing tool helped a lot to convey the point.

###Arduino
Before the academy started, I had bought some Arduino kits on e-bay and tried a couple of easy experiments. My plan next was to build an automated plant watering system for my indoor plants, but by the time I received all the components (I tried to go as cheap as possible, so I ordered them from China) the academy had started. So my plant watering system is on hold for now until I graduate from the academy. But I digress... In my opinion there are 3 main circuits needed, so in the beginning I've build each separate.

####Light and Relay
The incubator has to maintain a fixed temperature inside and to achieve this the first thing needed is a heat source. In my case the heat source is an infrared bulb connected to the 220 power supply plug and controlled via a relay by Arduino. I was bit worried about this part, so I had someone show me how it's done and I have to admit that now I find it pretty easy. The images below show the test circuit for the relay connected to Arduino and a light bulb and the video captures a test where Arduino turns the light on for 5 seconds and off for 5 seconds and repeats the cycle over and over again as long as it has power: in this case Arduino is connected to my laptop's usb port and the light is plugged in the wall socket. For testing I used a normal light bulb (E27) in place of the infrared bulb.

<img src="{{ site.baseurl }}/images/incubator/relay.jpg" height="315" />
<iframe width="420" height="315" src="https://www.youtube.com/embed/aVjFg2NNEhs" frameborder="0" allowfullscreen> </iframe>

####Fan
The fan's role is to circulate the air inside the incubator and make sure there are no temperatures differences.

###Temperature sensor

###The result
I'm very close to finishing the incubator. Too bad the temperature sensor broke, I have to order a new one, or 2 just to be sure.

<img src="{{ site.baseurl }}/images/incubator/incubator.jpg" width="400" height="400" />


