SquantorEagleLib
================

Personal component libraries for kicad.

I tend to seperate out my libraries per vendor as each usually have their own flavour of packaging.

Design Rules
============

General
=======
I try and keep everything metric as possible but usually grids are in imperial format, usually divisions/multiples of 1.27mm.
Here is a short overview of the design rules I use for various objects:
Font size: 1.27mm Width 1.27mm Height, 0.15mm Thickness

Components
==========
Reference on top, front silk screen, name REF**, centered on footprint
Value bottom, front fabrication layer, name footprint name, centered
grid: 0.127mm
Smaller size: 1.0mm
Through holes: metric, with 0.3mm annulus
IC's note pin 1 on front silk with small circle, 0.127mm radius
Keep 0.1mm solder mask clearance

TODO
====
Fix my own SMD package outlines, 0.1mm solder mask clearance around pads etc.


