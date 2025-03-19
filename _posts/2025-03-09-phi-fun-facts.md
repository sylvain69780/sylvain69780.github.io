---
layout: default
title : "Phi (the golden number) fun facts"
tags : shadertoy
---
## Questions

Which number can be found in the architecture, computer graphics, the 2D and 3D geometry of the pentagon and icosahedron, and French politics? 

This number is "Phi" !

## In architecture

I first heard about Phi, very pretentiously called "the golden number," in the field of architecture. I was a bit skeptical about the almost mystical use of this number, more or less convincingly, in many famous constructions like the Parthenon or the pyramids.

## In computer graphics!

The first surprise was learning that this very pretentious number is used in the field of computer graphics for harmoniously distributing points on a rectangle or a disc.

This number is unique in its ability to produce non-overlapping patterns, a corollary of the fact that it is the number with the slowest possible convergence in its continued fraction expansion. This contributes to the absence of cycles and overlaps in the patterns.

That's already super cool.

For this reason, it's interesting to have this value memorized.

$$
\Phi = \frac{1 + \sqrt{5}}{2}
$$

$$
\Phi \approx 1.618034
$$

$$
\frac{1}{\Phi} = \Phi - 1 \approx 0.618034
$$

$$
\Phi^2 = \Phi+1 \approx 2.618034
$$

## In 2D and 3D geometry!

<iframe width="400" height="300" frameborder="0" src="https://www.shadertoy.com/embed/wf23Wd?gui=true&t=10&paused=false&muted=false" allowfullscreen></iframe>

Shane, a well-known Shadertoy user, recently shared an intuitive method to construct an icosahedron using three perpendicular golden rectangles.

A golden rectangle is a rectangle whose side lengths are in the golden ratio, $ \Phi $. This means that the ratio of the longer side to the shorter side is $ \Phi $. If the longer side of the rectangle is \( a \) and the shorter side is \( b \), then:

$$
\frac{a}{b} = \Phi
$$

From the reading of Divine Proportion [Luca Pacioli 1509] we deduce that some mathematicians of that time knew the golden relationships in the icosahedron thoroughly !

One can construct a geometric figure with 2 dimensions a and b that fulfill the golden ratio relation $a/b = (a+b)/a$.

It turns out that this figure has by construction, angles of $ \frac{\pi}{5} rad$, $ \frac{\pi}{5} rad$, and $ \frac{3\pi}{5} rad$.

* Pentagons and Icosahedrons use PI/5 rad (36°) for their constructions.
* This explains why Phi equals 2 * cos(π/5).

