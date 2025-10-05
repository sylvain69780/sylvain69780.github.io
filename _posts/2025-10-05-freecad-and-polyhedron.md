---
layout: default
title : "Rhombic Dodecahedron using FreeCAD"
tags : freeCAD
---
# Réaliser dodédécahedres rombiques à l'aide de freecad

Vous êtes peutêtre comme moi complètement débutant avec FreeCAD qui est un outil de conception parametrique extremement puissant.

Je voulais aller plus loin dans la modélisation de mes pièces de puzzle en testant un assemblage dans freeCAD.

Voir pour cela mon [autre article]({% post_url _posts\2021-06-05-dihedral-angle-and-the-spider-slider-puzzle %}) sur le puzzle dit "spider slider". 

Pour cela il fallait que je modélise un dodécahedre Rhombique pour pouvoir y positionner mes picèes.

![preview](/assets/download/freecad/rhombic-dodecahedron.png)

Je met à dispo le [fichier freeCAD](/assets/download/freecad/rhombic-dodecahedron.FCStd) qui m'a permis de le faire.

* Créer un cube dans part design
* Positionner des plans de construction sur les trois arretes exterieurs, ces plans doivent être inclinés à 45 degres par rapport aux faces.
* Utiliser "pocket" pour soustraite ces plans au cube, sur une profondeur de $\frac{\sqrt{2}}{2}$ fois la taille d'un arrête.
* Utiliser 3 fois un mirroir pour rendre la pièce symétriques sur les trois axes X Y et Z.

