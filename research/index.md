---
title: Research
nav:
  order: 2
  tooltip: Learn what research we do
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

<div align="center">
	<video width="300" height="300" autoplay="autoplay" loop="loop" name="Skeleton">
	  <source src="/video/skeleton.mov">
	</video>
</div>

{:.center}
See below for a taste of the types of studies we do, analysis methods we develop, and the lab and equipment in it.

{% 
  include button.html 
  type="link"
  text="Open Science"
  icon="fa-solid fa-arrow-right fa-beat"
  link="research/openscience"
  tooltip="We strive to make our research available to others"
  style="button" 
%}

## Research themes

### Bone fragility and skeletal ageing

We use high-resolution imaging to study how bone microarchitecture and estimated strength change with age. Our work develops and evaluates microarchitecture-based fracture-risk tools, bone phenotypes and skeletal-age measures to make these changes easier to interpret.

### Quantitative imaging from clinical CT

We develop calibration and automated analysis methods to extract bone density and model-based strength estimates from CT scans acquired for other clinical reasons. We test how acquisition protocols, contrast enhancement and modelling choices affect the measurements, and apply these methods in clinical research.

### Bone and joint changes after knee injury

We combine HR-pQCT, MRI and automated image analysis to measure bone microarchitecture and bone marrow lesions after ACL injury. By following these changes over time, we study how joint injury relates to symptoms and the processes implicated in post-traumatic osteoarthritis.

### Bone adaptation to loading and unloading

Our astronaut research tracks how bone is lost during spaceflight and how it reforms after return to Earth, helping us understand the response of bone to unloading and recovery.

### Reproducible imaging and computational biomechanics

Across these themes, we develop and share image-analysis workflows, trained models and benchmark resources, and contribute to community guidance for open and reproducible musculoskeletal imaging research.

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

## {% include icon.html icon="fa-solid fa-lightbulb" %}New Ideas

Here is a place we collect ideas for future projects. Some of them are small and some are big!

{% include list.html data="posts" component="post-excerpt" %}

{% include section.html %}
