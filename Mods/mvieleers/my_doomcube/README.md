# DoomCube
Based on the DoomCube Mod for the Voron V2 and several popular Mods out there, I decided to capture my personalized DoomCube build in a full CAD.
Different types of Mods are used in this build:
- DoomCube personalization. These are changes I made to the original DoomCube files, but are very specific to this particular build. Be very carefull if you use these files and make sure they can be applied to your situation. The files will be hosted under this "My DoomCube" Mod.
- Official Mods. These are official Mods untouched by me and implemented as is. I will link to their official github.
- Altered DoomCube specific Mods. These are Mods by me based on the official DoomCube files and applicable to any DoomCube build. They will be hosted seperately under the Mods section of the official DoomCube repository.
- Voron V2 Mods by me. These are Mods by me that are applicable to any Voron V2 (Doomed or not) and will be hosted from my own Github.

[Make sure to join the DoomCube discord!](https://discord.gg/EAANfEk25f)

## CAD
A full CAD for this build will is available. For the most part it will include fasteners as well, with the exception for flanges, skirts and panelmounts.
As the CAD is 100 Mb+ it cannot be uploaded as one into Github. I've broken it up in different sections (one of these also needed to be zipped). When you import the STEP files into a new drawing, it will form one complete assembly again.

Click [HERE](CAD) for STEP files

![Full Assembly](Images/full_assembly.png)

## Frame

![Frame](Images/frame.png)

### Specifics
- 300m3 build.
- Added 20mm to the height of the vertical frame, so the door, side and back panels all rest within an extrusion frame. This eliminates the need for the flanges to support the panels. 
- The bed frame has a cross bar in order to mount my bed with 3 mounting points instead of 4. It is a preparation to add a kinematic bed mounting solution at a later time.

### Hardware
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

## Panels

![Panels](Images/panels.png)

### Specifics
- The principle of the original DoomCube door is applied to the side and back panels, where the panels slide into panelmounts that bolt into the extrusion.
- Top and bottom panels use the original DoomCube mounting system. Unfortunately this requires them to be inserted during the build, but I haven't been able to come up with an alternative solution that allows for installation after the frame build.
- Top and bottom (deck) panels have cutouts for wire passthroughs and the top deck panel has mounting holes for mounting the ERCF on top of the top deck panel.

### Dimensions
Drawings are [here](Drawings), DXFs are [here](DXF)

Panel|Drawing|DXF|QTY
|:---:|:---:|:---:|:---:|
Door|panel_side.pdf|panel_side.dxf|2
Sides|panel_side.pdf|panel_side.dxf|4
Back|panel_back.pdf|panel_side.dxf|2
Top|panel_top.pdf|panel_top.dxf|2
Bottom|panel_bottom.pdf|panel_bottom.dxf|2
Top Deck|panel_top_deck.pdf|panel_top_deck.dxf|1
Bottom Deck|panel_bottom_deck.pdf|panel_bottom_deck.dxf|1

### Hardware
Hardware|Part|QTY|Remarks
|:---:|:---:|:---:|:---:
Handle|[Aluminum Alloy Door Handle](https://nl.aliexpress.com/item/1407596513.html?spm=a2g0s.9042311.0.0.66fb4c4deTZEmA)|1|CAD shows printed door handle, I use this type of aluminum handle in size 120mm (ordered without screws and nuts)
Hinge|[HHPBSN5-SET](https://uk.misumi-ec.com/vona2/detail/110302362010/?HissuCode=HHPBSN5-SET&PNSearch=HHPBSN5-SET&KWSearch=HHPBSN5-SET&searchFlow=results2type)|2

## Skirts

![Skirts](Images/skirts.png)

### Specifics
- Basis is the hexagon skirts from the original DoomCube. 
- Due to side and back panel mounting system, flanges of the door are used all around as well as the panelmounts.
- Panelmounts are 2 pieces per side, instead of 3. This might not be printable on smaller bed sizes.
- Top and Bottom have altered top caps for the corners. These caps allow the deck panels to be attached to the corners with magnets.
- Top corners and skirts have been increased in size in order to accomodate my Waveshare 4,3" LCD. For this a center skirt was modded to hold the LCD.

### Hardware
Hardware|Part|QTY|Remarks
|:---:|:---:|:---:|:---:
4.3" LCD|[Waveshare 4.3" LCD DSI](https://www.waveshare.com/4.3inch-dsi-lcd.htm)|1|The Raspberry Pi can be screwed to the LCD screen
Power Inlet|[Schaffner FN-286](https://www.digikey.nl/product-detail/en/schaffner-emc-inc/FN286-1-06/817-1928-ND/1997125?utm_adgroup=Power%20Entry%20Connectors%20-%20Inlets%2C%20Outlets%2C%20Modules&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Product_Connectors%2C%20Interconnects&utm_term=&productid=1997125&gclid=CjwKCAjw7fuJBhBdEiwA2lLMYTt-iqS_a8Cr28pWmyBAhIXpcLJp1rsu5ffDzC7lFXPegO6_Ck0uYBoCgaoQAvD_BwE)|1

### Included Mods
Name|Creator|Description|Remarks
|:---:|:---:|:---:|
[FN-286 Plug Panel](../fn-286_plug_panel/)|mvieleers|Altered Plug Panel to hold the Schafnner FN-286 
[Corner Panel Mounts](../corner_panel_mounts/)|mvieleers|Modded upper and lower corner caps and square feet to attach the top and bottom deck panels to the feet with magnets.|For my personal build I use different (higher) feet on the top and therefor the upper corner caps are also different. These versions can be found under this Mod itself.

## Heated Bed

![Heated Bed](Images/heated_bed.png)

### Specifics
- Mandela Rose Works ultra flat bed is used. It has mounting holes for both the V1.8 and the V2.4. Therefor I'm able to use a triangle 3-point mounting method, by inserting a cross bar between the two bed extrusions. This is also done to accomodate for a kinematic mounting system that is in development with Mandela Rose Works and uses 3 mounting points.

## Z-Assembly

![Z Assembly](Images/z_assembly.png)

### Specifics
- Mostly utilizes DoomCube parts.
- Motor Mounts are taken from the DoomCube CAD, there are no stl's for this in the repository which implies to use the original V2.4 parts. Those have 3 mounting points though, I like the 4 mounting points better, so I created the stl from the DoomCube CAD.
- The belt covers are based on crag-something belt covers, I just added a somewhat different ledge to make a tighter integration to the panels.
- Cable cover for A drive by crag-something

## Gantry

![Gantry](Images/gantry.png)

### Specifics
- MGN 12 Mod Arkeet
- Pins Mod hartk
- Y relocation Mod hartk
- GE5C mod hartk

## X-Carriage

![X-Carriage](Images/x-carriage.png)

### Specifics
- klicky probe mod for x-carriage
- crag-something adxl mount (modded)
- hartk PCB
- majarspeed pcb mount for galileo
- jaredc01 galileo
- badnoob ab-bn-30
- Mosquito
- ERCF sensor for galileo, experimental version for v1.1 (to be released). Not in cad as there is only an stl.

## Electronics

![Electronics](Images/electronics.png)

### Specifics
- Wire grommet for passthrough of Tircowns ERCF easy board to the ERCF
- PTFE grommet for passthrough of PTFE from top deck panel to top panel
- PTFE and Umbilical grommet for passthrough of PTFE and Wires to the toolhead
- Wire grommet for the Z-chain wires
- Wire grommet for the wires trough the bottom panel to the bottom of the chamber
- All grommets are based on loco... wire grommet
- BED PCB for central connection of the wires at the bottom of the chamber. Bed Mains and Fuse, Bed Thermistor, Z Endstop, 2x bed fan or nevermore micro.
- DIN Mounts for BTT Octopus, Tircown's ERCF Easy Board, LRS-200-24

## Other

![Other](Images/other.png)

### Specifics
 - LED
 - Klicky Probe
 - hartk Sexbolt
 - Nevermore Duo, with modded plenum
 - Annex's purge bucket
 - Webcam mount for Wansview 1080o

## ERCF

![ERCF](Images/ercf.png)

### Specifics
 - 9 Channel ERCF. Number of channels irrelevant as I mount the ERCF to the extrusion.

#### A big thanks to all original authors for permission to include their mods in the Doomcube CAD!  Always follow the links to their respective repos for the latest stl's, and info on how to best make use of their mods.


