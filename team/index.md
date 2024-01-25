---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}MATCH LAB TEAM

Graduate students in the Marra lab are in the [UBC Bioinformatics Training Program](https://www.grad.ubc.ca/prospective-students/graduate-degree-programs/phd-bioinformatics), [UBC Genome Sciences and Technology Program (GSAT)](https://www.grad.ubc.ca/prospective-students/graduate-degree-programs/phd-genome-science-technology), and the [UBC Medical Genetics Program](https://www.grad.ubc.ca/prospective-students/graduate-degree-programs/phd-medical-genetics). Trainees are working on characterizing cancer driver mutations and other alterations relevant to cancer, or on projects designed to identify and study critical cancer genes and pathways.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
