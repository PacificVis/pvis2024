---
layout: single
title: 'Papers Accepted in Conference Track'
permalink: '/papers/conf/'
date: 2024-02-16
---

{% for p in site.data.accepted_conf -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}
