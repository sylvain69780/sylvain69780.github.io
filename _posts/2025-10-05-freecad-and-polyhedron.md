---
layout: default
title : "Rhombic Dodecahedron using FreeCAD"
tags : freeCAD
---
# Creating Rhombic Dodecahedrons with FreeCAD

If you're like me, a complete beginner with FreeCAD, you'll find it's an extremely powerful parametric design tool.

I wanted to take my puzzle piece modeling further by testing an assembly in FreeCAD.

See my [other article](https://sylvain69780.github.io/2021/06/05/dihedral-angle-and-the-spider-slider-puzzle.html) about the [Scorpius](https://puzzleworld.org/PuzzleWorld/puz/scorpius.htm) wood puzzle.

The photo below shows the model I own, which is the "Spider Slider" version without any beveled parts.  
It is said that Stewart Coffin only produced 20 of these, which seems quite surprising to me.

![preview](https://static.blog4ever.com/2008/06/213622/artfichier_213622_8769121_202010012502419.png)

To do this, I needed to model a Rhombic Dodecahedron to position my pieces.

![preview](/assets/download/freecad/rhombic-dodecahedron.png)

I'm sharing the [FreeCAD file](/assets/download/freecad/rhombic-dodecahedron.FCStd) I used to create it.

* Create a cube in Part Design.
* Place construction planes on the three outer edges; these planes should be tilted at 45 degrees relative to the faces.
* Use "pocket" to subtract these planes from the cube, to a depth of $\frac{\sqrt{2}}{2}$ times the edge length.
* Use the mirror tool three times to make the piece symmetrical along the X, Y, and Z axes.

# Going Further

Here are the FreeCAD files for constructing the Scorpius puzzle.

[Parscorpius_part.FCStdt](/assets/download/freecad/scorpius_part.FCStd)

[rhombic-dodecahedron.FCStd](/assets/download/freecad/rhombic-dodecahedron.FCStd)

[scorpius_assembly.FCStd](/assets/download/freecad/scorpius_assembly.FCStd)

![preview](/assets/download/freecad/scorpius.png)

![preview](/assets/download/freecad/assembly.png)


# References

* [FreeCAD 0.19 Débutant : Datum Plane et système de coordonnées local](https://youtu.be/0PSiFiA2JxI?si=HPDgam6RddYEOJev)
* [FreeCAD débutant : Formes liées ou "ShapeBinder"](https://youtu.be/KYD9Ojugi8Q?si=J5p7QfEHfU3QuErc)
* [Icosahedron using FreeCAD in under 5 min](https://www.youtube.com/watch?v=tm-JiVusZPA&t=12s)
* [Regular and Rhombic Dodecahedrons (less than 4 minutes)](https://www.youtube.com/watch?v=yNe30vjTsnA)
