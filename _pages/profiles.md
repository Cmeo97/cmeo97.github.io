---
layout: page
permalink: /people/
title: Network
description: 
nav: true
nav_order: 5
---

### Mentors
{% assign mentors = site.data.mentors %}
{% for item in site.data.mentors %}
  {% include person-item.liquid %}
{% endfor %}
<br>

### Mentees
{% assign mentees = site.data.mentees %}
{% for item in site.data.mentees %}
  {% include person-item.liquid %}
{% endfor %}
<br>

### Collaborators
{% assign collaborators = site.data.collaborators %}
{% for item in site.data.collaborators %}
  {% include person-item.liquid %}
{% endfor %}
<br>

### Students
{% for student in site.data.students %}
  {% include student-item.liquid student=student %},<br>
{% endfor %}
<br>
