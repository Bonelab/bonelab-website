---
title: Open Science
nav:
  order: 10
  tooltip: Open Science
---
# Open Science

A collection of medical imaging data, machine learning model weights, links to source code, and other contributions toward an open science goal.

## Machine Learning Models

{:.left}

### Automatic segmentation of radius and tibia HR-pQCT images

| Modality      | HR-pQCT                                               |
| :------------ | :---------------------------------------------------- |
| Github        | [https://github.com/Bonelab/HR-pQCT-Segmentation](https://github.com/Bonelab/HR-pQCT-Segmentation) |
| Model weights | (researchFS BOYD drive) /Volumes/BOYD/03 - Projects/Current Projects/HR-pQCT Segmentation/trained_models |
| Publication   | https://doi.org/10.1038/s41598-022-27350-0 |

{% include section.html %}

{:.left}

### Automatic generation of periarticular ROIs for knee HR-pQCT images

| Modality      | HR-pQCT                                               |
| :------------ | :---------------------------------------------------- |
| Github        | [https://github.com/Bonelab/HRpQCT-Knee-Seg](https://github.com/Bonelab/HRpQCT-Knee-Seg) |
| Model weights | (zenodo) https://doi.org/10.5281/zenodo.11244681 |
| Publication   | (pre-print) https://doi.org/10.1101/2024.05.20.24307643 |

{% include section.html %}

{:.left}

### Automatic BML Segmentation

| Modality      | MRI                                                   |
| :------------ | :---------------------------------------------------- |
| Github        | [https://github.com/Bonelab/BML-MRI-segmentation](https://github.com/Bonelab/BML-MRI-segmentation) |
| Model weights | /Volumes/BOYD/03\ -\ Projects/Current\ Projects/BML-MRI-segmentation/unet |
| Publication   | https://doi.org/10.1016/j.compbiomed.2024.108791 |

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