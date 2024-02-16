---
layout: single
title: 'Papers Accepted in Visualization Notes Track'
permalink: '/papers/notes/'
date: 2024-02-16
---

{% for p in site.data.accepted_notes -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}