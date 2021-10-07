![DOOMCUBE](Images/DCLogo.png)
# Doom-Cube
A mod for Voron 2.4; designed by the Voron community, for the Voron community! Please note that it is a work in progress, design iterations are expected. The files are hosted on github so we have a log of the past history for the parts.

[![](https://img.shields.io/discord/825469421346226226?color=darkred&label=DOOMCUBE&logo=discord&logoColor=fafafa)](https://discord.gg/doomcube)

#### Key features:

- 4040 vertical components to allow for insulation with air gap stock

- Top mounted Z drives

- Top mounted low voltage components

- Bottom mounted high voltage components

#### Optional

- Replace X/Y cable chains with umbelical (Z chain retained for A/B motors and Y endstop)


#### Changes required:

- 4pcs 4040 extrusions (HFSB5-4040)   -or-   4pcs 404020 rounded extrusions (HFSR5-404020)

- New Z Idlers  (only printed parts required)

- Relocate X/Y endstops  (only printed parts required)

- Cable Glands for Umbelical

#### Tips for printing parts:

For any Voron stock parts, or the Z idlers, please use standard Voron settings.

For skirts, etc, you may use other settings to reduce filament usage. Currently I am using: 0.3mm layer height, 2 perimeters, 2 bottom, 3 top, 20% infill. 

## BOM 

All extrusions are listed using Misumi part numbers.

Part numbers are listed for both square 4040, and rounded 404020 vertical extrusions.  Choose only one type.  The first set of part numbers is for plain cut extrusions.  The second part number is for square extrusions that are cut and drilled by misumi.  

#### Note:
If you choose to use rounded corners, you will need to reuse your frame's existing 2020 vertical extrusions, or purchase a set of them for a scratch build.  The rounded verticals do not require machining, but the 2020 verticals that nest into them will need to have holes drilled to enable securing the rounded piece with blind joints, as shown here.

<img src="Images/404020-1.jpg" alt="drawing" width="200"/>

## Extrusions Based on Standard V2 Build Sizes

## DOOM-350
### Frame Extrusions
#### DIY
Misumi Part #  |Qty
|:----:|:----:|
Square Verticals: HFSB5-4040-530 |4 
Rounded Verticals: HFSR5-404020-530 |4

#### Pre-Drilled
Misumi Part #  |Qty
|:----:|:----:|
Square Verticals: HFSB5-4040-530-LCP-RCP |4

### Door Extrusions

#### DIY
Misumi Part #  |Qty
|:----:|:----:|
HFSB5-2020-530|2
HFSB5-2020-428|2

#### Pre-Drilled
Misumi Part #  |Qty
|:----:|:----:|
HFSB5-2020-530-AH10-BH520|2
HFSB5-2020-428-TPW|2

## DOOM-300
### Frame Extrusions
#### DIY
Misumi Part #  |Qty
|:----:|:----:|
Square Verticals: HFSB5-4040-480 |4
Rounded Verticals: HFSR5-404020-480 |4

#### Pre-Drilled
Misumi Part #  |Qty
|:----:|:----:|
Verticals: HFSB5-4040-480-LCP-RCP |4

### Door Extrusions
#### DIY
Misumi Part #  |Qty
|:----:|:----:|
HFSB5-2020-480|2
HFSB5-2020-378|2

#### Pre-Drilled
Misumi Part #  |Qty|
|:----:|:----:|
HFSB5-2020-480-AH10-BH470|2
HFSB5-2020-378-TPW|2

## DOOM-250
### Frame Extrusions
#### DIY
Misumi Part #  |Qty
|:----:|:----:|
Square Verticals: HFSB5-4040-430 |4
Rounded Verticals: HFSR5-404020-430 |4

#### Pre-Drilled
Misumi Part #  |Qty|
|:----:|:----:|
Square Verticals: HFSB5-4040-430-LCP-RCP| 4

### Door Extrusions

#### DIY
Misumi Part #  |Qty| 
|:----:|:----:|
HFSB5-2020-430|2
HFSB5-2020-328|2

#### Pre-Drilled

Misumi Part #  |Qty| 
|:----:|:----:|
HFSB5-2020-430-AH10-BH420|2
HFSB5-2020-328-TPW|2

## Door Hinges
Silver and Black are listed 

|Misumi Part #  |Qty|Color
|:------:|:---:|:---:|
HHPSN5-SET|2| Silver
HHPBSN5-SET|2| Black


# Ongoing and Future Development
While we all have many irons in the fire, Doomcube v2 is still being worked on.  Keep an eye out for changes coming to the panel printed parts, as well as some coming mods from the community.  In the interest of encouraging more Doom builds, as well as more mods, a complete DOOM CAD file is now available with all the Doom and Voron components together.  Find it in the CAD folder with all the individual component CAD files.  The individual components have been gone through and all hole sizes have been made consistent.  Missing chamfers were added, and some geometry cleaned up.  The frame and panel assemblies will stay as they are until new files are ready.
### CAD Notes
If you examine the complete CAD file you will see it is not limited to the basic DOOM and Voron components.  Included are two optional gantry variants, with a handful of popular community produced V2 mods installed.  The file is structured to be very easy to see what you want, and hide what you don't.  The step file has everything shown by default, so you'll need to hide the frame, skirts, and gantries you don't wish to see.  It should only take a few clicks.

DoomCubing is a great way to improve your v2.  It's also a perfect time to install several mods, while you have things partially disassembled.  To give you some ideas about possible mod combos, the optional modded gantries in the complete cad file contain the following excellent mods:


### Afterburner MGN12 Gantry
Mod|Repository
|:---:|:---:|
Ark's MGN12|https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/arkeet/mgn12
Hartk's GE5C Spherical Z Joint|https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_GE5C
Hartk's Pinmod (X/Y Joints, ,A/B Drive Frames, A/B idlers, Z idlers)|https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Pins_Mod


### Mantis MGN12 Gantry
Mod|Repository
|:---:|:---:|
Long's Mantis Toolhead|https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Long/Mantis_Dual_5015
Hartk's GE5C Spherical Z Joint|https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_GE5C
Hartk's Pinmod (X/Y Joints,A/B Drive Frames, Z idlers)|https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Pins_Mod
Phalanx's Other Idlers|https://github.com/selliott79/Other-V2-Idlers

### Other Mods
The following mods are present in all or most Doomcube variants in the complete CAD file.  Klicky is not on the Mantis toolhead, since it has a native magprobe that works identically to Klicky.

Mod|Repository
|:---:|:---:|
L.e.o.p.a.r.d and Hartk's Sexbolt Z Endstop|https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_SexBolt_ZEndstop
josar's Klicky Probe|https://github.com/jlas1/Klicky-Probe 
whoppingpochard's Gantry Rail Backers|https://github.com/tanaes/whopping_Voron_mods/tree/main/extrusion_backers

#### A big thanks to all original authors for permission to include their mods in the Doomcube CAD!  Always follow the links to their respective repos for the latest stl's, and info on how to best make use of their mods.

##### A set of stl checklists to match these mod sets is in the works.  That can be one of the most confusing parts of building up a modded printer from scratch, or doing many mods at once with redundant components.  Hopefully a few checklists will simplify things a little bit.  A huge debt is owed to all the mod makers and their willingness to share their work!  Keep up the good work y'all!
