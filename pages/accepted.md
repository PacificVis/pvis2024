---
layout: single
title: 'Accepted Papers / Program'
permalink: '/accepted/'
date: 2024-01-30
---

## Banquet: April 25 (Thu)

The PacifivVis 2024 banquet takes place on a cruise boat!

<center>
<img src="/pvis2024/assets/images/banquet/6940-7138mix.jpg" width="100%" />
</center>

In the course of modernization, the cityscape of Edo, once ruled by Samurai warriors, has been transformed into the modern city of Tokyo. Would you like to travel back 150 years in time on a "yakatabune" (traditional Japanese houseboat) filled with the atmosphere of the Edo period? The evening view of modern Tokyo from inside the boat in the full bloom of Edo is exceptional.

---

## TVCG Papers Accepted in Journal Track

{% for p in site.data.accepted_tvcg_jrnl -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}

## TVCG Papers from Regular Issues

{% for p in site.data.tvcg_regular -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}

## Papers Accepted in Conference Track

{% for p in site.data.accepted_conf -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}

## Papers Accepted in Visualization Notes Track

{% for p in site.data.accepted_notes -%}
- {{ p.authors }}, "{{ p.title }}."
{% endfor %}