[Construction using Desmos](https://www.desmos.com/geometry/c8ety52kpm)

By construction of these 2 isosceles triangles, $AC/AB = AB/AD = x$

Taking special case where $AB=1$ :
$$AC = x$$

$$AD = AC - AB = x - 1$$

$$AC/AB = AB/AD  \Leftrightarrow x = 1/(x-1)  \Leftrightarrow x*(x-1) = 1$$

We conclude that x is the positive solution of the equation $x^2 = x + 1$ and $x = \Phi$

You can also observe the relation : 

$$
\Phi = 2 \cdot \cos\left(\frac{\pi}{5}\right)
$$

<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="400" height="400"><defs/><g transform="scale(1,1)"><g id="background-979cbd5e"><rect fill="white" stroke="none" x="0" y="0" width="400" height="400" class="dcg-svg-background"/></g><g id="graphpaper-979cbd5e"><g id="axis-979cbd5e"><g><g><path fill="none" stroke="rgb(0,0,0)" class="dcg-svg-tickmark" paint-order="fill stroke markers" d="" stroke-opacity="0.9" stroke-miterlimit="2" stroke-width="1.5" stroke-dasharray=""/></g></g></g></g><g id="expressions-979cbd5e"><g id="sketch-979cbd5e"><title>C</title><path fill="#6042a6" stroke="none" class="dcg-svg-point" paint-order="stroke fill markers" d=" M 383.00559285339534 258.6025560942219 A 4 4 0 1 1 383.0055908533955 258.5985560948885 Z"/></g><g id="sketch-979cbd5e"><title>A</title></g><g id="sketch-979cbd5e"><title>B</title></g><g id="sketch-979cbd5e"><title>Expression 6</title><path fill="#c74440" stroke="none" class="dcg-svg-point" paint-order="stroke fill markers" d=" M 136.06956417050904 341.42897699742963 A 4 4 0 1 1 136.06956217050922 341.42497699809627 Z"/></g><g id="sketch-979cbd5e"><title>D</title><path fill="#6042a6" stroke="none" class="dcg-svg-point" paint-order="stroke fill markers" d=" M 161.45793593833545 260.6995616973012 A 4 4 0 1 1 161.45793393833563 260.69556169796783 Z"/></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#2d70b3" stroke="none" class="dcg-svg-region" paint-order="stroke fill markers" d=" M 20.533953836927765 261.99558243460314 L 198.53718437769686 130.07662384978758 L 379.00559285339534 258.6025560942219 L 20.533953836927765 261.99558243460314 L 20.533953836927765 261.99558243460314" fill-opacity="0.4"/><path fill="#2d70b3" stroke="none" paint-order="stroke fill markers" d="" fill-opacity="0.4"/><g><path fill="none" stroke="#2d70b3" class="dcg-svg-curve" paint-order="fill stroke markers" d=" M 20.533953836927765 261.99558243460314 L 20.533953836927765 261.99558243460314 L 198.53718437769686 130.07662384978758 L 379.00559285339534 258.6025560942219 L 20.533953836927765 261.99558243460314" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-width="2.5" stroke-dasharray=""/></g></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#2d70b3" stroke="none" class="dcg-svg-region" paint-order="stroke fill markers" d=" M 198.53718437769686 130.07662384978758 L 157.45793593833545 260.6995616973012 L 20.533953836927765 261.99558243460314 L 198.53718437769686 130.07662384978758 L 198.53718437769686 130.07662384978758" fill-opacity="0.4"/><path fill="#2d70b3" stroke="none" paint-order="stroke fill markers" d="" fill-opacity="0.4"/><g><path fill="none" stroke="#2d70b3" class="dcg-svg-curve" paint-order="fill stroke markers" d=" M 198.53718437769686 130.07662384978758 L 198.53718437769686 130.07662384978758 L 157.45793593833545 260.6995616973012 L 20.533953836927765 261.99558243460314 L 198.53718437769686 130.07662384978758" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-width="2.5" stroke-dasharray=""/></g></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#2d70b3" stroke="none" paint-order="stroke fill markers" d="" fill-opacity="0.4"/><g><path fill="none" stroke="#2d70b3" class="dcg-svg-curve" paint-order="fill stroke markers" d=" M 198.53718437769686 130.07662384978758 L 132.06956417050904 341.42897699742963" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-width="2.5" stroke-dasharray=""/></g></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#2d70b3" stroke="none" paint-order="stroke fill markers" d="" fill-opacity="0.4"/><g><path fill="none" stroke="#2d70b3" class="dcg-svg-curve" paint-order="fill stroke markers" d=" M 109.53556910731231 196.03610314219537 L 157.45793593833545 260.6995616973012" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-width="2.5" stroke-dasharray=""/></g></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#2d70b3" stroke="none" paint-order="stroke fill markers" d="" fill-opacity="0.4"/><g><path fill="none" stroke="#2d70b3" class="dcg-svg-curve" paint-order="fill stroke markers" d=" M 199.76977334516155 260.29906926441254 L 198.53718437769686 130.07662384978758" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-width="2.5" stroke-dasharray=""/></g></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#000000" stroke="none" paint-order="stroke fill markers" d="" fill-opacity="0.4"/><g><path fill="#000000" stroke="none" class="dcg-svg-curve" paint-order="stroke fill markers" d=" M 20.533953836927765 261.99558243460314 L 40.533057986142566 261.80628576569933 L 40.533057986142566 261.80628576569933 A 19.99999999999997 20 0 0 0 36.6023031756273 250.0872597345117 L 20.533953836927765 261.99558243460314" fill-opacity="0.4"/><path fill="none" stroke="#000000" class="dcg-svg-curve" paint-order="fill stroke markers" d=" M 40.533057986142566 261.80628576569933 A 19.99999999999997 20 0 0 0 36.6023031756273 250.0872597345117 M 50.532610060749974 261.71163743124737 L 20.533953836927765 261.99558243460314 L 44.636477844977065 244.13309838446594" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-width="1.5" stroke-dasharray="" stroke-opacity="0.2"/></g></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#000000" stroke="none" paint-order="stroke fill markers" d="" fill-opacity="0.4"/><g><path fill="#000000" stroke="none" class="dcg-svg-curve" paint-order="stroke fill markers" d=" M 198.53718437769686 130.07662384978758 L 182.46883503899733 141.98494654987903 L 182.46883503899733 141.98494654987903 A 19.99999999999997 20 0 0 0 214.82806529697592 141.6786581056355 L 198.53718437769686 130.07662384978758" fill-opacity="0.4"/><path fill="none" stroke="#000000" class="dcg-svg-curve" paint-order="fill stroke markers" d=" M 182.46883503899733 141.98494654987903 A 19.99999999999997 20 0 0 0 214.82806529697592 141.6786581056355 M 174.43466036964756 147.93910789992478 L 198.53718437769686 130.07662384978758 L 222.97350575661545 147.47967523355945" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-width="1.5" stroke-dasharray="" stroke-opacity="0.2"/></g></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#000000" stroke="none" paint-order="stroke fill markers" d="" fill-opacity="0.4"/><g><path fill="#000000" stroke="none" class="dcg-svg-curve" paint-order="stroke fill markers" d=" M 379.00559285339534 258.6025560942219 L 362.7147119341163 247.00052183837397 L 362.7147119341163 247.00052183837397 A 19.99999999999997 20 0 0 0 359.0064887041805 258.7918527631257 L 379.00559285339534 258.6025560942219" fill-opacity="0.4"/><path fill="none" stroke="#000000" class="dcg-svg-curve" paint-order="fill stroke markers" d=" M 362.7147119341163 247.00052183837397 A 19.99999999999997 20 0 0 0 359.0064887041805 258.7918527631257 M 354.56927147447675 241.19950471045 L 379.00559285339534 258.6025560942219 L 349.00693662957315 258.8865010975776" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-width="1.5" stroke-dasharray="" stroke-opacity="0.2"/></g></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#000000" stroke="none" paint-order="stroke fill markers" d="" fill-opacity="0.4"/><g><path fill="#000000" stroke="none" class="dcg-svg-curve" paint-order="stroke fill markers" d=" M 198.53718437769686 130.07662384978758 L 192.53715315378892 149.15539805863364 L 192.53715315378892 149.15539805863364 A 19.99999999999997 20 0 0 1 182.46883503899733 141.98494654987903 L 198.53718437769686 130.07662384978758" fill-opacity="0.4"/><path fill="none" stroke="#000000" class="dcg-svg-curve" paint-order="fill stroke markers" d=" M 192.53715315378892 149.15539805863364 A 19.99999999999997 20 0 0 1 182.46883503899733 141.98494654987903 M 189.53713754183494 158.69478516305668 L 198.53718437769686 130.07662384978758 L 174.43466036964756 147.93910789992475" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-width="1.5" stroke-dasharray="" stroke-opacity="0.2"/></g></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#c74440" stroke="none" class="dcg-svg-point" paint-order="stroke fill markers" d=" M 202.53718437769686 130.07662384978758 A 4 4 0 1 1 202.53718237769704 130.07262385045425 Z"/></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#6042a6" stroke="none" class="dcg-svg-point" paint-order="stroke fill markers" d=" M 113.53556910731231 196.03610314219537 A 4 4 0 1 1 113.53556710731247 196.03210314286204 Z"/></g><g id="sketch-979cbd5e"><title>Expression 1</title><path fill="#6042a6" stroke="none" class="dcg-svg-point" paint-order="stroke fill markers" d=" M 203.76977334516155 260.29906926441254 A 4 4 0 1 1 203.76977134516173 260.2950692650792 Z"/></g></g><g id="labels-979cbd5e"><g transform="rotate(0,0,0) translate(389,251)"><g class="dcg-svg-label"><text fill="none" stroke="#FFF" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="2" stroke-width="3" stroke-dasharray="">C</text><text fill="rgb(96, 66, 166)" stroke="none" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start">C</text></g></g><g transform="rotate(0,0,0) translate(16,231)"><g class="dcg-svg-label"><text fill="none" stroke="#FFF" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="2" stroke-width="3" stroke-dasharray="">A</text><text fill="rgb(96, 66, 166)" stroke="none" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start">A</text></g></g><g transform="rotate(0,0,0) translate(217,122)"><g class="dcg-svg-label"><text fill="none" stroke="#FFF" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="2" stroke-width="3" stroke-dasharray="">B</text><text fill="rgb(199, 68, 64)" stroke="none" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start">B</text></g></g><g transform="rotate(0,0,0) translate(162,266)"><g class="dcg-svg-label"><text fill="none" stroke="#FFF" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="2" stroke-width="3" stroke-dasharray="">D</text><text fill="rgb(96, 66, 166)" stroke="none" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start">D</text></g></g><g transform="rotate(0,0,0) translate(45,242)"><g class="dcg-svg-label"><text fill="none" stroke="#FFF" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="2" stroke-width="3" stroke-dasharray="">36°</text><text fill="rgb(0, 0, 0)" stroke="none" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start">36°</text></g></g><g transform="rotate(0,0,0) translate(183,154)"><g class="dcg-svg-label"><text fill="none" stroke="#FFF" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="2" stroke-width="3" stroke-dasharray="">108°</text><text fill="rgb(0, 0, 0)" stroke="none" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start">108°</text></g></g><g transform="rotate(0,0,0) translate(331,239)"><g class="dcg-svg-label"><text fill="none" stroke="#FFF" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="2" stroke-width="3" stroke-dasharray="">36°</text><text fill="rgb(0, 0, 0)" stroke="none" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start">36°</text></g></g><g transform="rotate(0,0,0) translate(165,153)"><g class="dcg-svg-label"><text fill="none" stroke="#FFF" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="2" stroke-width="3" stroke-dasharray="">36°</text><text fill="rgb(0, 0, 0)" stroke="none" font-family="arial, sans-serif" font-size="15.4px" font-style="normal" font-weight="400" text-decoration="normal" x="0" y="12.4888" text-anchor="start">36°</text></g></g></g><path fill="#6042a6" stroke="none" class="dcg-svg-point" paint-order="stroke fill markers" d=" M 24.533953836927765 261.99558243460314 A 4 4 0 1 1 24.533951836927933 261.9915824352698 Z"/><path fill="#c74440" stroke="none" class="dcg-svg-point" paint-order="stroke fill markers" d=" M 202.53718437769686 130.07662384978758 A 4 4 0 1 1 202.53718237769704 130.07262385045425 Z"/><g id="labels-979cbd5e"/></g></svg>

## In French politics!

It's worth noting that Phi is also the symbol used by the **LFI (La France Insoumise)**, a French ultra-left party. This association is unfortunate, as it links such a remarkable mathematical constant to a political group that some may find disagreeable.

### References 

[Golden ratio - Wikipedia](https://en.wikipedia.org/wiki/Golden_ratio)

[Golden rectangle - Wikipedia](https://en.wikipedia.org/wiki/Golden_rectangle)

[GM Shaders Mini: Phi](https://open.substack.com/pub/xordev/p/phi?r=2ib59b&utm_campaign=post&utm_medium=email)

[almanach ou dictionnaire des nombres - curiosités et propriétés](http://villemin.gerard.free.fr/)

[ICOSAHEDRON AND Ф](http://www.polyhedra-world.nc/stuff/gold_icosahedron.pdf)

[The exact value of cos(π/5) (Geometric Proof)](https://www.youtube.com/watch?v=NKhvO1uVvEM)

<iframe width="400" height="300" frameborder="0" src="https://www.shadertoy.com/embed/Wlcfz4?gui=false&t=10&paused=false&muted=false" allowfullscreen></iframe>
