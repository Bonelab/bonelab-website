---
title: Research
nav:
  order: 2
  tooltip: Learn what research we do
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

<div align="center">
	<video controls="controls" width="300" height="300" autoplay="autoplay" loop="loop" name="Skeleton">
	  <source src="/video/skeleton.mov">
	</video>
</div>

{:.center}
See below for a taste of the types of studies we do, analysis methods we develop, and the lab and equipment in it. 
Take a spin through and see if you find something you like...

## Studies
{% include list.html component="card" data="projects" filters="group: studies" style="small" %}

{% include section.html %}

## Software
{% include list.html component="card" data="projects" filters="group: software" style="small" %}

{% include section.html %}

## Infrastructure
{% capture content %}

{% include figure.html image="images/equipment/QCT.png" caption="GE Revolution HD GSI" %}

{% include figure.html image="images/equipment/pQCT.png" caption="XCT 3000 pQCT" %}

{% include figure.html image="images/equipment/DXA.png" caption="GE iDXA" %}

{% include figure.html image="images/equipment/XT2.png" caption="XtremeCT II" %}

{% include figure.html image="images/equipment/XT2B.png" caption="XtremeCT IIb" %}

{% include figure.html image="images/equipment/LAB5.png" caption="Lab" %}

{% include figure.html image="images/equipment/LAB6.png" caption="Lab" %}

{% include figure.html image="images/equipment/LAB4.png" caption="Lab meeting room" %}

{% include figure.html image="images/equipment/LAB7.png" caption="Lab fun" %}

{% endcapture %}

{%
  include grid.html 
  content=content
  style="100%"
%}

{% include section.html %}
