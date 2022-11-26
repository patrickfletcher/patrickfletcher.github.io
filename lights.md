---
layout: default
title: lights
permalink: /lights/
---

# LED light projects
  
Here are a few LED-based projects I've been working on! Not for sale at this time.

## Triangular LED panels

<p style="text-align:center;">
<img src="{{ site.url }}/assets/led/LED_10_triangle_top cropped.png" alt="Equilateral triangle with 10 LEDs - KiCad"  style="width: 50%"/>
<img src="{{ site.url }}/assets/led/single triangle.jpg" alt="Equilateral triangle with 10 LEDs - realized"  style="width: 45%"/>
</p>

I designed these triangular LED panels to light my [icosahedral lantern](#icosahedral-lantern). Each custom printed circuit board has 10 individually addressable RGB LEDs (WS2812b), and multiple panels can be chained together into flat arrays or 3D shapes.

## Icosahedral Lantern

<p style="text-align:center;">
<img src="{{ site.url }}/assets/led/lantern in bank window.jpg" alt="Icosahedral lantern at the Takoma Park Bank"  style="width: 100%"/>
</p>

*An icosahedral lanterns displayed at the [Market at the Bank](https://www.marketatthebank.com/) in Takoma Park, MD.*

A [regular icosahedron](https://en.wikipedia.org/wiki/Regular_icosahedron) is made up of 20 equilateral triangles. This lantern is made up of two layers: an outer layer of laser-cut wooden triangles, lit from within by a second set of 20 [triangular LED panels](#triangular-led-panels). The icosahedra are held together with 3D printed corner connectors. 

<p style="text-align:center;">
<img src="{{ site.url }}/assets/led/lantern open.jpg" alt="Icosahedral lantern - internal view"  style="width: 100%"/>
</p>

The pattern on the outer layer is an example of a reaction diffusion pattern - specifically, I simulated the Gray-Scott equations on the surface of an icosahedron using [Ready](https://github.com/GollyGang/ready). To play with these patterns interactively, check out [Robert Munafo's Gray Scott Explorer](http://mrob.com/pub/comp/xmorphia/ogl/index.html).

The LEDs are driven using the excellent [Pixelblaze v3 controller](https://www.bhencke.com/pixelblaze).

## PorthoLED

<p style="text-align:center;">
<img src="{{ site.url }}/assets/led/portholes.jpg" alt="A pair of LED portholes displayed at the Market at the Bank in Takoma Park, MD"  style="width: 100%"/>
</p>

*A pair of LED portholes displayed at the [Market at the Bank](https://www.marketatthebank.com/) in Takoma Park, MD.*

These colorful light fixtures are lit with flat arrays of my [triangular LED panels](#triangular-led-panels). The small one has 6 triangles and the large one has 13.  These panels are also driven by [Pixelblaze v3 controllers](https://www.bhencke.com/pixelblaze) and the Pixelblaze sensor board expansion, which includes a microphone for sound-reactive effects.

<p style="text-align:center;">
<img src="{{ site.url }}/assets/led/hex open.jpg" alt="inside the small porthole - 6 LED triangles in a hexagonal array"  style="width: 100%"/>
</p>

*inside the small porthole - 6 LED triangles in a hexagonal array*

<p style="text-align:center;">
<img src="{{ site.url }}/assets/led/trihex open.jpg" alt="inside the large porthole - 13 LED triangles in a hexagonal array"  style="width: 100%"/>
</p>

*inside the large porthole - 13 LED triangles in a hexagonal array*