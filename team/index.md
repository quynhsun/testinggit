---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

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
  filters="role: labman"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%}
{:.center}

{% include section.html %}
## Undergraduate Students

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}


{% include section.html background="images/banner.jpg" dark=true%}

{% include section.html %}

## Lab Alumni

 Kylor Lachut (Undergrad, 2022) <br>
 Clare Melley (Summer Undergrad 2021) <br>
 Pareesha Haresh (Summer Undergrad 2021) <br>

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html

  image1="images/images.jpg"
  link1="https://www.bmc.org/"
  tooltip1="Boston Medical Center"

  image2="images/download.png"
  link2="https://www.nih.gov/"
  tooltip2="NIH"

%}
