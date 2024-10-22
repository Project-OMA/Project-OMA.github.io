---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team is a multidisciplinary and complementary team that brings together professors and undergraduate, master's, and PhD students from the Federal University of Ceará, CEFET/RJ, and IFCE/CE, with experience in software development and orientation and mobility.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html dark=true %}

We sincerely thank all our partners and supporters for their invaluable contributions to this project. The collaboration of our partners and supporters is essential to our success.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/cnpq.jpg" %}
{% include figure.html image="images/funcap.jpg" %}
{% include figure.html image="images/capes.jpg" %}
{% include figure.html image="images/great.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
