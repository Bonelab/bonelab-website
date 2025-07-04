---
title: Links
nav:
  order: 7
  tooltip: Relevant links and videos
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}Links

Please find some useful links related to the Bone Imaging Laboratory and our YouTube videos.

## Helpful Links

{% capture col1 %}
##### Academic
- [McCaig Institute for Bone and Joint Health](https://mccaig.ucalgary.ca/)
- [Department of Radiology](https://www.ucalgary.ca/radiology/)
- [Division of Image Science](https://www.ucalgary.ca/image-science/)
- [Cumming School of Medicine](https://cumming.ucalgary.ca/)
- [Schulich School of Engineering](https://schulich.ucalgary.ca/)
- [Faculty of Kinesiology](https://kinesiology.ucalgary.ca/)
- [BME Graduate Program](https://www.ucalgary.ca/bme/graduate)

##### GitHub Sites of Interest
- [Bonelab](https://github.com/Bonelab)
- [Numerics88](https://github.com/Numerics88)
- [ManskeLab](https://github.com/ManskeLab)
- [ORMIR-MIDS](https://github.com/ormir-mids)
- [uniGradICON](https://github.com/uncbiag/uniGradICON)

##### Public Datasets
- [Kaggle](https://www.kaggle.com/datasets)
- [Grand Challenge](https://grand-challenge.org)
- [Google Dataset](https://datasetsearch.research.google.com)

##### Python Programming
- [Classic Harvard Intro](https://cs50.harvard.edu/python/2022/)
- [U of Helsinki](https://programming-23.mooc.fi/)
- [Textbook for IDE & Python](https://thepythoncodingbook.com/book-outline/)
- [Navigate the Terminal](https://futurecoder.io/)

{% endcapture %}

{% capture col2 %}
##### Funding
- [Natural Sciences and Engineering Research Council](https://www.nserc-crsng.gc.ca/index_eng.asp)
- [Canadian Institutes for Health Research](https://cihr-irsc.gc.ca/e/193.html)
- [Alberta Innovates](https://albertainnovates.ca/)
- [Graduate Student Salary Calculator](https://bonelab.github.io/salarycalc/index.html)

##### Travel & Safety
- [Register to travel for work](https://www.ucalgary.ca/risk/risk-management-insurance/travel/register-travel)
- [Radiation safety](https://www.radiologyinfo.org/en/info.cfm?pg=safety-xray)

##### Visitor Information
- [City of Calgary](https://www.calgary.ca/)
- [Rocky Mountains](http://www.canadianrockies.net/)
- [Government of Canada](https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada.html)

##### University of Calgary
- [Parking](https://www.ucalgary.ca/ancillary/parking/parking-permits/find-parking)
- [Maps](https://www.ucalgary.ca/about/our-campuses/campus-maps-and-room-finder)
- [Transit](https://www.ucalgary.ca/sites/default/files/teams/157/Main-Campus-Transit_20230831.pdf)
- [Library APC Coverage](https://search.scifree.se/ucalgary)

##### BME Companies
- [Start Alberta](https://startalberta.ca) (Click Explore Dealflow, select Companies, Filter by location)
- [Medtech Canada](https://medtechcanada.org/membership/directory/full-members.html) (Canadian companies)

{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

{% 
  include button.html 
  type="link"
  text="Join us? Learn more here"
  icon="fa-solid fa-arrow-right fa-beat"
  link="about#joinus"
  tooltip="Information about the application process"
  style="button" 
%}

{% include section.html %}

## {% include icon.html icon="fa-brands fa-youtube" %} YouTube
We have created a number of videos for learning how to use our software and learning about the reserach we do.

## Bonelab Git Repository
Learn how to download, install and contribute to our [BoneLab](https://github.com/Bonelab/Bonelab) Git repository through a series of YouTube videos prepared by [Dr. Bryce Besler](_members/bryce-besler.md). This repository includes tools for visualization, image processing, and example scripts in Python and R. 

{% capture bryce %}
{% include figure.html width="100%" caption="Part 1: Welcome" image="https://www.youtube.com/embed/4HBwhlR5p-0" %}
{% include figure.html width="100%" caption="Part 2: Overview" image="https://www.youtube.com/embed/-HPJHFbDQBk" %}
{% include figure.html width="100%" caption="Part 3: Structure" image="https://www.youtube.com/embed/uTTqe2_OnsY" %}
{% include figure.html width="100%" caption="Part 4: Tools" image="https://www.youtube.com/embed/skQNISaDtNc" %}
{% include figure.html width="100%" caption="Part 5: Versioning & contributing" image="https://www.youtube.com/embed/7BID__k96Ho" %}
{% include figure.html width="100%" caption="Part 6: Relation to Numerics88" image="https://www.youtube.com/embed/IOccBoZdkOQ" %}
{% include figure.html width="100%" caption="Part 7: Dependencies" image="https://www.youtube.com/embed/iWNMNneGxyA" %}
{% include figure.html width="100%" caption="Part 8: zsh fix" image="https://www.youtube.com/embed/S0Jt4KE0OL0" %}
{% include figure.html width="100%" caption="Part 9: Clone & Install" image="https://www.youtube.com/embed/s7Us47c-BW4" %}
{% include figure.html width="100%" caption="Part 10: Example Data" image="https://www.youtube.com/embed/Z2TTk4LjXAA" %}
{% include figure.html width="100%" caption="Part 1: Closing" image="https://www.youtube.com/embed/okf6bCD6KpA" %}
{% endcapture %}

{%
  include grid.html
  content=bryce
  style="square"
%}

{% include section.html %}

## Technical Webinars
Presentations on how to perform some of our key activities in the lab are collected here.

{% capture webinar %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/jxQ4l1pGkjM" caption="Registration webinar" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/Ks3KlHUhGKQ" caption="Normative webinar" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/lx2UAp2ouQ0" caption="blQtViewer" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/LSrIwvBGs1w" caption="Statistical Data Exploration &amp; Implementation using R" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/nG7KF0_PhDU" caption="EOS Lower Limb Tutorial" %}
{% include figure.html width="100%" image="https://youtu.be/Nyf9oWGrenk" caption="Normative 2.0 Tutorial" %}
{% endcapture %}

{%
  include grid.html
  content=webinar
  style="square"
%}

{% include section.html %}

## Research Presentations
A collection of presentations that members of the lab have produced so that we can share our science.

{% capture research %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/PDOaHLt9xgI" caption="Kurt Hildebrand: Assessing Skeletal Muscle at the Proximal Tibia using Second Generation HR-pQCT" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/qdvBBvcj7ms" caption="ML in Bones: What are Functions?" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/JB-2oKn8qHQ" caption="Tannis Kemp: Estimation of Model Parameters for Subject-Specific Prediction of Bone Adaptation" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/J5wmhoY59j8" caption="Pre-Flight Biomarkers of Bone Remodelling Predict Bone Loss on Long-Duration Spaceflight" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/cRFk0wbsb2k" caption="Bone Imaging Laboratory: Overview" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/ikvWMi3W8Dc" caption="High-dose Vitamin D Supplementation Affects Bone Density Differently in Females than Males" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/tT3dz4VrwfE" caption="MicroCT Image Tours" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/_s-WcBOJWMw" caption="Postdoc Research Slam - Leigh Gabel" %}
{% include figure.html width="100%" image="https://www.youtube.com/embed/CY0ymsnkcp8" caption="An investigation into predictive fracture modelling using machine.  PhD Candidate Danielle Whittier" %}
{% endcapture %}

{%
  include grid.html
  content=research
  style="square"
%}

## Podcasts and Radio
Sometimes we get publicity through podcasts or radio interviews.

{% capture podcast %}
{% include figure.html width="100%" image="https://soundcloud.com/bmjpodcasts/what-can-sem-learn-from-the-international-space-station-w-leigh-gabel-and-kathryn-ackerman-ep-476" caption="TBONE Podcast" %}
{% include figure.html width="100%" image="images/general/deutschlandfunk.png" link="https://www.deutschlandfunk.de/knochenjob-weltall-und-himmliche-highlights-dlf-15e99cad-100.html" caption="TBONE on Deutschlandradio" %}
{% include figure.html width="100%" image="images/general/ndr_logo.png" link="https://www.ndr.de/nachrichten/info/Was-Weltraumaufenthalte-ueber-Knochenabbau-lehren,audio1797820.html" caption="TBONE on Norddeutscher Rundfunk" %}
{% endcapture %}

{%
  include grid.html
  content=podcast
%}
