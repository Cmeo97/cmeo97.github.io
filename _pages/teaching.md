---
layout: page
title: Academical service
permalink: /teaching
nav: true
nav_order: 4
---


### Teaching
{% assign teaching = site.data.teaching | sort: 'year' | reverse %}
{% for item in site.data.teaching %}
  {% include teaching-item.liquid %}
{% endfor %}
<br>

### Supervision
{% assign teaching = site.data.supervision | sort: 'year' | reverse %}
{% for item in site.data.supervision %}
  {% include teaching-item.liquid %}
{% endfor %}
<br>


### Voluntary work
- **Organiser** of AI Job Fair in Delft (ongoing).
- **Reviewer** for ICML, NeurIPS and ICLR. 
- **PhD Council representative** at [Delft University of Technology](https://www.tudelft.nl/en/eemcs/the-faculty/eemcs-phd-council). 
- **Supervisor** of several MSc students at TUDelft and [National University of Singapore](https://www.cogai4sci.com). 
<br>

