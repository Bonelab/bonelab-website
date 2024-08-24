---
---
# Welcome!

{% capture content %}
  {%
    include figure.html
    image="images/photos/BIL_CT_Room.jpg"
    width="100%"
  %}
{% endcapture %}

{%
  include float.html
  content=content
  flip=true
%}

The Bone Imaging Laboratory was established in 2004 by Dr. Steven Boyd at the University of Calgary 
and is focused on using advanced imaging and computational methods for understanding the role of bone in joint injuries and disease.
Our goal is to prevent, diagnose and develop interventions to maximize bone health across the lifespan.

We collect novel image data that often involves multiple imaging modalities and develop novel computational approaches to analyse those data.
We publish our findings related to osteoporosis, osteoarthritis, high performance athletes, the effects of vitamin D, how bones are altered 
by space flight, and more.

{% include section.html %}

## Highlights

{% capture text %}

Our research uses **advanced medical imaging and computational methods** to study bone fragility and treatments in **osteoporosis** 
and how to prevent **osteoarthritis** after suffering a joint injury.

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

Our research includes developing methods for fragility **fracture risk**, how bones change in **astronauts**, the effects of 
**vitamin D**, what happens to a **knee joint** after a tear of the ACL, using **machine learning** for assessing bone quality in
**opportunistic CT**, and much more.

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

Our team includes **undergraduate** summer students, **graduate students** doing their MSc or PhD, **post-doctoral fellows**, medical imaging
and computational specialists, **staff**, and **faculty**. We collaborate with people in Calgary and around the world.


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
  image="images/photos/BIL_Stairs.jpg"
  link="team"
  title="Our Team"
  text=text
%}

{% 
  include button.html 
  type="link"
  text="Thinking of applying? Learn more here"
  icon="fa-solid fa-circle-plus fa-beat"
  link="about"
  tooltip="Information about the application process"
  style="button" 
%}

{% include section.html %}

## Funding
{% capture col1 %}
<a href="https://cihr-irsc.gc.ca/e/193.html"><img src="images/logos/Funder_CIHR.png"></a> <!-- width="50%" link="https://cihr-irsc.gc.ca/e/193.html" %}-->
{% endcapture %}

{% capture col2 %}
<a href="https://www.nserc-crsng.gc.ca/index_eng.asp"><img src="images/logos/Funder_NSERC.png"></a> <!-- width="50%" link="https://www.nserc-crsng.gc.ca/index_eng.asp" %}-->
{% endcapture %}

{% capture col3 %}
<a href="https://albertainnovates.ca/about/who-we-are/teams/health-innovations-team/"><img src="images/logos/Funder_AI.png"></a> <!-- width="50%" link="https://albertainnovates.ca/about/who-we-are/teams/health-innovations-team/" %}-->
{% endcapture %}

{% capture col4 %}
<a href="https://www.innovation.ca"><img src="images/logos/Funder_CFI.png"></a> <!-- width="50%" link="https://www.innovation.ca" %}-->
{% endcapture %}

{% capture col5 %}
<a href="https://www.asc-csa.gc.ca/eng/"><img src="images/logos/Funder_CSA.png"></a> <!-- width="50%" link="https://www.asc-csa.gc.ca/eng/" %}-->
{% endcapture %}

{% capture col6 %}
<a href="https://arthritis.ca"><img src="images/logos/Funder_TAS.png"></a> <!-- width="50%" link="https://arthritis.ca" %}-->
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4 col5=col5 col6=col6%}

{% include section.html %}

{% capture col1 %}
<a href="https://www.ucalgary.ca"><img src="images/logos/University_of_Calgary.png"></a>
{% endcapture %}

{% capture col2 %}
<a href="https://mccaig.ucalgary.ca"><img src="images/logos/McCaig_Institute.png"></a>
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html %}
