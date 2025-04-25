---
image: images/projects/asynchronous.png
title: A comparison of asynchronous to synchronous calibration
author: Steven Boyd
tags:
  - clinical ct
  - image processing
datasources: 
  - "ARTININ"
resources: 
  - "Python scripts"
  - "Ogo GitHub repository"
scope: 
  - "MSc project"
  - "Summer student"
---

Does synchronous calibration work as well as we think?

Typically CT scans are not acquired with a calibration phantom in the scan (i.e., synchronous calibration) and so we have to either perform internal calibration or use synchronous calibration (i.e., scan the phantom in the same scanner as the patient, but not at the same time). The reason a phantom is not used clinically is because most CT imaging is not quantitative, but rather used for diagnostic purposes. We assume that the best way to have quantitative data is to include a calibration phantom, but is it? Does the inclusion of the dense phantom rods actually lead to beam hardening that alters the resulting BMD? This is hard to know because it'd require scanning a person twice: once with the phantom and once without the phantom (and them scan the phantom separately).

This project would propose to test whether an in-scan phantom results in the most accurate quantitative CT outcome. We would work with the gross anatomy lab to scan a fresh cadaver with and without the calibration phantom in place. We would do this for a KUB scan as well as a chest scan. Although BMD is our ultimate outcome of interest, our comparison would be based on the HU from each scan. Using ML we'd segment the L1-L4 and left/right femurs and calculate the mean HU in each bone. 

Additional measures we might consider are adjusting table height as well as employing internal calibration. Since it is a lot of work to have a cadaver in the scanner we might consider other scanning protocols as well (i.e., knees, head).

Image shown is from Mateo Ruedes.
