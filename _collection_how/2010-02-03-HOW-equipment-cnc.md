---
published: true
title: "CNC Router"
slug: cnc
category: equipment
description: "Shopbot is a factory built CNC Router able to cut Wood, Plastic, Foam and soft metals. Maximum material size: 2440 x 1220 x 150mm. Many different sizes and types of cutting bits can be used."
---

Shopbot is a factory built CNC Router able to cut Wood, Plastic, Foam and soft metals. Maximum material size: 2440 x 1220 x 150mm. Many different sizes and types of cutting bits can be used.

## Cost

Individual           | Cost/hour
-----------          | ------------  
SAUL Student         | €0         
Student              | €20         
Non Profit           | €30         
Commercial           | €40       

## Technical Data

Bed Size   |  2440mm x 1220 x 150mm
Power      |  4hp Spindle

## Preparing Drawings

### Drawing
Any 2D drafting software can be used to create the files for CNC Routing such as Autocad, Adobe Illustrator or free softwares such as [draftsight](http://www.3ds.com/products-services/draftsight-cad-software/) or [Inkscape](https://inkscape.org/en/). Each different cutting profile (profile cut, pocketet cut, etc) needs to be drawn on a different layer. When creating your drawings screw patterns and bit sizes need to be considered. Screws are used to secure material to bed. Adequate space needs to be left around screws to ensure cutting bits don't come in contact with them. We usually leave a border of 30mm at the edge of our material for screws. Save drawing as .dwg or .dxf.

### CNC Cutting Bits
There is many many types of CNC cutting bits. Differnt bits are used for different materilas. They vary in size speed and shape. [This document](http://www.shopbottools.com/Training/Videos/Info%20on%20bits.pdf) gives a good overview on the general type of bits that we use. As a rule of thumb, the bigger the diameter of the bit, the faster and deeper it can cut. However if you have intricate work to do you may want to use smaller bits. The bit size we most popularly use is a 1/4 inch (6.35mm) bit as it gives a good level of detil and speed combined. We keep a range of bits in stock but please give us notice if you would like to test any new materials or procedures as we may need to research and purchase new bits.  

### G-code
Your drawing needs to be converted to 'G-code' for the CNC to read it. For this process we use V-carve pro or Partworks 3D. Both of these softwares are not free. Therefore they are avaiable on a PC in Fab Lab Limerick for your convenience.

It is very important to use tabs in your work. Tabs are small bridges of material that the CNC intentionally leaves uncut so that your piece stays in place until the cutting procedure is finished. Tabs can be added automatically using V Carve Pro software. Please review your cutting process through the preview option before sending it to the machine.

## Safety
The Shopbot CNC Router is an **extremely** dangerous piece of equipment if misused. Please keep a safe distance back from machine at all times when it is in operation. Please use eye and ear protection when using the Shopbot. Do not wear loose clothing or jewellery. Tie back long hair. Take note of all emergency stops before turning the machine on. If you are not completely sure the machine is cutting correctly, pause the Shopbot and turn off the extraction before inspecting. Shopbot can be paused by pressing spacebar on Keyboard.

### Control Software
Shopbot 3 is the proprietry software available for our Shopbot CNC. It is used to send manual commands and g-code to the CNC Router. It is installed on our computer and directly connected to the CNC. When the 'Yellow Box' is open you can use the keyboard to manually move the machine. The 'Yellow Box' must be closed to send any other commands to the machine.

### Warm-up
If the CNC has not been used within the previous 4 hours, the spindle needs to be warmed up. Shopbot 3 shortcut is **C5**.

### Loading Material
Move spindle up using 'Yellow Box'. Hoover bed so that it is free from debris. Place material on bed and secure with screws. Be sure to place screws so that the cutting bit cannot hit them (in the 30mm border around edge of your piece).

### Insert Cutting Bit
Using the two spanners provided to loosen the Collet. One of the spanners must be removed from a Keylock to be used. This is a safety measure to prevent the spindle from turning when you are changing the bit. Insert the new bit with a suitable sized collet and tighten using the two spanners provided.

### Zeroing the CNC
The Shopbot CNC router has no 'memory' of what coordinate position it is at if it is switched off. Therefore everytime you switch the machine back on you must set the 0,0,0 (x,y,z) coordinate. Using your 'Yellow Box' move the bit so it hovers above the x,y 0,0 make. ie the bottom left hand corner of your sheet. Using 'Yellow Box' press 'zero Axis' and select x and y zero.
The z axis needs to be more accurate. Therefore, we use a zeroing clip and plate. With the 'Yellow Box' closed, connect the alligator clip to the bit and place the place underneath the bit on the material surface. Select shortcut **C2** and Machine will automatically zero Z axis. Once all 3 axis are zeroed, the Shopbot 3 software can be closed.

### Sending the File
When you have your file created in V carve pro or Partworks 3D, save the toolpaths and it will automatically reopen Shopbot 3. Follow the promps on Screen. It will tell you to turn on the spindle and then send the file. Your now cutting!! Turn on the extraction keep space free from dust.

### Post-Processing
Once the Shopbot is finished cutting, turn off extraction. Remove screws from work piece and move workpiece to workbench provided. If you turn the workpiece upside down, you can cut tabs out cleanly with sharp chisel.

[Book Here](http://fablab.saul.ie/how/how/booking/)
