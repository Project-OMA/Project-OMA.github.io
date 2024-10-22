---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our team is a multidisciplinary and complementary team that brings together professors and undergraduate, master's, and PhD students from the Federal University of Ceará, CEFET/RJ, and IFCE/CE, with experience in software development and orientation and mobility.

{%
  include button.html
  type="email"
  text="agebson"
  link="agebson@ifce.edu.br"
%}
{%
  include button.html
  type="address"
  tooltip="IFCE/CE - Campus Maracanaú"
  link="https://maps.app.goo.gl/gFqYh2DgzSafRevx7"
%}
{%
  include button.html
  type="email"
  text="joel"
  link="jsantos@eic.cefet-rj.br"
%}
{%
  include button.html
  type="address"
  tooltip="CEFET/RJ - Unidade Maracanã"
  link="https://maps.app.goo.gl/dy13StKA6rtGiZq57"
%}
{%
  include button.html
  type="email"
  text="windson"
  link="windson@virtual.ufc.br"
%}
{%
  include button.html
  type="address"
  tooltip="Great/UFC"
  link="https://maps.app.goo.gl/oepSdQ18VLS87G9Z7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/cefet_rj.png"
  caption="CEFET/RJ"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/great_ufc.png"
  caption="Great/UFC"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/ifce_maracanau.png"
  caption="IFCE/CE"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}