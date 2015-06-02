---
layout: project
title: Planetary Gear System
date: 2015-03-08
category: Engineering
tags:
- 3D CAD
- Mechanical Engineering
- Plastic
- Metal
excerpt: "This planetary gear system was part of a project in my 3D CAD class in college. The gears were cut with a waterjet and a chassis was created to rotate the gears in different variations. The gears were designed from scratch using an involut curve to profile the gear tooth."
published: true
dir: gear-system/
---

### The Involute Gear Tooth

Drawing the actual curve of the involute tooth was the hardest part of this project. Since this will not be a highly technical post I will not go into the involute curve in great detail but will instead provide you with some additional reading below if it peaks your interest.

<div>Tap the file icons <label class="collapse" for="_1"><i class="fa fa-files-o"></i></label><input id="_1" type="checkbox"> to show the papers I studied for this project.
<div style="width:100%">
<iframe class="scribd_iframe_embed" src="https://www.scribd.com/embeds/267406568/content?start_page=1&view_mode=scroll&show_recommendations=true" data-auto-height="false" data-aspect-ratio="undefined" scrolling="no" class="scribds" frameborder="0"></iframe>
<iframe class="scribd_iframe_embed" src="https://www.scribd.com/embeds/267406640/content?start_page=1&view_mode=scroll&show_recommendations=true" data-auto-height="false" data-aspect-ratio="undefined" scrolling="no" class="scribds" frameborder="0"></iframe>
</div>
</div>

---

To sum up those documents, the involute curve can be made by the unwrapping of an cord which has been wrapped around a circle. The arc created by the end of our cord as it travels farther back around the circle creates the profile of the tooth. The width of the tooth is primarily a function of the diameter of the gear without teeth (the cirrcle) and the number of teeth. This shape is used ubiquitously as it performs better than any other shape on all measures - power, efficiency, reliability, and repeatability.

### Assembly

My team of four was assigned different parts of the assembly. My portion was the pinned connection which would allow the Sun gear to be stil while the Planet and Ring gears rotated around it. Here is a gif of that in action:

![assembly gif 1]({{ site.images }}{{ page.dir }}sun-still.gif)

And a video of the gif itself:

![assembly gif 1]({{ site.images }}{{ page.dir }}assembly.gif)

### Planet
The model:
<script src="https://embed.github.com/view/3d/daveas/3D-Products/master/Gear-System/Involute-Gear-Planet.stl"></script>
Animation with the Planet still (not rotating).
![planet still]({{ site.images }}{{ page.dir }}still-planet.gif)

### Sun
The model:
<script src="https://embed.github.com/view/3d/daveas/3D-Products/master/Gear-System/Involute-Gear-Sun.stl"></script>
Animation with the Sun still (not rotating).
![sun still]({{ site.images }}{{ page.dir }}still-sun.gif)

### Ring
The Model:
<script src="https://embed.github.com/view/3d/daveas/3D-Products/master/Gear-System/Involute-Gear-Ring.stl"></script>
Animation with the Ring still (not rotating).
![still ring]({{ site.images }}{{ page.dir }}still-ring.gif)
