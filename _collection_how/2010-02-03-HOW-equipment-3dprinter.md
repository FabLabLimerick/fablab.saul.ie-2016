---
published: true
title: "3D Printing"
slug: 3dprinter
category: equipment
description: "3D printing is a form of additive manufacturing technology where a three dimensional object is created by laying down successive layers of material."
---

3D printing is a form of additive manufacturing technology where a three dimensional object is created by laying down successive layers of material.

## Reprap Mendel
The Reprap Mendel is an open-souce 3D printer that can print most of its own components. At Fab Lab Limerick we have two Reprap Mendel's built by staff and students working together. It can produce objects up to 210mm x 190mm x 140mm with layer accuracy of 0.2 to 0.3mm. It can print a large variety of plastics including PLA ABS and Nylon. More info about the Reprap Mendel is available [here](http://reprap.org/wiki/RepRapPro_Mendel) and [here](https://reprappro.com/shop/machine-kits/mendel-full-kit/).

## Ultimaker 2
Factory built open-source 3D printer. Ultimaker uses an additive manufacturing technique called Fused Filament Fabrication to lay down material in layers. The max build size is 230 x 225 x 205 mm with layer accuracy of 0.06mm to 0.2mm.


### Cost

Individual           | Cost/hour
-----------          | ------------  
SA UL Student        | €0         
Student              | €5         
Non Profit           | €7.50          
Commercial           | €10  

_Note: White PLA plastic is included in the hourly rate. If you wish to use other materials there is an extra cost per/hour (It varies with every material)._


### Technical Data
Reprap Mendel Build Size: The printer can build objects up to 210mm x 190mm x140mm  (lxbxh).

Ultimaker 2 Build Size: The printer can build objects up to 230mm x 224mm x 205mm (lxbxh).


### Materials
Fab Lab Limerick have a supply of white PLA plastic in stock at all times. Many materials are available for 3D printing but we may not have them in stock. [ColorFabb](http://colorfabb.com/) has a good selection of good quality plastics to purchase. We can order the material you like but we also welcome people bringing their own material in to use on our machines. New materials are being developed regularly including metal composites. Examples are on display in Fab Lab Limerick.

### Preparing Drawings
#### Download a 3D object

[Thingiverse](http://www.thingiverse.com/) has many 3D files ready to download and print for free. The file type you need for printing is a .stl file.

#### Draw a 3D Object

If you would like to draw a 3D object, any 3D drawing software can be used including Sketchup, Rhino, Solidworks, 123D Make, etc. [Sketchup](http://www.sketchup.com/) can be downloaded for free and is a good software for a beginner to start with. Sketchup Tutorials are available [here](http://www.sketchup.com/learn/videos?playlist=58).The only requirement for a 3D software is that it can produce an .stl file type. If the base software cannot do this, install a plugin. The plugin for sketchup is available on the sketchup extensions warehouse [here](http://extensions.sketchup.com/en/content/sketchup-stl). Once you have your specific 3D object drawn export the .stl file.

#### Fix a .stl file
The .stl file needs to be a completely solid object. If the drawn object has gaps between its faces it may not print properly. [Netfabb](www.netfabb.com) can be used to fix 3D models with small gaps between faces. Upload your model to their online service, fix and download the model again.

#### Cura
Cura is a slicing software. It is produced by Ultimaker and is free to [download](https://ultimaker.com/en/products/software). This software takes your .stl file, slices it and creates the gcode that the 3D printers can use. It is simple to use and the specific settings needed for our printers can be got from us when you call in.

To control the 3D printer you need to install a driver and two softwares on your personal laptop. The driver helps your computer connect to the printer. Slic3r is a software that takes your 3D model (.stl) slices it up and creates a file (gcode) that the printer can read. Pronterface is the software that is used to control the 3D printer. You can download and install the relevant files from here:

### Printing

#### Bed Preparation

The first layer of printing is very important. If this layer does not adhere to the bed properly your print is likely to fail. PLA is easiest to print. Use acetone and a tissue to wipe down the bed. Give the bed a light spray with Hairspray if required. With other plastics such as ABS you will need additional adhesives to bond to the bed. ABS juice can be painted onto the bed to create good adhesion.

#### Reprap Mendel
From Cura save your file onto the SD card and insert into the printer. To use the mendel, you need to conect your laptop directly to the printer to select your file. To connect your laptop you will need to install a driver and a control software called pronterface.

Windows

* [Driver](http://www.ftdichip.com/Drivers/CDM/CDM20824_Setup.exe)  (Or if that fails look [here](http://www.ftdichip.com/Drivers/VCP.htm))
* [Pronterface](http://www.reprappro.com/w/images/7/75/RepRapPro-Printrun-Slic3r.zip)

Mac

* [Driver](http://www.ftdichip.com/Drivers/VCP.htm)
* [Pronterface](http://www.reprappro.com/w/images/4/46/RepRapPro-Pronterface-Mac.zip)


#### Ultimaker 2
With the Ultimaker 2 sending the file to print is a quick and easy job. From Cura save your file onto an SD card. Slot the card into the front of the machine and select your file for printing.

[Book Here](http://fablablimerick.schedulista.com/)
