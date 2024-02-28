---
layout: single
title: 'Papers Accepted in Visualization Meets AI Workshop'
permalink: '/papers/visxai/'
date: 2024-02-28
---

{% for p in site.data.accepted_visxai -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}