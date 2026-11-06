---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

I am Assistant Professor of Neuroscience at Pomona College in Claremont, CA, but my research would not be possible without this dedicated team of students! 

If you are a student in the Claremont Colleges and interested in joining the lab for senior thesis or research experience, please complete this form and email Prof. Ince with a short description of your research experience/interest:

<a href="https://forms.gle/NhLruhkEd4grhsz17">
  <button style="padding: 10px 20px; background-color: #da4409; color: white; border: none; border-radius: 6px; font-weight: 600; cursor: pointer;">
    Ince Lab Application Form
  </button>
</a>

**Spring 2027:** Prof. Ince is no longer taking applications for research placements in Spring 2027.

**Summer 2027:** Pomona SURP applications are welcomed! Please complete the above form and reach out if you are interested in a Summer project. 

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

## Alumni (Fonken Lab)
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
Our work is made possible by start-up funds to Louise Ince and previous grant funding from the NIH (R01AG078758 - PI: Laura Fonken, Co-I: Louise Ince, Co-I: Andrew Gaudet).

{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/Logo NIH.png"
  imagetitle="NIA"
  text=text
%}
