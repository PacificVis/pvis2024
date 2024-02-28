---
layout: single
title: 'Papers Accepted in Visualization Notes Track'
permalink: '/papers/visxai/'
date: 2024-02-28
---

{% for p in site.data.accepted_visxai -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}