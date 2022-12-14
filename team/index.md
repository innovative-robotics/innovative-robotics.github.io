---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Interested in robotics? Want to do research? Email petras.swissler@njit.edu

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
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
  filters="role: programmer"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

---

{% include section.html %}

## Join

#### PhD Student, Mechanical Engineering

We are looking for a new PhD student who is interested in developing novel robot hardware to explore new challenges.

- Willingness to learn new disciplines a must
- Experience with mechatronic systems a plus
- Experience programming a plus
- Fully-funded position

{% include link.html type="external" link="https://www.njit.edu/admissions/how-apply-graduate-admissions" text="Apply Now" icon="" style="button" %}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from:
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/placeholder.svg"

  image2="images/logo_njit.png"
  link1="https://njit.edu"
  tooltip1="New Jersey Institute of Technology"
  
  image3="images/placeholder.svg"
%}
