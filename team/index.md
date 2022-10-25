---
title: Team
# nav:
#   order: 3
#   tooltip: About our team
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

{% include section.html background="images/banner.jpg" dark=true%}

<!-- {% include section.html %}

## Join

#### Post Dogtoral Researcher

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

- 3+ (dog) years experience managing bone portfolios
- Strong desire to learn tricks and go on walkies
- Aptitude to sit and stay

{% include link.html type="external" link="https://google.com/" text="Apply Now" icon="" style="button" %}
{:.center} -->
<!-- 
{% include section.html %} -->

## Funding

Our work is made possible by funding from the NIH (R01AG078758) and start-up funds to Dr. Laura Fonken.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/Logo NIH.png"
  link1="https://www.nia.nih.gov/"
  tooltip1="NIH"
%}
