---
image: images/projects/Treece.png
title: Extraction of an image mask from polygon data
author: Steven Boyd
tags:
  - software
  - image processing
datasources: 
  - "ARTININ"
  - "CaBHS"
resources: 
  - "Treece surface model in Bonelab github"
scope: 
  - "PhD/MSc side project"
  - "Summer student"
---

Cortical bone mapping with global optimization produces incredible results for all types
of CT data, including clinical CT and HR-pQCT. The result of the algorithm is a polygon
dataset of the periosteal surface of the bone and scalars representing the local thickness
(i.e., periosteal to endosteal) calculated by the algorithm. The calculation of cortical
thickness can be summarized from the individual data points (i.e., means, standard deviations,
localized measurements, etc). 

https://github.com/Bonelab/Bonelab/blob/master/bonelab/cli/treece_thickness.py

However, the algorithm cannot produce an image mask. So the aim of this project is to develop 
additional functionality that outputs a binarized image with voxels labelled as cortical bone (127), 
trabecular bone (100), and background (0). The image will be the identical size to the input
that is input. Likely it would be based on VTK stencil objects (similar to blRapidPrototype):

https://github.com/Bonelab/Bonelab/blob/master/bonelab/cli/RapidPrototype.py

When completed it will be validated on HR-pQCT of radius, tibia and knee, as well as QCT of 
abdomen and knee.
