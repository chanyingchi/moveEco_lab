---
title: People
nav:
  order: 2
  tooltip: 
---

# {% include icon.html icon="fa-solid fa-users" %}Lab Members


{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

{% capture content %}


{% endcapture %}

{% include grid.html style="square" content=content %}

Are you interested to join us? Click [here](https://chanyingchi.github.io/moveEco_lab/contact/) to find out more!
