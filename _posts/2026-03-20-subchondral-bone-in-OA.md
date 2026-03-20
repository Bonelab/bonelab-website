---
image: images/projects/subchondral_bone_thickness.png
title: What are the longitudinal changes in subchondral bone thickness after ACL injury?
author: Steven Boyd
tags:
  - clinical ct
  - hr-pqct
  - image processing
datasources: 
  - "SALTACII"
resources: 
  - "Python scripts"
  - "Bonelab GitHub repository"
  - "Ogo GitHub repository"
scope: 
  - "MSc project"
  - "Summer student"
---

What are the longitudinal changes in subchondral bone thickness after ACL injury?

In our SALTACII study we have been following a cohort of young adults who sustained an acute 
knee injury involving a tear to their anterior cruciate ligament. We are now approaching the 
6-year time point of the study and have an assortment of image (and other) data that has been 
tracking their knee health. 

We know that in post-traumatic injury of the knee often leads to knee osteoarthritis development, 
even if reconstruction surgery is performed. The etiology seems to eventually lead to a thickening 
of the subchondral bone plate, but this is typically shown in animal models, not humans.

The goal of this project would be to use the HR-pQCT and/or the DECT images of the knees of this cohort
from annual visits since their original injury to measure the local subchondral bone thickness:

https://github.com/Bonelab/Bonelab/blob/master/bonelab/cli/treece_thickness.py

We have imaging for the injured knee as well as the contralateral knee, which can serve as a control. Given
the long follow-up of this cohort there is a good chance we will begin to see early changes to the subchondral
bone thickness.

