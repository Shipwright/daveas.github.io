---
layout: project
title: Tobacco Pipe
date: 2015-01-01
category: Engineering, Design
tags:
- 3D CAD
- Prototyping
- Wood
- Plastic
- Product Design
- Mechanical Engineering
excerpt: "Since I started to smoke a pipe in 2010 I have wanted to design one for myself. Smoking is such an intimate and yet unchanged experience. Pipe smoking itself really hasn't changed for hundreds if not thousands of years. I found it hard tobelieve that modern materials and manufacturing did not have anything to add to the experience."
published: true
dir: tobacco-pipe/
---

### Research

There is a lot to know about pipes before you intend to make one of any kind. But to start off, I had to learn the basic parts of pipe, as pictured below:
![pipe parts]({{site.images}}{{ page.dir }}1.jpg)[^1]

Number | Part | Function
:---: | :--- | :---
1 | Bowl | Outer wall that holds the tobacco
2 | Chamber | Space within bowl that tobacco occupies
3 | Draught Hole | Allows passage of smoke into the bore and keeps tobacco dry
4 | Shank | Section between Bowl and Stem that shelters the Mortise  
5 | Mortise | Made to fit the outside diameter of the Tennon
6 | Tennon | Made to fit the inside diameter of the Mortise
7 | Stem | Piece with protruding Tennon, connects the Shank and Mouthpiece
8 | Mouthpiece | Made to fit the lips of the smoker
9 | Lip | Ridge made to fit inside the lip or on teeth for stability
10 | Bore | The through hole for the smoke from the chamber

<div>Tap the file icons <label class="collapse" for="_1"><i class="fa fa-files-o"></i></label><input id="_1" type="checkbox"> to show the papers I studied for this project.
<div style="width:100%">
<iframe class="scribd_iframe_embed" src="https://www.scribd.com/embeds/267145533/content?start_page=1&view_mode=scroll&show_recommendations=true" data-auto-height="false" data-aspect-ratio="undefined" scrolling="no" class="scribds" frameborder="0"></iframe>
<iframe class="scribd_iframe_embed" src="https://www.scribd.com/embeds/267145535/content?start_page=1&view_mode=scroll&show_recommendations=true" data-auto-height="false" data-aspect-ratio="undefined" scrolling="no" class="scribds" frameborder="0"></iframe>
</div>
</div>

---

Every part of the pipe must be very carefully designed to optimize the burning of the tobacco and the comfort and aesthetic of the object itself. The documenst above, "Characteristics of Briar Wood"[^2] and "On the Burning Temperatures of Tobacco"[^3] were (and still are) extraordinarily helpful in designing the pipe. Specifically in understanding how the pipe's dimensions affect the smoking quality of the pipe from the chamber diameter and depth to the thickness of the bowl and the diameter of the Draught Hole and Bore.

The bowl material and chamber dimensions are particularly important because they not only affect the feel of the object in your hand and its loft as you hold it in your mouth but the the quality of the smoke. The right dimensions allow the tobacco to burn as cool as possible without losing the "cherry" - the ongoing combustion of the tobacco. Below you can see the different zones in the chamber and get a better idea for how dimensions affect smoke quality and makeup:

![chamber zones]({{site.images}}{{ page.dir }}2.jpg)[^4]

My first design is a fairly common 3/4" pipe bowl with a 1 1/4" deep chamber and a minimum wall thickness of 3/16". Once I get past the aesthetic design I will have to create several prototypes at different sizes and test them for temperature and humidity. I plan to make a rig that will pull a constant flow rate directly from the shank.

---

### Aesthetic & Interaction Design

Some of my inital brainstorming drawings are below. You can see that aside from considering patentability I started off experimenting with asymetrical designs. I noticed while assmbling my Dyson that this is one of their key features of every part which made it a pleasure to put together. You will also see that I plan to use magnets and some sort of gasket seal to join the shank to the stem without the use of a mortise & tennon. There are three reasons for this:

1. Upon heating the briar portion of the pipe expands and squeezes the tennon. This stress overtime can crack the pipe, and forces savvy pipe smokers to wait for the pipe to cool before dissassembly and cleaning.
2. The user experience of squeezing the two pieces together and pulling them apart is cumbersome. I am a huge fan of magnets in interaction design like the Apple magcharger and I think a snap together stem & shank would be more simple
3. Diameterical tolerancing of the shank, mortise, tennon, and stem drives up the price barrier to produce finer pipes. This closure would allow you to focus only on the outer diameter of two pieces.

Asymmetric drawing:
![asymmetric design]({{site.images}}{{ page.dir }}3.jpg)

(Ugly) Foamcore model:
![asymmetric design]({{site.images}}{{ page.dir }}5.jpg)

Considering IP, if any:
![patentability]({{site.images}}{{ page.dir }}4.jpg)

I am a big fan of using natural numbers in design like e, pi, and phi. In the drawing below you can see I used the golden ratio (phi) to construct the almost wine-glass-like silhouette of the pipe bowl:
![golden ratio]({{site.images}}{{ page.dir }}6.jpg)

### Drafting and Prototyping

One of the pipes that I find inspring is the [Stiff Pipe](http://stiffonline.com). This company likes to use plastic as a material and they created a molded thermoplastic pipe body with a briar core, something which I definitely plan to experiment with. As pipes become somewhat popular again as a relic of a more masculine stoic age, I think a few craft pipe makers using new materials and techniques might be able to make a decent business serving a new demographic of pipe smoker. As an admirer, I took a digital ruler and used evernote to see what dimensions Stiff was using to see if I could gleam any insight.
![Stiff Pipe Measured]({{site.images}}{{ page.dir }}7.jpg)

Here a photo rendering of the first asymmetric based design I made in Solidworks:
![Pipe Rendering]({{site.images}}{{ page.dir }}10.jpg)

Eventually I realized I could place the magnets asymetrically and allow for a symmetric body which I thought was more visually appealing. As I got ready to 3D print a model I checked the printing tolerances:
![Pipe Rendering]({{site.images}}{{ page.dir }}8.jpg)

### Status

This project is currently underway, so as it continues I will update this post with sketches, models, renderings, prototypes, and eventually with the product itself.

You can view and edit the most recent version of this project [here](https://cad.onshape.com/documents/a00b2e67daf64aad90f84bce/w/7c1cec4a0ec24249843c3a42).

---

### Associated Products

My love for pipe smoking now has me interested in a suite of complementary products. I am considering an automated tobacco blending machine and a web and mobile app to order custom blends to your door. I also played around with a custom lighter and this tamp with a screw-set spring mechanism that would relieve at a set force to tamp tobacco uniformly:
![Custom Tamp]({{site.images}}{{ page.dir }}9.jpg)

---

[^1]: [Pipe Parts image credit](http://en.wikipedia.org/wiki/Tobacco_pipe)
[^2]: [G. Tsoumis, N. Kezos, I. Fanariotou, E. Voulgaridis and C. Passialis](http://pipedia.org/docs/CharacteristicsOfBriar.pdf)
[^3]: [Pentti Ermala and Lars R. Holsti](http://cancerres.aacrjournals.org/content/16/6/490.abstract)
[^4]: [Chamber Zones image credit](http://passionforpipes.squarespace.com/classic-blog-posts/the-thermodynamics-of-pipe-smoking.html)
