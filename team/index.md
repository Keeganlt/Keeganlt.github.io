---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

## Current Team

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: research-assoc" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: masters" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

## Alumni 

{% include list.html data="members" component="portrait" filters="role: alumni" %}

{% include section.html dark=true %}

Interested in joining us? Take a look at our [current opportunities](https://keeganlt.github.io/AppliedIDD-website/opportunities/).

{% include section.html %}

{% capture content %}

{% include figure.html image="images/CDC_Talk.png" %}
{% include figure.html image="images/AlaiyahPoster.png" %}
{% include figure.html image="images/TierneyCDC.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
