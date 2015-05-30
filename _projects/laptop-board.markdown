---
layout: project
title: Laptop Board
date: 2012-01-20
category: work
tags:
- CAD
- Mechanical
- Engineering
excerpt: I always wanted a laptop board but I was not happy with what was available. They were all ugly and innefective or loud (if they had fans). So I decided to make one out of wood and metal that would be more attractive and passively effective."
published: true
dir: laptop-board/
---


### Materials:

I knew I wanted to use a hardwood for the body and a metal as the heat conductive surface. I chose a red oak board from Lowe's for maximum stiffness & hardness and started looking at how to find my metal. To get started I knew that I needed to select the metal with the highest possible thermal conductivity, "k", to increase the amount of heat transfer "q", as they are directly proportional: \\[q = kA\frac{dT}{s} \\]

I knew I was going to order the metal form a website called [Online Metals](http://www.onlinemetals.com) which mainly offers aluminum, steel, cooper, brass, nickel, and titanium.

I know copper would be highest and aluminum second, but I decided to record the values just in case. Here are some sample values of q:

Material | q (W/m<sup>2</sup>K)
:--- | :---:
Copper | 386
Aluminum | 202
Brass | 99
Nickel | 62
Titanium | 19
Stainless Steel | 16

Of the aluminum selection at Online Metals, the best choice was aircraft grade 6061-T6 at 167 W/m<sup>2</sup>K.

Aluminum | q (W/m<sup>2</sup>K)
:--- | :---:
2024-T3 | 121
5052-H32 | 138
5086-H32 | 125
**6061-T6** | **167**
7075-T6 | 130

### Construction:

I went to a friend's house who has an immaculate wood shop. We checked out everything he had before deciding on how we would reduce the wood to create a reasonable amount of airflow. I had invisioned a series of holes at the bottom through to the conductive surface and slots on the sides to allow heat to escape as it rose without marring the appearance of the top surface.

We planed the work piece and then secured it to fillet the sides with a router:
![2]({{ site.images }}{{page.dir}}1.jpg)
Finished edges after staining:
![2]({{ site.images }}{{page.dir}}2.jpg)

We then mounted the router in the router table and raised it above the height of the table equal to the thickness of the metal sheet, and built a rectangular jig around it within which moving the work piece would move the piece over the router to create the bore equal to the size of the cut metal surface. Next we drilled a matrix of through holes for ventilation, and lastly we bore three logitudinal slots on the sides of the work piece with the router.
![3]({{ site.images }}{{page.dir}}3.jpg)

And the finished product:
![4]({{ site.images }}{{page.dir}}4.jpg)

It works great!
