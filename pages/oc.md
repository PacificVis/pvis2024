---
layout: single
title: 'Conference Committees'
permalink: '/tmp/committees/'
date: 2023-09-06
---

{% assign role = '' %}

{% for member in site.data.oc -%}
{% if role != member.Role %}

## {{ member.Role }}
{% assign role = member.Role %}
{% endif %}
- {{ member.Name }} ({{ member.Affiliation }})
{% endfor %}

---

# Journal Track Program Committee Members

# Conference Track Program Committee Members

# Visualization Notes Program Committee Members
