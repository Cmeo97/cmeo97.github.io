---
layout: page
permalink: /people/
title: Network
description: 
nav: true
nav_order: 5
---

### Mentors
{% for mentor in site.data.mentors %}
  {% include person-item.liquid person=mentor %}
{% endfor %}
<br>

### Mentees
{% for mentee in site.data.mentees %}
  {% include person-item.liquid person=mentee %}
{% endfor %}
<br>

### Collaborators
{% for collaborator in site.data.collaborators %}
  {% include person-item.liquid person=collaborator %}
{% endfor %}
<br>

### Students
{% for student in site.data.students %}
  {% include student-item.liquid student=student %}
{% endfor %}
<br>
