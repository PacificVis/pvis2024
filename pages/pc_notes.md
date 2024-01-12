---
layout: single
title: 'Visualization Notes Program Committee Members'
permalink: '/tmp/notes_pc/'
date: 2023-09-06
---

| Name               | Affiliation        |
|--------------------|--------------------|
{% for member in site.data.pc_notes -%}
{{ member.Name }} | {{ member.Affiliation }}
{% endfor %}