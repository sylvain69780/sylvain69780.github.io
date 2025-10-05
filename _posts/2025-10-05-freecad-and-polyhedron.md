---
layout: default
title : "Rhombic Dodecahedron using FreeCAD"
tags : freeCAD
---
# Creating Rhombic Dodecahedrons with FreeCAD

If you're like me, a complete beginner with FreeCAD, you'll find it's an extremely powerful parametric design tool.

I wanted to take my puzzle piece modeling further by testing an assembly in FreeCAD.

See my [other article](https://sylvain69780.github.io/2021/06/05/dihedral-angle-and-the-spider-slider-puzzle.html) about the "spider slider" puzzle.

To do this, I needed to model a Rhombic Dodecahedron to position my pieces.

![preview](/assets/download/freecad/rhombic-dodecahedron.png)

I'm sharing the [FreeCAD file](/assets/download/freecad/rhombic-dodecahedron.FCStd) I used to create it.

* Create a cube in Part Design.
* Place construction planes on the three outer edges; these planes should be tilted at 45 degrees relative to the faces.
* Use "pocket" to subtract these planes from the cube, to a depth of $\frac{\sqrt{2}}{2}$ times the edge length.
* Use the mirror tool three times to make the piece symmetrical along the X, Y, and Z axes.
