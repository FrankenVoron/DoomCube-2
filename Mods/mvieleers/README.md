# DoomCube
Based on the DoomCube Mod for the Voron V2 and several popular Mods out there, I decided to capture my personalized DoomCube build in a full CAD. Some Mods I use are implemented as is, other Mods have been altered and some Mods I created myself (most of the times inspired by other Mods).
Untouched mods will link to their official github, altered DoomCube specific mods will be hosted seperately under the Mods section of this DoomCube repository and Mods that are applicable to standard Voron V2 will be hosted from my own Github.

[Make sure to join the DoomCube discord!](https://discord.gg/EAANfEk25f)

## CAD
A full CAD for this build will be available. For the most part it will include fasteners as well, with the exception for flanges, skirts and panelmounts.
As the CAD is 100 Mb+ it cannot be uploaded as one into Github. I've broken it up in different sections (one of these also needed to be zipped). When you import the STEP files into a new drawing, it will form one complete system again.

Click [HERE](../mvieleers/CAD/) for STEP files

![Full Assembly](Images/full_assembly.png)

## Frame

![Frame(Images/frame.png)

Section|Part| Part #|QTY|Remarks
|:---:|:----:|:----:|:---:|:---:|
Bottom Frame
||Bottom Horizontals|[HFSB5-2020-420-TPW](https://uk.misumi-ec.com/vona2/detail/110302683830/?HissuCode=HFSB5-2020-420-TPW&PNSearch=HFSB5-2020-420-TPW&KWSearch=HFSB5-2020-420-TPW&searchFlow=results2type)|8
||OpenBuilds Angle Corner Connector|[20x20x20](https://openbuildspartstore.com/black-angle-corner-connector/)|4|Used to keep the two extrusions from rotating
||Slot Covers|[HSCKS5-B](https://uk.misumi-ec.com/vona2/detail/110302695120/?HissuCode=HSCL5-B&searchFlow=results2similartn)|1|Comes in 2m so needs to be cut to length
Vertical Frame
||Square Verticals|[HFSB5-4040-500-LWP-RWP-TPW](https://uk.misumi-ec.com/vona2/detail/110302684530/?HissuCode=HFSB5-4040-500-LWP-RWP-TPW&PNSearch=HFSB5-4040-500-LWP-RWP-TPW&KWSearch=HFSB5-4040-500-LWP-RWP-TPW&searchFlow=results2type)|4
||Slot Covers|[HSCKS5-B](https://uk.misumi-ec.com/vona2/detail/110302695120/?HissuCode=HSCL5-B&searchFlow=results2similartn)|2|Comes in 2m so needs to be cut to length
Top Frame
||Top Horizontals|[HFSB5-2040-420-TPW](https://uk.misumi-ec.com/vona2/detail/110302684350/?HissuCode=HFSB5-2040-420-TPW&PNSearch=HFSB5-2040-420-TPW&KWSearch=HFSB5-2040-420-TPW&searchFlow=results2type)|4
||Slot Covers|[HSCKS5-B](https://uk.misumi-ec.com/vona2/detail/110302695120/?HissuCode=HSCL5-B&searchFlow=results2similartn)|1|Comes in 2m so needs to be cut to length
Bed Frame
|||[HFSB5-2020-420-TPW](https://uk.misumi-ec.com/vona2/detail/110302683830/?HissuCode=HFSB5-2020-420-TPW&PNSearch=HFSB5-2020-420-TPW&KWSearch=HFSB5-2020-420-TPW&searchFlow=results2type)|2|
|||[HFSB5-2020-130](https://uk.misumi-ec.com/vona2/detail/110302683830/?HissuCode=HFSB5-2020-130&PNSearch=HFSB5-2020-130&KWSearch=HFSB5-2020-130&searchFlow=results2type)|1
||OpenBuilds Angle Corner Connector|[20x20x20](https://openbuildspartstore.com/black-angle-corner-connector/)|6|4 for securing the bed frame to the bottom frame, 2 to secure the cross bar

### Specifics
- 300m3 build.
- Added 20mm to the height of the vertical frame, so the door, side and back panels all rest within an extrusion frame. This eliminates the need for the flanges to support the panels. 
- The bed frame has a cross bar in order to mount my bed with 3 mounting points instead of 4. It is a preparation to add a kinematic bed mounting solution at a later time.

## Panels

![Panels(Images/panels.png)

### Specifics
- The principle of the original DoomCube door is applied to the side and back panels, where the panels slide into panelmounuts that bolt into the extrusion.
- Top and bottom panels use the original DoomCube mounting system. Unfortunately this requires them to be inserted during the build, but I haven't been able to come up with an alternative solution that allows for installation after the frame build.
- Top and bottom (deck) panels have cutouts for wire passthroughs and the top deck panel has mounting holes for mounting the ERCF on top of the top deck panel.

Panel|Drawing|DXF|QTY
|:---:|:---:|:---:|:---:|
Door|panel_side.pdf|panel_side.dxf|2
Sides|panel_side.pdf|panel_side.dxf|4
Back|panel_back.pdf|panel_side.dxf|2
Top|panel_top.pdf|panel_top.dxf|2
Bottom|panel_bottom.pdf|panel_bottom.dxf|2
Top Deck|panel_top_deck.pdf|panel_top_deck.dxf|1
Bottom Deck|panel_bottom_deck.pdf|panel_bottom_deck.dxf|1


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


