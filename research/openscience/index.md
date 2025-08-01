---
title: Open Science
---
# Open Science

{% include figure.html image="images/projects/OpenScience.png" height="200px" link="https://science.gc.ca/site/science/sites/default/files/attachments/2022/Roadmap-for-Open-Science.pdf"%} 

We are actively building this page and plan to include additional resources in the future.

## Semantic Segmentation

Here we share models developed for automated semantic segmentation applied to HR-pQCT, clinical CT, MRI and more...

#### {% include icon.html icon="fa-solid fa-circle-arrow-right" %}HR-pQCT Radius/Tibia Segmentation

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

#### {% include icon.html icon="fa-solid fa-circle-arrow-right" %}Opportunistic CT to FEA for Standardization

{% capture col1 %}
{% include figure.html image="images/projects/oct_to_fea.png" width="100%" %}
{% endcapture %}

{% capture col2 %}
A pipeline that extracts vertebra, calibrates the CT for performing linear and non-linear FEA.

{%
  include tags.html
  tags="Published Manuscript"
  link="http://gigadb.org/dataset/102733"
%}

{%
  include tags.html
  tags="SpineFE GitHub Repository"
  link="https://github.com/Bonelab/spineFE-benchmark"
%}

{%
  include tags.html
  tags="Zenodo Vertebrae Data"
  link="https://doi.org/10.5281/zenodo.15313258"
%}
{%
  include tags.html
  tags="Zenodo Segmentation Vert Model"
  link="https://doi.org/10.5281/zenodo.15238175"
%}
{%
  include tags.html
  tags="Zenodo Segmentation Reference Tissue Model"
  link="https://doi.org/10.5281/zenodo.15238422"
%}
{%
  include tags.html
  tags="Original VerSe 2019"
  link="http://dx.doi.org/10.17605/OSF.IO/NQJYW"
%}

{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

{% include section.html %}
