![DOOMCUBE](Images/DCLogo.png)
# DoomCube
Based on the DoomCube Mod for the Voron V2 and several popular Mods out there, I decided to capture my DoomCube build in a full CAD. Some Mods are implemented as is, other Mods have been altered and some Mods I created myself (most of the times inspired by other Mods).
I will try to capture all details below.

[Make sure to join the DoomCube discord!](https://discord.gg/EAANfEk25f)


#### Frame and panels:

- 300m3 build
- applied the panel mounting principle of the original DoomCube door to the side and back panels.
- Added 20mm to the height. so the door, side and back panels all rest within a frame. This eliminates the need for the flanges to support the panels. All panels are mounted in panelmounts that directly bolt into the extrusions.
- Top and bottom panels use the original system. Unfortunately this requires them to be inserted during the build, but I haven't been able to come up with an alternative solution that allows for installation after the frame build.
- All panels have cutouts for wire passthroughs and for mounting the ERCF on top of the upper deck panel.

#### Skirts:

- Basis are the hexagon skirts from the DoomCube. 
- Due to side and back panel mounting system, flanges of the door are used all around as well as the panelmounts.
- Panelmounts are 2 pieces per side, instead of 3. This might not be printable on smaller bed sizes.
- Top and Bottom have different top caps for the corners. These caps allow the deck panels to be attached to the corners with magnets.
- Top Corners and skirts have been increased in size in order to accomodate my Waveshare 4,3" LCD. For this a center skirt was also modded to hold the LCD.
- At the bottom a center skirt was modded to accomodate a Schaffner FN-286 inlet.

#### Heated Bed:

- Mandela Rose Works ultra flat bed is used. It has mounting holes for both the V1.8 and the V2.4. Therefor I'm able to use a triangle 3-point mounting method, by inserting a cross bar between the two bed extrusions. This is also done to accomodate for a kinematic mounting system that is in development with Mandela Rose Works and uses 3 mounting points.

#### Z-Assembly:
- Mostly utilizes DoomCube parts.
- Motor Mounts are taken from the DoomCube CAD, there are no stl's for this in the repository which implies to use the original V2.4 parts. Those have 3 mounting points though, I like the 4 mounting points better, so I created the stl from the DoomCube CAD.
- The belt covers are based on crag-something belt covers, I just added a somewhat different ledge to make a tighter integration to the panels.
- Cable cover for A drive by crag-something

#### Gantry:

- MGN 12 Mod Arkeet
- Pins Mod hartk
- Y relocation Mod hartk
- GE5C mod hartk

#### X-Carriage
- klicky probe mod for x-carriage
- crag-something adxl mount (modded)
- hartk PCB
- majarspeed pcb mount for galileo
- jaredc01 galileo
- badnoob ab-bn-30
- Mosquito
- ERCF sensor for galileo, experimental version for v1.1 (to be released). Not in cad as there is only an stl.

#### Electronics
- Wire grommet for passthrough of Tircowns ERCF easy board to the ERCF
- PTFE grommet for passthrough of PTFE from top deck panel to top panel
- PTFE and Umbilical grommet for passthrough of PTFE and Wires to the toolhead
- Wire grommet for the Z-chain wires
- Wire grommet for the wires trough the bottom panel to the bottom of the chamber
- All grommets are based on loco... wire grommet
- BED PCB for central connection of the wires at the bottom of the chamber. Bed Mains and Fuse, Bed Thermistor, Z Endstop, 2x bed fan or nevermore micro.
- DIN Mounts for BTT Octopus, Tircown's ERCF Easy Board, LRS-200-24

#### Other

 - LED
 - Klicky Probe
 - hartk Sexbolt
 - Nevermore Duo, with modded plenum
 - Annex's purge bucket
 - Webcam mount for Wansview 1080o

#### ERCF

 - 9 Channel ERCF. Number of channels irrelevant as I mount the ERCF to the extrusion.

# COPY PASTE STUFF

<img src="Images/404020-1.jpg" alt="drawing" width="200"/>

# Header
## Sub Header
### Sub Sub Header
#### Sub Sub Sub Header

Table

Misumi Part #  |Qty
|:----:|:----:|
Square Verticals: HFSB5-4040-530 |4 
Rounded Verticals: HFSR5-404020-530 |4


### Afterburner MGN12 Gantry
Mod|Repository
|:---:|:---:|
Ark's MGN12|https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/arkeet/mgn12
Hartk's GE5C Spherical Z Joint|https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_GE5C
Hartk's Pinmod (X/Y Joints, ,A/B Drive Frames, A/B idlers, Z idlers)|https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Pins_Mod




#### A big thanks to all original authors for permission to include their mods in the Doomcube CAD!  Always follow the links to their respective repos for the latest stl's, and info on how to best make use of their mods.


