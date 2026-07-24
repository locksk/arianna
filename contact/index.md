---
title: Contact
nav:
  order: 8
---

# Contact

<center> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <center> 

{%
  include button.html
  type="email"
  text="E-mail"
  link="reproductivementalhealth@cardiff.ac.uk"
%}
{%
  include button.html
  type="phone"
  text="Phone"
  link="+44 29206 88382"
%}
{%
  include button.html
  type="address"
  text="Address"
  link="https://maps.app.goo.gl/mGUrehMZj1aKULRV8"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/cardiff.jpg"
  caption="Cardiff University Main Building"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/heb.jpg"
  caption="Hadyn Ellis Building"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
