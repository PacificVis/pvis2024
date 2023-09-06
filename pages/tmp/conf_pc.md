---
layout: single
title: 'Conference Track Program Committee Members'
permalink: '/tmp/conf_pc/'
date: 2023-09-06
---

| Name               | Affiliation        |
|--------------------|--------------------|
{% for member in site.data.pc_conf -%}
{{ member.First }} {{ member.Family }} | {{ member.Affiliation }}
{% endfor %}
