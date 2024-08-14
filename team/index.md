---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab consists of a dynamic and collaborative group of researchers who are deeply engaged in their work. We understand that diverse teams produce superior research. We cultivate an environment where every team member is valued equally, and where our differences are respected and celebrated. Our team includes postdocs, students at all levels, staff, and our lab mascots.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: technician, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

{% include section.html background="images/background.jpg" dark=true %}

We collaborate with an array of exceptional teams from across the globe and continually seek out fresh and unique perspectives. Our goal is to advance the frontiers of data science and to mentor the next generation of data scientists.

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="join"
  style="button"
%}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: technician, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: alum" style="small" %}

{% include section.html %}

## Funding

{% capture content %}
[![Gordon and Betty Moore Foundation](/images/Funding/2012-logo.png)](https://www.moore.org/)

[![National Cancer Institute](/images/Funding/DoD-Logo-Stacked.png)](https://www.cancer.gov/)

[![Alex's Lemonade Stand Foundation for Childhood Cancer](/images/team/alex's-lemonade-stand-foundation-for-childhood-cancer.png)](https://www.alexslemonade.org/)

[![Chan Zuckerberg Initiative](/images/team/chan-zuckerberg-initiative.png)](https://chanzuckerberg.com/)

[![Cystic Fibrosis Foundation](/images/team/cystic-fibrosis-foundation.png)](https://www.cff.org/)

[![Alfred P. Sloan Foundation](/images/team/alfred-p-sloan-foundation.png)](https://sloan.org/)

[![National Human Genome Research Institute](/images/team/national-human-genome-research-institute.png)](https://www.genome.gov/)

[![National Heart, Lung, and Blood Institute](/images/team/national-heart-lung-and-blood-institute.png)](https://www.nhlbi.nih.gov/)

[![National Institute of Neurological Disorders and Stroke](/images/team/national-institute-of-neurological-disorders-and-stroke.png)](https://www.ninds.nih.gov/)

{% endcapture %}

{% include grid.html style="square" content=content %}
