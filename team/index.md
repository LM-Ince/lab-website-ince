---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

I am an Assistant Professor at Pomona College in Claremont, CA. 
If you are a student in the Claremont Colleges and interested in joining the lab for senior thesis or research experience, please email me or stop by one of my classes.

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: PI"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="group: current, role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="group: current, role: undergrad" 
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="group: current, role: technician"
  %}
{:.center}

{% include section.html %}

## Alumni
{% 
  include list.html 
  data="members" 
  component="portrait" 
  filters="group: alum, role: phd" 
%} 
{% 
  include list.html 
  data="members" 
  component="portrait" 
  filters="group: alum, role: undergrad" 
%} 
{% 
  include list.html 
  data="members" 
  component="portrait" 
  filters="group: alum, role: technician" 
%} 

{:.center}

{% include section.html %}

## Funding

{% capture text %}
Our work is made possible by funding from the NIH (R01AG078758 - PI: Laura Fonken, Co-I: Louise Ince, Co-I: Andrew Gaudet) and start-up funds to Louise Ince.

{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/Logo NIH.png"
  imagetitle="NIA"
  text=text
%}
