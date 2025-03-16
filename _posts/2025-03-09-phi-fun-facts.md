---
layout: default
title : "Phi (the golden number) fun facts"
tags : shadertoy
---
## Questions

Which number can be found in the architecture of the most beautiful constructions, computer graphics for uniform pattern distributions on a surface, the 2D and 3D geometry of the pentagon and icosahedron, and French politics? 

This "WTF !" number is "Phi".

## In architecture

I first heard about Phi, very pretentiously called "the golden number," in the field of architecture. I was a bit skeptical about the almost mystical use of this number, more or less convincingly, in many famous constructions like the Parthenon or the pyramids.

## In computer graphic ??

The first surprise was learning that this very pretentious number is used in the field of computer graphics for reproducing natural forms like flowers or harmoniously distributing points on a rectangle. That's already super cool.

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

## In the 3d construction of the Icosahedron ???

<iframe width="640" height="360" frameborder="0" src="https://www.shadertoy.com/embed/wf23Wd?gui=true&t=10&paused=false&muted=false" allowfullscreen></iframe>

Shane, a well-known Shadertoy user, recently shared an intuitive method to construct an icosahedron using three perpendicular golden rectangles.

A golden rectangle is a rectangle whose side lengths are in the golden ratio, \( \Phi \). This means that the ratio of the longer side to the shorter side is \( \Phi \), approximately 1.618. If the longer side of the rectangle is \( a \) and the shorter side is \( b \), then:

$$
\frac{a}{b} = \Phi
$$

From the reading of Divine Proportion [Luca Pacioli 1509] we deduce that some mathematicians of that time knew the golden relationships in the icosahedron thoroughly !

The reason is that one can construct a triangle with a similar inscribed triangle, and through this construction, one can find the definition of the golden ratio. It turns out that this triangle has angles of \( \frac{\pi}{5} \), \( \frac{\pi}{5} \), and \( \frac{3\pi}{5} \).

These are angles we can find the pentagons and Icosahedras.

This also explains why Phi equals 2 * cos(π/5).

$$
\Phi = 2 \cdot \cos\left(\frac{\pi}{5}\right)
$$

<svg width="400" height="200" viewBox="0 0 400 200" xmlns="http://www.w3.org/2000/svg">
    <rect width="400" height="200" fill="white"/>
    <polygon points="200,80 390,190 10,190" fill="none" stroke="black" stroke-width="2"/>
    <line x1="120" y1="190" x2="200" y2="80" stroke="black" stroke-width="2"/>
    <text x="80" y="100" font-family="Arial" font-size="24" fill="black">1</text>
    <text x="310" y="100" font-family="Arial" font-size="24" fill="black">1</text>
    <text x="200" y="180" font-family="Arial" font-size="24" fill="black">Phi</text>
    <text x="170" y="140" font-family="Arial" font-size="24" fill="black">phi</text>
    <text x="70" y="180" font-family="Arial" font-size="18" fill="black">PI/5 rad (36°)</text>
    <path d="M 50 190 A 20 20 0 0 0 40 170" fill="none" stroke="black" stroke-width="2"/>
</svg>

## In French politics ????

It's worth noting that Phi is also the symbol used by the *LFI (La France Insoumise), a French ultra-left party*. This association is unfortunate, as it links such a remarkable mathematical constant to a political group that some may find disagreeable.

### References 

[Golden ratio - Wikipedia](https://en.wikipedia.org/wiki/Golden_ratio)
[GM Shaders Mini: Phi](https://open.substack.com/pub/xordev/p/phi?r=2ib59b&utm_campaign=post&utm_medium=email)
[almanach ou dictionnaire des nombres - curiosités et propriétés](http://villemin.gerard.free.fr/)
[ICOSAHEDRON AND Ф](http://www.polyhedra-world.nc/stuff/gold_icosahedron.pdf)
[The exact value of cos(π/5) (Geometric Proof)](https://www.youtube.com/watch?v=NKhvO1uVvEM)

<iframe width="640" height="360" frameborder="0" src="https://www.shadertoy.com/embed/Wlcfz4?gui=false&t=10&paused=false&muted=false" allowfullscreen></iframe>
