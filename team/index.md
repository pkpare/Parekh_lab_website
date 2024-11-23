---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team



{% include section.html %}

## Current Members

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include list.html data="members" component="portrait" filters="role: Research Assistant II" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!Research Assistant II$)" %}

{% include list.html data="members" component="portrait" filters="role: Research Assistant II" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!Research Assistant II$)" %}

{% include section.html %}
