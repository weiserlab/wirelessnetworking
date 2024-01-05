---
layout: page
title: Schedule
description: The weekly event schedule.
---

# Weekly Schedule

The lectures begin the week starting 15th January 2024. The tutorials begin the week starting 22nd of January 2024.

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
