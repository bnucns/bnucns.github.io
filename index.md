---
layout: home
title: Home
nav_exclude: true
seo:
  type: Course
  name: Home
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{% if site.announcements.size < 3 %}
    {% assign announcements = site.announcements | reverse %}
    {% assign num_announcements = announcements | size %}
    {% for announcement in announcements limit:num_announcements %}
        {{ announcement }}
    {% endfor %}
{% else %}
    {% assign announcements = site.announcements | reverse %}
    {% for announcement in announcements limit:3 %}
        {{ announcement }}
    {% endfor %}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## Reminders

