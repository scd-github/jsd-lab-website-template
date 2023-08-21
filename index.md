---
title: Home
carousels:
  - images:
    - image: images/limits 2023.png
      url: "https://limits.pubpub.org/pub/iw8v1y2m/release/1"
    - image: images/curbcut.png
      url: "https://toronto.curbcut.ca/"
    - image: images/insolvent.png
      url: insolvent
---

{% include carousel.html height="40" unit="%" duration="7" number="1" %}


{% include section.html background="images/green.png" dark=true %}

# {% include icon.html icon="fa-solid fa-feather-pointed" %} Just Sustainability Design Lab

{% include section.html %}

## What We Do and Why

The overarching theme of our group is to conduct  **impactful research on designing information technology for sustainability and social justice, which converge in just sustainability**. The aim is often to enact meaningful change in tech to meet the urgent need for sustainability and social justice. 

We do that through a combination of:
1. critical examinations of the politics, values, and cognitive processes of design
2. the development of methods and tools for just sustainability design 
3. design projects to bring forth just sustainabilities in urban contexts

## Recent Projects
{% include list.html component="card" data="projects" filters="group: " style="small" %}

## Who We Are
### Current Members
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

### Alumni
- Curtis McCord (PhD '22)
- Dawn Walker (PhD '22)

[##]: #

{%
  include button.html
  type=""
  text="Joining the Lab"
  link=prospective students
%}

## Research Funding

{% capture col1 %}

{%
  include figure.html
  image="images/uoft-school-of-cities.jpg"
  caption="School of Cities"
  height="105px"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/ontario research fund.jpg"
  caption="Ontario Research Fund"
  height="105px"

%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/NSERC.jpg"
  caption="NSERC"
  height="105px"
%}

{% endcapture %}

{% capture col4 %}

{%
  include figure.html
  image="images/innovation-ca-canada-foundation-for-innovation-cfi-logo-vector.png"
  caption="Canada Foundation for Innovation"
  height="105px"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4 %}

{% include section.html background="images/green.png" dark=true %}

# {% include icon.html icon="fa-solid fa-microscope" %} Introducing Just Sustainability Design

{% include section.html %}

### *Computing is insolvent: unable to pay its debts to our planet and its societies. JSD reorients tech work so we can build a better future together.*

## What is Just Sustainability Design
Just Sustainability Design, JSD for short, is a framework for systems design practice, research, and pedagogy that privileges sustainability and justice and therefore, the asymmetric and uneven effects of systems design choices at a distance. JSD aims to bring about improvement, not just avoid damage. 

JSD was introduced in Professor Becker's book, Insolvent: How to reorient computing for just sustainability appeared at MIT Press in 2023. If you want to learn more about Just Sustainability Design, see the resources below.


{% capture col1 %}

{%
  include figure.html
  image="images/compulsory.png"
%}

{% endcapture %}

{% capture col2 %}

{%
  include button.html
  type=""
  text="Read Insolvent For Free"
  link="https://direct.mit.edu/books/oa-monograph/5594/InsolventHow-to-Reorient-Computing-for-Just"
%}

{% endcapture %}

{% capture col3 %}

{%
  include button.html
  type=""
  text="Get Your Copy"
  link="https://mitpress.mit.edu/9780262545600/insolvent/"
%}

{% endcapture %}

{% capture col4 %}

{%
  include button.html
  type=""
  text="Learn More About Insolvent"
  link="https://scd-github.github.io/jsd-lab-website-template/insolvent/"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4 %}


