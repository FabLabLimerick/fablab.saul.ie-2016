---
published: true
title: "3D Printing"
slug: 3dprinter
category: equipment
description: "3D printing is a form of additive manufacturing technology where a three dimensional object is created by laying down successive layers of material."
---

3D printing is a form of additive manufacturing technology where a three dimensional object is created by laying down successive layers of material.

## Reprap Mendel
The Reprap Mendel is an open-souce 3D printer that can print most of its own components. At Fab Lab Limerick we have two Reprap Mendel's built by staff and students working together. It can produce objects up to 210mm x 190mm x 140mm with layer accuracy of 0.2 to 0.3mm. It can print a large variety of plastics including PLA, ABS and Nylon. More info about the Reprap Mendel is available [here](http://reprap.org/wiki/RepRapPro_Mendel) and [here](https://reprappro.com/shop/machine-kits/mendel-full-kit/).

## Ultimaker 2
Factory built open-source 3D printer. Ultimaker uses an additive manufacturing technique called Fused Filament Fabrication to lay down material in layers. The max build size is 230 x 225 x 205 mm with layer accuracy of 0.06mm to 0.2mm.

## Wasp 2040
The 2040 is a very popular delta printer produced by [Wasp](http://www.wasproject.it) in Italy. The Wasp also prints by Fused Filament Fabrication, in a variety of plastics. The print volume of the Wasp is 200 x 200 x 400mm, with a high accuracy and a default layer height of 0.1mm.

## Wasp 4070
The 4070 is a larger printer, very similar to the 2040, but offering a build volume of 400 x 400 x 700mm.

<!---
## LDM Extruder (for Wasp)
Print in clay...
-->

<!---
## Form2 (SLA Printing)
The Form2 is a printer from Form Labs, which uses a method of printing called StereoLithography,
Please see [this page](http://fablab.saul.ie/) for more details.
-->

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

Wasp 2040 Build Size: 200mm diameter, 400mm high (cylindrical build volume)

Wasp 4070 Build Size: 400mm diameter, 700mm high (cylindrical build volume)


### Materials
We keep a good supply of white PLA plastic. Many other materials are available for 3D printing but we may not have them in stock. [ColorFabb](http://colorfabb.com/) has a good selection of good quality plastics to purchase. We can order the material you like but we also welcome people bringing their own material in to use on our machines. New materials are being developed regularly including metal composites. Examples are on display in Fab Lab Limerick.

### Preparing Drawings
#### Download a 3D object

[Thingiverse](http://www.thingiverse.com/) has many 3D files ready to download and print for free. The file type you need for printing is a .stl file.

#### Draw a 3D Object

If you would like to draw a 3D object, any 3D drawing software can be used including Sketchup, Rhino, Solidworks, 123D Make, etc. [Sketchup](http://www.sketchup.com/) can be downloaded for free and is a good software for a beginner to start with. Sketchup Tutorials are available [here](http://www.sketchup.com/learn/videos?playlist=58).The only requirement for a 3D software is that it can produce an .stl file type. If the base software cannot do this, install a plugin. The plugin for sketchup is available on the sketchup extensions warehouse [here](http://extensions.sketchup.com/en/content/sketchup-stl). Once you have your specific 3D object drawn export the .stl file.

#### Fix a .stl file
The .stl file needs to be a completely solid object. If the drawn object has gaps between its faces it may not print properly. [Netfabb](www.netfabb.com) can be used to fix 3D models with small gaps between faces. Upload your model to their online service, fix and download the model again.

#### Slicing with Cura
Cura is a slicing software, which takes your 3D model (.stl) slices it up and creates a file (gcode) that the printer can read. Cura is produced by Ultimaker and is free to [download](https://ultimaker.com/en/products/software). It is simple to use, and the specific settings needed for our printers can be got from us when you call in.

#### Note on slicing for the Wasp Printers
Unfortunately, Cura v2 and later do not support delta printers. As described [here](https://ultimaker.com/en/community/21355-am-i-wrong-or-this-new-cura-212-doesnt-support-delta-printers) support for circular beds was a contibuted feature developed by users of the Cura software, and no replacement has been implemented in the newer versions. So unfortunately, if you would like to use Cura with our Wasp Printers, you need to install version 15.04.6 or older [from this page](https://ultimaker.com/en/products/cura-software/list).

#### Adding Wasps as new machines in Cura
In the file menu, go to `Machine > Add New Machine`. Then, in the dialog box, click `Next`. Select `Other (Ex: RepRap, MakerBot, WitBox)`, and then `DeltaBot Style`. Then click `OK` to finish the setup process. The "DeltaBot Style" machine is a good template for other delta printers, and we just need to change the dimensions now to suit the Wasp 3D printers. In the file menu again, go to `Machine > Machine Settings`, click the machine name, `DeltaBot Style` from the tabs at the top of the window. Now change the **Maximum Width (mm)**, **Maximum Depth (mm)** and **Maximum Height (mm)** settings. For the Wasp 2040, these should be 200, 200 and 400 respectively; and for the 4070, these should be 400, 400 and 700. You can click `Change Machine Name` at the bottom of the window, to give the machine a more descriptive name.

#### Configuration files:
For the Wasp 2040 printer, Wasp has supplied the following configuration profiles: [PLA](http://fablab.saul.ie/assets/downloads/Configurazioni_Delta%202040_PLA.ini), and 
[ABS](http://fablab.saul.ie/assets/downloads/Configurazioni_Delta%202040_ABS.ini); and for the 4070: [PLA](http://fablab.saul.ie/assets/downloads/Configurazioni_Delta%204070_ABS.ini), and
[ABS](http://fablab.saul.ie/assets/downloads/Configurazioni_Delta%204070_PLA.ini). To load a preconfigured profile in Cura, go to File > Open Profile and choose the location of the above files.

#### Other slicing programs - Slic3r, Simplify3D

[Slic3r](http://slic3r.org/) (which is free, and Open Source) and [Simplify3D](http://simplify3d.com) ($149 USD) are other softwares that takes your 3D model (.stl), slice it up and create a file (gcode) that the printer can read.

### Printing

#### Bed Preparation

The first layer of printing is very important. If this layer does not adhere to the bed properly your print is likely to fail. PLA is easiest to print. Use acetone and a tissue to wipe down the bed. Give the bed a light spray with Hairspray if required. With other plastics such as ABS you will need additional adhesives to bond to the bed. ABS juice can be painted onto the bed to create good adhesion.

The Wasp Printers require Pritt Stick, or glue stick to provide additional adhesion to the bed. Ensure that the print area gets an even coating, and consider brims and rafts as other techniques to improve the bed adhesion of your print.

#### Reprap Mendel
From Cura save your file onto the MicroSD card and insert into the printer. To control the Mendel directly by serial port(USB), you will need to install a driver and a control software called PronterFace.

Windows

* [Driver](http://www.ftdichip.com/Drivers/CDM/CDM20824_Setup.exe)  (Or if that fails look [here](http://www.ftdichip.com/Drivers/VCP.htm))
* [Pronterface](http://www.reprappro.com/w/images/7/75/RepRapPro-Printrun-Slic3r.zip)

Mac

* [Driver](http://www.ftdichip.com/Drivers/VCP.htm)
* [Pronterface](http://www.reprappro.com/w/images/4/46/RepRapPro-Pronterface-Mac.zip)

#### Ultimaker 2
With the Ultimaker 2 sending the file to print is a quick and easy job. From Cura save your file onto an SD card. Slot the card into the front of the machine and select `Print` or `Preheat` and then your file for printing.

### Booking
To use any of our printers, you need to book [here](http://fablab.saul.ie/how/how/booking/). Each printer is available to be booked by the hour, and you should book as many slots as estimated by your slicer software. If you have any queries, send us an [email](mailto:fablab@saul.ie).
