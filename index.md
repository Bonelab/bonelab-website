---
---
# Welcome!

{% capture content %}
  {%
    include figure.html
    image="images/general/BIL_CT_Room.jpg"
    width="100%"
  %}
{% endcapture %}

{%
  include float.html
  content=content
  flip=true
%}

At the University of Calgary, the Bone Imaging Laboratory studies how bone structure and strength change with ageing, injury and altered loading. We combine high-resolution medical imaging, computational biomechanics and machine learning to measure skeletal change and develop tools for fracture-risk assessment.

Our research spans microarchitecture-based fracture prediction, quantitative analysis of clinical CT, and bone and joint changes after knee injury. We also share analysis methods and benchmark resources so that others can test and build on our work.

Our long-term goal is to improve the assessment of bone and joint health and inform strategies that preserve mobility.

{% 
  include button.html 
  type="link"
  text="Participate in research"
  icon="fa-solid fa-arrow-right fa-beat"
  link="research/mobility_for_life"
  tooltip="Information about the application process"
  style="button" 
%}

{% include section.html %}

## Highlights

{% capture text %}

From bone microarchitecture to estimated strength and fracture risk, we develop and evaluate imaging-based measures of skeletal health. Our studies follow bone change in populations and after knee injury, while our computational work makes these measurements more quantitative and reproducible.

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/general/Skeleton.png"
  link="publications"
  title="Our Research"
  text=text
%}

{% capture text %}

Explore microarchitecture-based fracture-risk assessment, opportunistic CT, knee-injury imaging, and bone adaptation during spaceflight—alongside the methods and shared resources that support these studies.

{%
  include button.html
  link="research"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects/VITD.png"
  link="research"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our team includes undergraduate summer students, graduate students doing their MSc or PhD, post-doctoral fellows, medical imaging
and computational specialists, staff, and faculty. We collaborate with people in Calgary and around the world.


{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/general/BIL_Stairs.jpg"
  link="team"
  title="Our Team"
  text=text
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

## Funding
{% capture col1 %}
<a href="https://cihr-irsc.gc.ca/e/193.html" target="_blank"><img src="images/logos/Funder_CIHR.png"></a> <!-- width="50%" link="https://cihr-irsc.gc.ca/e/193.html" %}-->
{% endcapture %}

{% capture col2 %}
<a href="https://www.nserc-crsng.gc.ca/index_eng.asp" target="_blank"><img src="images/logos/Funder_NSERC.png"></a> <!-- width="50%" link="https://www.nserc-crsng.gc.ca/index_eng.asp" %}-->
{% endcapture %}

{% capture col3 %}
<a href="https://albertainnovates.ca/about/who-we-are/teams/health-innovations-team/" target="_blank"><img src="images/logos/Funder_AI.png"></a> <!-- width="50%" link="https://albertainnovates.ca/about/who-we-are/teams/health-innovations-team/" %}-->
{% endcapture %}

{% capture col4 %}
<a href="https://www.innovation.ca" target="_blank"><img src="images/logos/Funder_CFI.png"></a> <!-- width="50%" link="https://www.innovation.ca" %}-->
{% endcapture %}

{% capture col5 %}
<a href="https://www.asc-csa.gc.ca/eng/" target="_blank"><img src="images/logos/Funder_CSA.png"></a> <!-- width="50%" link="https://www.asc-csa.gc.ca/eng/" %}-->
{% endcapture %}

{% capture col6 %}
<a href="https://arthritis.ca" target="_blank"><img src="images/logos/Funder_TAS.png"></a> <!-- width="50%" link="https://arthritis.ca" %}-->
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4 col5=col5 col6=col6%}

{% include section.html %}

{% capture col1 %}
<a href="https://www.ucalgary.ca" target="_blank"><img src="images/logos/University_of_Calgary.png"></a>
{% endcapture %}

{% capture col2 %}
<a href="https://mccaig.ucalgary.ca" target="_blank"><img src="images/logos/McCaig_Institute.png"></a>
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html %}
