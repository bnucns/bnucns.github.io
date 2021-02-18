---
layout: page
title: Assignments
nav_order: 3
---

{% assign assignments = site.assignments | reverse %}
{% for assignment in assignments %}
{{ assignment }}
{% endfor %}