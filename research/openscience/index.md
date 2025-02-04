---
title: Open Science
---
# Open Science Resources

## Semantic Segmentation

Here we share models developed for automated semantic segmentation applied to HR-pQCT, clinical CT, MRI and more...

#### {% include icon.html icon="fa-solid fa-circle-arrow-right" %}HR-pQCT Knee Segmentation

{% capture col1 %}
{% include figure.html image="images/projects/RadTib.png" width="100%" %}
{% endcapture %}

{% capture col2 %}
This model will automatically segment the distal radius and distal tibia scans measured by HR-pQCT and provide masks for the cortical and trabecular compartments.

{%
  include tags.html
  tags="Published Manuscript"
  link="https://www.nature.com/articles/s41598-022-27350-0"
%}

{%
  include tags.html
  tags="GitHub Repository"
  link="https://github.com/Bonelab/HR-pQCT-Segmentation"
%}

{%
  include tags.html
  tags="Zenodo Model"
  link="https://zenodo.org/records/14755838"
%}

{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

{% include section.html %}

#### {% include icon.html icon="fa-solid fa-circle-arrow-right" %}HR-pQCT Knee Segmentation

{% capture col1 %}
{% include figure.html image="images/projects/Knee_2d.png" width="100%" %}
{% endcapture %}

{% capture col2 %}
This model will automatically segment the proximal tibia and distal femur of the knee measured by HR-pQCT and provide ROIs for subsequent analysis.

{%
  include tags.html
  tags="Published Manuscript"
  link="https://www.medrxiv.org/content/10.1101/2024.05.20.24307643v1"
%}

{%
  include tags.html
  tags="GitHub Repository"
  link="https://github.com/Bonelab/hrpqct-knee-segmentation"
%}

{%
  include tags.html
  tags="Zenodo Model"
  link="https://zenodo.org/records/11244681"
%}

{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

{% include section.html %}

#### {% include icon.html icon="fa-solid fa-circle-arrow-right" %}MRI BML Segmentation

{% capture col1 %}
{% include figure.html image="images/projects/bml.png" width="100%" %}
{% endcapture %}

{% capture col2 %}
This model extracts bone marrow lesions (BMLs) from knee MRI scans.

{%
  include tags.html
  tags="Published Manuscript"
  link="https://www-sciencedirect-com.ezproxy.lib.ucalgary.ca/science/article/pii/S001048252400876X?via%3Dihub"
%}

{%
  include tags.html
  tags="GitHub Repository"
  link="https://github.com/Bonelab/BML-MRI-segmentation"
%}

{%
  include tags.html
  tags="Zenodo Model"
  link="https://zenodo.org/records/14805833"
%}

{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

{% include section.html %}
