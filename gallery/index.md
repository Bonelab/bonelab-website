---
title: Gallery
nav:
  order: 5
  tooltip: Photographs of lab activities
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}Gallery

{% include section.html %}

## Photographs

Lab hikes, events, activities and more...

{% capture content %}

{% include figure.html image="images/gallery/2001_Calgary.jpg" %}

{% include figure.html image="images/gallery/2001_McCaig_Tower.jpg" %}

{% include figure.html image="images/gallery/2006_haling.jpg" %}

{% include figure.html image="images/gallery/2007_hockey.jpg" %}

{% include figure.html image="images/gallery/2008_prairieview.jpg" %}

{% include figure.html image="images/gallery/2008_t4k.jpg" %}

{% include figure.html image="images/gallery/2009_lake_louise_skiing.jpg" %}

{% include figure.html image="images/gallery/2009_t4k.jpg" %}

{% include figure.html image="images/gallery/2012_Nola.jpg" %}

{% include figure.html image="images/gallery/2012_Tour_for_kids_team.jpg" %}

{% include figure.html image="images/gallery/2015_Postdocs.jpg" %}

{% include figure.html image="images/gallery/2015_bonelab_members.jpg" %}

{% include figure.html image="images/gallery/2015_Bonelab_gang.jpg" %}

{% include figure.html image="images/gallery/2015_Holiday_Dinner.jpg" %}

{% include figure.html image="images/gallery/2016_McCaig_Foundation.jpg" %}

{% include figure.html image="images/gallery/2016_xt_install.jpg" %}

{% include figure.html image="images/gallery/2016_Bodyworlds.jpg" %}

{% include figure.html image="images/gallery/2016_Christmas_Party.jpg" %}

{% include figure.html image="images/gallery/2017_skating.jpg" %}

{% include figure.html image="images/gallery/2017_vitd_done.jpg" %}

{% include figure.html image="images/gallery/2017_BME_Remembrance_Day.jpg" %}

{% include figure.html image="images/gallery/2018_holiday.jpg" %}

{% include figure.html image="images/gallery/2018_TBone_Table.png" %}

{% include figure.html image="images/gallery/2018_lab_hike.jpg" %}

{% include figure.html image="images/gallery/2018_mccaig_anniversary.jpg" %}

{% include figure.html image="images/gallery/2019_Michalski_QCT.jpg" %}

{% include figure.html image="images/gallery/2019_TeamVitaminD.jpg" %}

{% include figure.html image="images/gallery/2019_QMSKI_organizers.jpg" %}

{% include figure.html image="images/gallery/2022_Bonelab.jpg" %}

{% include figure.html image="images/gallery/2022_summer_students.png" %}

{% include figure.html image="images/gallery/2022_bme_conference.jpg" %}

{% include figure.html image="images/gallery/2022_bme_outside.jpg" %}

{% include figure.html image="images/gallery/2022_Adventure_hike.jpg" %}

{% include figure.html image="images/gallery/2022_BME_Conference.png" %}

{% include figure.html image="images/gallery/2022_Lab_in_HRIC.jpg" %}

{% include figure.html image="images/gallery/2023_HaLing.jpg" %}

{% include figure.html image="images/gallery/2023_halloween.jpg" %}

{% include figure.html image="images/gallery/2023_lab_photo1.jpg" %}

{% include figure.html image="images/gallery/2023_lab_photo2.jpg" %}

{% include figure.html image="images/gallery/2023_lab_ski_day.jpg" %}

{% include figure.html image="images/gallery/2023_mccaig_party.jpg" %}

{% include figure.html image="images/gallery/2023_Hike_Ha_Ling.jpg" %}

{% include figure.html image="images/gallery/2023_Hike_Ha_Ling_saddle.jpg" %}

{% include figure.html image="images/gallery/2023_Wood_Forum.jpg" %}

{% endcapture %}

{%
  include grid.html 
  content=content
  style="100%"
%}

{% include section.html %}

## Animations

### {% include icon.html icon="fa-solid fa-circle-arrow-right" %}Extracting the skeleton from CT images using machine learning

{% capture col1 %}
<video controls="controls" autoplay="autoplay" loop="loop" width="400" name="KUB">
  <source src="/video/kub.mov">
  Your browser does not support this video format.
</video>
{% endcapture %}

{% capture col2 %}
Using machine learning, we can extract the skeleton from CT scans. In this animation
each frame represents a different person. There were 1000 people automatically segmented
included in this animation.
{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

### {% include icon.html icon="fa-solid fa-circle-arrow-right" %}Simulating X-rays from CT images

{% capture col1 %}
<video controls="controls" autoplay="autoplay" loop="loop" width="400" name="KUB">
  <source src="/video/skeleton.mov">
</video>
{% endcapture %}

{% capture col2 %}
Starting with a CT scan, we can create projections that look like an X-ray. If we rotate the projections and 
stitch them together we can an animation as you see here. It is based on 360 views.
{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

### {% include icon.html icon="fa-solid fa-circle-arrow-right" %}Automated definition of regions of interest from knee images

{% capture col1 %}
<video controls="controls" autoplay="autoplay" loop="loop" width="400" name="KUB">
  <source src="/video/knee_compartments.mov">
</video>

<video controls="controls" autoplay="autoplay" loop="loop" width="400" name="KUB">
  <source src="/video/knee_rois.mov">
</video>
{% endcapture %}

{% capture col2 %}
We are working on a project to extract the cortical and trabecular bone in the knee (tibia shown)
using machine learning on data collected using high-resolution peripheral quantitative computed tomography (top).
Once defined, an atlas-based registration is used to define the three regions of interests in each compartment (bottom).
{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

{% include section.html %}

{% include figure.html image="images/general/Mount_Jimmy_Simpson.jpg" caption="Just going for a walk in our back yard" width="100%"%}
