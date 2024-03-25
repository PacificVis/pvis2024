---
layout: single
title: 'TVCG Papers'
permalink: '/papers/jrnl/'
date: 2024-02-16
---

## TVCG Papers Accepted in Journal Track

{% for p in site.data.accepted_tvcg_jrnl -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}

## TVCG Papers from Regular Issues

{% for p in site.data.tvcg_regular -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}