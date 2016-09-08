---
published: true
title: "Setting up Inkscape for use with the Lasersaur"
slug: inkscape-lasercuting
category: tutorials
description: "A step by step guide to using our lasersaur with Inkscape"
---

For Laser Cutting with Inkscape, to avoid any inherent scaling issues, you should download this [Lasersaur Template](https://groups.google.com/group/lasersaur/attach/7b0c933b5665b43d/Lasersaur.svg?part=0.1&authuser=0) (uploaded via Google groups, by user Stefanix). Laser cutting is only possible with versions 0.9.1 or later, which you can download from [inkscape.org](https://inkscape.org/download/).

* For Windows: Open `C:\Program Files\Inkscape\share\templates` Copy the template file that you have just downloaded into this folder.

* For Mac/Linux: Copy the above template to `~/.config/inkscape/templates`. `~/.config` is a hidden folder, so you may need to change your Finder view setting to see it on Mac. However if you click `Go > Go To Folder` you can type the above location to be taken to that location.

If you rename this as `default.svg` (with no capital letters) and replace the existing file of the same name this becomes the file that opens when you launch Inkscape, with the correct dimensions and scaling.

## File Types
Inkscape works natively with .SVG files, which can be used for laser cutting. Remember to outline any text elements and to assign distinct colours to each type of cut or engrave - these can be any colour, just as long as they are different, that is how the LasersaurApp will differentiate between the different settings needed for your job.

## Other links:
As described above, you can also use the templates below to help in preparing files for the Trotec. Inkscape files need to be installed in their respective folder inside `C:\Program Files\Inkscape\share\templates` or `~/.config/inkscape/templates`

* <a href="https://cdn.rawgit.com/FabLabLimerick/fablablimerick.github.io/a25482298b580ffb31d461b0ef1f9e51a14b46b6/app/assets/Trotec.svg" download>Trotec template (Inkscape)</a> (Right click and "Save Link As" to download)

* <a href="https://cdn.rawgit.com/FabLabLimerick/fablablimerick.github.io/a25482298b580ffb31d461b0ef1f9e51a14b46b6/app/assets/Trotec.gpl" download>Trotec Swatch (Inkscape)</a>

* <a href="https://cdn.rawgit.com/FabLabLimerick/fablablimerick.github.io/a25482298b580ffb31d461b0ef1f9e51a14b46b6/app/assets/Trotec.ase" download>Trotec Swatch (Illustrator)</a> This swatch can be loaded by going to `Window > Swatch Libraries > Other Libraries... `. Or it can be added to your default swatch list by copying this file to `C` (on PC) or `/Applications/(Your version of Adobe Illustrator)/Presets.localized/en_GB` (on Mac).
