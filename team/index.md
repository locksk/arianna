---
title: Team
nav:
  order: 1
---

# Team

<center> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </center>

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

<br>
<br>

{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}



