---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Get in touch! We are currently recruiting PhD students.

{%
  include button.html
  type="email"
  text="engelhard-lab@duke.edu"
  link="engelhard-lab@duke.edu"
%}
#{%
#  include button.html
#  type="phone"
#  text="(555) 867-5309"
#  link="+1-555-867-5309"
#%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/rkVx2Ed6xysDh1de9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/hock-plaza_signature_hres_web.jpg"
  caption="Hock Plaza, Duke University Medical Center"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/007319_chapel002.jpg"
  caption="Duke Chapel"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

#{% include section.html dark=true %}
#
#{% capture col1 %}
#Lorem ipsum dolor sit amet  
#consectetur adipiscing elit  
#sed do eiusmod tempor
#{% endcapture %}
#
#{% capture col2 %}
#Lorem ipsum dolor sit amet  
#consectetur adipiscing elit  
#sed do eiusmod tempor
#{% endcapture %}
#
#{% capture col3 %}
#Lorem ipsum dolor sit amet  
#consectetur adipiscing elit  
#sed do eiusmod tempor
#{% endcapture %}
#
#{% include cols.html col1=col1 col2=col2 col3=col3 %}
