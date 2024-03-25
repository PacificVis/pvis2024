---
layout: single
title: 'Poster Presentations'
permalink: '/papers/posters/'
date: 2024-03-05
---

{% for p in site.data.accepted_posters -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}