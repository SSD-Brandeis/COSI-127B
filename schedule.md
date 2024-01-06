---
layout: page
title: Schedule
nav_order: 1
description: Database Management Systems (COSI 127B)
banner_image: /COSI-127B/assets/css/schedule.jpg
banner_heading: "Schedule"
banner_description: "Course Schedule and Important Dates"
---

{% for schedule in site.modules %}
{{ schedule }}
{% endfor %}