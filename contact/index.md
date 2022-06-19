---
title: Contact
nav:
  order: 3
  tooltip: Email, address, and location
---

# <i class="fas fa-paper-plane"></i>Contact

{% capture text %}
Our lab is part of the Department of Medicine, Division of Hematology/Oncology at the [IU School of Medicine](https://medicine.iu.edu/).
{% endcapture %}

{%
  include link.html
  type="email"
  icon=""
  text="amasood@iu.edu"
  tooltip=""
  link="amasood@iu.edu"
  style="button"
%}
{%
  include link.html
  type="phone"
  icon=""
  text="(317) 948-7575"
  tooltip=""
  link="+1-317-948-7575"
  style="button"
%}
{%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/dtq4xSufwziKhiyR7"
  style="button"
%}
{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address

535 Barnhill Drive
RT 473
Indianapolis, IN 46202
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="The Center for Wit and Sagacity"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Department of Metaphor"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
