---
layout: single
title: 'Accepted Papers'
permalink: '/accepted/'
date: 2024-01-30
---

# TVCG Papers Accepted in Journal Track

{% for p in site.data.tvcg_accepted_jrnl -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}

# TVCG Papers from Regular Issues

{% for p in site.data.tvcg_from_regular -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}

# Papers Accepted in Conference Track

{% for p in site.data.conf_accepted -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}