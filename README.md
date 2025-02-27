# sculptura ☆.ᐟ

> username: @arsoninstigator aka @anne on the slack (she/her) <br>
> here's the printer's [github repository](https://arsoninstigator/sculptura) and the main [infill page](https://infill.hackclub.com/printers/sculptura/) <br>
> total time spent on this till date: 17.2 hours (as of 21/2)
- [X] i currently / will have access to a 3d printer before 21st march (bambu a1 mini)

sculptura is a wip fully **open-source** and customized budget 3d printer made from scratch for printing smooth, detailed and precise models that are meant to to be used as high quality decorative pieces (like you would see at an art gallery) :D


## planning
<img src="https://www.mdpi.com/polymers/polymers-14-04659/article_deploy/html/images/polymers-14-04659-g001.png">

### ⋆ overview
- build volume: ~220x220x250mm
- multi-color & silent operation
- doesn't start on fire
- costs <250$ excluding costs of filament (im working with a bambu lab a1 mini)
- designed for printing functional decorative pieces over the industrial applications

### ⋆ desired specifications
- rigid braced aluminum frame + improved stability (wrt ender3 v3se)
- higher print resolution (0.1mm layer height capability)
- prints pla (silk, matte, wood, marble, metal-infused), transparent petg, tpu
- cartesian (since we need precise extrusion control and cooling rather than raw speed)
- smooth motion system + linear rails (if budget permits)
- runs klipper

## bill of materials
im currently researching stuff to make a comprehensive bom with everything i would require to make my printer come to life

## daily log
### ⋆ day one - initial research (time taken - 3 hours + ½ hour for readme)
started my journey by researching different 3D printer motion systems. the main types i considered were corexy, cartesian, and delta. after watching multiple comparison videos and reading user reviews, i decided on corexy and explored some popular diy corexy builds to understand potential designs:
- **[voron 0.1](https://vorondesign.com/voron0)** – super cool & compact
- **[vzbot](https://github.com/VZBot3D/VZBot)** – too complex and expensive
- **[ratrig v-core 3](https://ratrig.com/)** – over budget

### ⋆ day two -  frame & motion system (time taken - 3 hours)
to ensure stability while keeping costs low, i chose 2040 aluminum extrusions for the frame, offering a solid balance between rigidity and weight. for motion, i debated between <ins>linear rails</ins> (provide high precision and smooth movement but expensive) and <ins>pom wheels</ins> (budget-friendly and simpler to install but wear down over time). <br> <br> 
after reviewing multiple builds and cost analyses, i decided to start with pom wheels, knowing i can upgrade to linear rails later if needed. <br><br>
helpful video: [pom wheels vs. linear rails](https://youtu.be/9LVSXidVbzE?si=kI6JSTTjm1Ju_WpN)

### ⋆ day three - extruder & hotend (time taken - 2 hours)
choosing the right extruder and hotend was crucial for handling various filament types, especially for multicolor printing. i considered the bmg clone (affordable, reliable, and widely used) and orbiter 2.0 (higher filament grip and better retraction control, reducing stringing) extruders and opted for <ins>orbiter 2.0</ins> for its improved grip and lightweight design. 

for the hotend, i needed something all-metal to handle a range of filaments (pla, petg, tpu, etc.). i chose the <ins>e3d v6 clone</ins>, as it provides good heat dissipation and consistent extrusion without ptfe degradation.

### ⋆ day four - heated bed & printed surface
a heated bed is essential for improving first-layer adhesion and preventing warping, especially when printing with materials like petg and abs. i needed a bed that could heat quickly and evenly across the surface, so i researched different heating solutions: pcb heater beds affordable but uneven heat distribution, silicone heater pads (expensive) and aluminium heated beds (good heat retention + even heating). after comparing options, i decided on a 12v or 24v heated bed with an aluminum plate, as its cheaper and durable.

a quality print surface is essential for good first-layer adhesion. i compared options of a glass bed (that's smooth but requires adhesive for some filaments) and pei-coated spring steel (that's flexible, durable w better adhesion) and textured powder coated pei (first-layer adhesion and provides a textured bottom layer) and chose the pei-coated spring steel sheet for easy print removal.

reference video - [guide to pei 3d printer beds](https://youtu.be/Z7LK28tL028?si=_4-VgD_tuooDlpQ8)

