---
title: Team
nav:
  order: 1
---

# Team

<center> The reproductive mental health team is led by Prof Arianna Di Florio. </center>

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

<br>
<br>

{% include list.html data="members" component="portrait" filter="role == 'phd' || role == 'postdoc'" %}

<br>

{% include list.html data="members" component="portrait" filter="role == 'professional-services'" %}

<br>

{% include list.html data="members" component="portrait" filter="role != 'friend' && role == 'developer' || role == 'mascot'" %}

<br>
<br>

{% include section.html %}

# Friends of the Group

{% include list_v2.html data="members" component="portrait" style = "small" filter="role == 'friend'" %}