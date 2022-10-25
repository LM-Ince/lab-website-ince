---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

I am a research associate in the [Fonken lab](https://www.fonkenlab.com/) and I currently mentor 2 awesome undergraduate students:

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: research associate"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergraduate"
%}
{:.center}

{% include section.html %}

## Funding

{% capture text %}
Our work is made possible by funding from the NIH (R01AG078758 - PI: Laura Fonken, Co-I: Louise Ince, Co-I: Andrew Gaudet) and start-up funds to Dr. Laura Fonken.

{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/Logo NIH.png"
  imagetitle="NIA"
  text=text
%}
