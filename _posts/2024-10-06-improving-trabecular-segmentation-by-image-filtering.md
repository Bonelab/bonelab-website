---
image: images/projects/kneeinprofile.png
title: Improved image segmentation of bone by image filtering
author: Steven Boyd, with Nathan Neeteson
tags:
  - hr-pqct
  - image processing
datasources: 
  - "TRIKNEE"
resources: 
  - "IPL scipts"
  - "Python scipts"
scope: 
  - "PhD/MSc side project"
  - "Summer student"
---

Can we do a better job of segmenting the trabecular structure in knee scans by HR-pQCT...

The use of HR-pQCT of the knee is relatively new, and although we are able to collect images
as part of our normal protocol now, the size of the knee seems to lead to some beam hardening 
issues at the centre. This is manifested as a slight darking of the trabecular structure. There
is work by the UCSF group (Kazakia, Burghardt) that has shown the so-called Laplace-Hamming
filter provided by Scanco Medical IPL seems to perform better than the standard Gaussian filtering.
Other methods such as Otsu's method, adaptive filtering, etc, are also options.

The goal of this project is to compare filtering methods on the ability to extract bone 
microarchitecture. We would want to determine how these affect measures such as TbTh and TbSp, 
and possibly finite element outcomes. This could be explored using the TRIKNEE study where we
have three repeat measures on the same individual for a small cohort. The ground-truth would be
taken as the Gauss segmentation, since we don't have a true gold standard for these in vivo scans.

We have implemented a L-H filter here: https://github.com/Bonelab/Bonelab/blob/master/bonelab%2Fcli%2Ffft_laplace_hamming.py