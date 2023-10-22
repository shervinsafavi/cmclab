---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Description on the phylosphy of the lab on team members

{% include section.html %}

{% include list.html data="members" component="portrait" filters="group: "%}

{% include section.html background="images/background.jpg" dark=true %}

A description and a bottom link to join the lab.

{% include button.html icon="fa-solid fa-handshake-angle" text="Join our Team" link="join" style="button" %}



{% include section.html %}

## Alumni

Gone but never forgotten.
These are past lab members who have moved on to other school programs, new jobs, or elsewhere.
They have all made lasting contributions to science and to our hearts. ❤️

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: alum" style="small" %}
