---
layout: page
title: Academical service
permalink: /teaching
---


### Teaching
{% assign teaching = site.data.teaching | sort: 'year' | reverse %}
{% for item in site.data.teaching %}
  {% include teaching-item.html %}
{% endfor %}
<br>


### Voluntary work
- **Organiser** of AI Job Fair in Delft (ongoing).
- **Reviewer** for ICML, NeurIPS and ICLR. 
- **PhD Council representative** at [Delft University of Technology](https://www.tudelft.nl/en/eemcs/the-faculty/eemcs-phd-council). 
- **Supervisor** of several MSc students at TUDelft and [National University of Singapore](https://www.cogai4sci.com). 
<br>

### Awards
- **Infineon’s IPCEI PhD Booster Scholarship** award obtained in 2023, it provides a 4 years scholarship to travel, attend conferences and world wide events.  
- **SURF Compute Grant** to conduct research on SURF supercomputer. 
