---
title: Clinic
nav:
  order: 5
---

# Clinic

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.


{% include section.html %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% capture col1 %}

{%
  include figure.html
  image="images/preddict.jpg"
  caption="Investigating the genetic and environmental factors associated with Premenstrual Dysphoric Disorder (PMDD) and severe Premenstrual Syndrome (PMS)"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/research.png"
  caption="Understanding severe mental illness during pregnancy and following childbirth to improve treatments and support"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}


