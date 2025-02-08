# sculptura ☆.ᐟ

sculptura is a wip fully **open-source** and customized budget 3d printer made by @anne **from scratch** for slow printing smooth and precise models to be used as decorative pieces :D

## planning

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



