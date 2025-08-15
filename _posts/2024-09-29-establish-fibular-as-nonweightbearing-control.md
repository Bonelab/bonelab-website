---
image: images/projects/TBONE.png
title: Establishing the fibula as a non-weight bearing control
author: Steven Boyd, with Matthias Walle
tags:
  - hr-pqct
  - image processing
datasources: 
  - "TBONE"
resources: 
  - "IPL scipts"
scope: 
  - "PhD/MSc side project"
  - "Summer student"
---

Establishing whether the fibula can be a non-weight bearing control instead of distal radius...

We know that typically the two main HR-pQCT scanning sites, the radius and tibia, often are 
surrogates for non-weight bearing and weight-bearing mechanical loading, respectively. However,
a complicating factor of the radius is that it is also a site that is prone to motion artifact
during HR-pQCT acquisition. There is research showing that the fibula is not carrying very much
weight relative to the tibia, and since it is scanned in the same FOV as the tibia, it is
subject to exactly the same motion artifacts. Therefore, to determine whether a mechanical 
stimulus, such as microgravity induced bone loss in space flight, it would be possible to 
confirm this difference more clearly because it removes the confounding effect of the motion 
differences between tibia and radius. 

It would require going back to the original ISQ files from the TBONE study and extracting the 
fibula from each scan. This would involve a simple modification to the IPL script that gets the
"largest bone" to getting the "second largest bone". Subsequently, a full morphological analysis
and voxel-based assessment could be performed on the fibula data for direct comparison to the 
tibia.

