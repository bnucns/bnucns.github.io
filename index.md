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
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## Reminders

- In W4, the lecture (Mar 16) and office hour (Mar 17) is canceled due to the University regulation. 
