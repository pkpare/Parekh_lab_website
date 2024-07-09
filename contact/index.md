---
title: Contact
nav:
  order: 5
  tooltip: Find us
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please feel free to reach out with any questions. 

{%
  include button.html
  type="email"
  text="pkp2002@med.cornell.edu"
  link="pkp2002@med.cornell.edu"
%}
{%
  include button.html
  type="phone"
  text=""
  link=""
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps"
  link="https://www.google.com/maps/place/School+of+Behavioral+and+Brain+Sciences/@32.9884781,-96.7502993,17z/data=!3m1!4b1!4m6!3m5!1s0x864c1f6fae01fb9b:0x725fb18b86a74062!8m2!3d32.9884736!4d-96.747719!16s%2Fg%2F11fd_qts1z?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/BBS.jpeg"
  caption="School of Behavioral and Brain Sciences"

  include button.html
  link="https://bbs.utdallas.edu"
%}

{%
  include figure.html
  image="images/UTDcampus.jpeg"
  caption="UTD Campus"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 %}

{% include section.html dark=true %}


