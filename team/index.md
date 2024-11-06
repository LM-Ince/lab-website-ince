---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

I am a Research Scientist in the [Fonken lab](https://www.fonkenlab.com/) and I currently mentor 3 undergraduate students:

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: research scientist"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
  filters="group: current" 
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
  filters="group: current" 
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: technician"
  filters="group: current" 
%}
{:.center}

{% include section.html %}

{% include section.html %}
## Alumni
{% 
  include list.html 
  data="members" 
  component="portrait" 
  filters="role: phd" 
  filters="group: alum" 
%} 
{% 
  include list.html 
  data="members" 
  component="portrait" 
  filters="role: undergrad" 
  filters="group: alum" 
%} 
{% 
  include list.html 
  data="members" 
  component="portrait" 
  filters="role: technician" 
  filters="group: alum" 
%} 
{:.center}

{% include section.html %}

## Funding

{% capture text %}
Our work is made possible by funding from the NIH (R01AG078758 - PI: Laura Fonken, Co-I: Louise Ince, Co-I: Andrew Gaudet) and start-up funds to Laura Fonken.

{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/Logo NIH.png"
  imagetitle="NIA"
  text=text
%}
