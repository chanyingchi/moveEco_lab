---
---

## Welcome to the website of the Movement Ecology and Conservation Lab!


{% include section.html %}

### Research themes:
- Animal movement ecology in Southeast Asia
- Applications of movement data in conservation
- Avian ecology and conservation in Asia

{% include section.html %}

{% capture text %}



{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/homepage_photo_projects.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

{%
  include button.html
  link="team"
  text="Meet our people"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo_team.jpg"
  link="team"
  title="Our People"
  text=text
%}
