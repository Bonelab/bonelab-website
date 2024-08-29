---
title: Open Science
nav:
  order: 10
  tooltip: Open Science
---
# Open Science

A collection of medical imaging data, machine learning model weights, links to source code, and other contributions toward an open science goal.

{% include section.html %}
## Automated HR-pQCT Knee Segmentation
Atlases and segmentation models for automated quantitative analysis of peri-articular bone microarchitecture in HR-pQCT knee images. Training and testing source code is here: https://github.com/Bonelab/hrpqct-knee-segmentation

Atlas and model weights are [here](https://zenodo.org/records/11244681).

## FAIM finite element software
A free software for image-based large-scale finite element analysis. A manual and instructions for download and installation are available.

Faim download is [here](https://bonelab.github.io/n88/).

{% capture content %}
  {%
    include figure.html
    image="images/general/QCT_Right.jpg"
    width="100%"
  %}
{% endcapture %}

{%
  include float.html
  content=content
  flip=true
%}

{% include section.html %}