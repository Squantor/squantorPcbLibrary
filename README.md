# squantorPcbComponentLibrary
Personal component libraries for kicad.

I tend to seperate out my libraries per vendor as each usually have their own flavour of packaging.

## Design Rules

### General
I try and keep everything metric as possible but usually grids are in imperial format, usually divisions/multiples of 1.27mm.
Here is a short overview of the design rules I use for various objects:
* Font size: 0.8mm Width 0.8mm Height, 0.15mm Thickness
* Silkscreen lines are 0.15mm thick
* Version string: VYYYYMMDD

### Symbols
* Symbol designator top using the standard symbol designators from wikipedia, Centered on footprint
* Symbol name below, centered on footprint
* Pin, two grid points long
* Pins placed on package item also on two gridpoints layout

### Components
* Reference on top, front silk screen, name REF, centered on footprint, keep designators off the courtyard
* Value bottom, front fabrication layer, name footprint name, centered
* grid: 0.1mm
* Through holes: metric, with 0.4mm annulus (fits aisler low cost design rules)
* SMD IC's note pin 1 on front silk with some silk lines placed on keepout, a small L shape or full enclosed
* Keep 0.1mm solder mask clearance
* Through hole IC's and connectors, square pin 1.
* Pads are rounded rectangles with 0.2mm chamfer
* Courtyard thickness is 0.05mm

## TODO

