---
---
# Welcome!

{% capture content %}
  {%
    include figure.html
    image="images/photos/BIL CT Room.jpg"
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
  image="images/general/VITD2-cropped.png"
  link="research"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our team includes **undergraduate** summer students, **graduate students** doing their MSc or PhD, **post-doctoral fellows**, medical imaging
and computational specialists *staff*, and **faculty**. We collaborate with people in Calgary and around the world.


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
  text="Learn more!"
  icon="fa-solid fa-handshake"
  link="about"
  tooltip="Learn more"
  style="button" 
%}

{% include section.html %}

## Funding

{% include figure.html width="100%" image="images/logos/funders.png" %}

{% include section.html %}

## Useful Links
{% capture content %}
  {% include figure.html image="images/logos/Logo_MyUofC_555_200.png" link="https://login.my.ucalgary.ca" %}
  {% include figure.html image="images/logos/Logo_McCaig_555_200.png" link="https://mccaig.ucalgary.ca" %}
  {% include figure.html image="images/logos/Logo_Altmetric_555_200.png" link="https://www.altmetric.com/details/65516542" %}
  {% include figure.html image="images/logos/Logo_BoneLab_555_200.png" link="https://ucalgary.ca/people/steven-boyd" %}
  {% include figure.html image="images/logos/Logo_BoneWiki_555_200.png" link="http://bone.wiki" %}
  {% include figure.html image="images/logos/Logo_Orcid_555_200.png" link="http://orcid.org/0000-0002-2930-5997" %}
  {% include figure.html image="images/logos/Logo_PubMed_555_200.png" link="https://pubmed.ncbi.nlm.nih.gov/advanced/" %}
  {% include figure.html image="images/logos/Logo_Scopus_555_200.png" link="https://www.scopus.com/authid/detail.uri?authorId=56216683100" %}
{% endcapture %}
{% include grid.html content=content %}
