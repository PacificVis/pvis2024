---
layout: single
title: 'Conference Committees'
permalink: '/committees/'
date: 2023-09-06
---

- [Organization Committee Members](#organization-committee-members)

- [Journal Track Program Committee Members](#journal-track-program-committee-members)

- [Conference Track Program Committee Members](#conference-track-program-committee-members)

- [Visualization Notes Program Committee Members](#visualization-notes-program-committee-members)

---

# Organization Committee Members

{% assign role = '' %}

{% for member in site.data.oc -%}
{% if role != member.Role %}

## {{ member.Role }}
{% assign role = member.Role %}
{% endif %}
<div style="display: inline-block; width: 32%; text-align: center;">
<img src="/pvis2024/assets/images/oc/{{ member.Photo }}"
     class="circle" width="150" height="150" /><br />
{{ member.Name }}<br/>
({{ member.Affiliation }})
</div>
{% endfor %}

---

# Journal Track Program Committee Members

| Name               | Affiliation        |
|--------------------|--------------------|
{% for member in site.data.pc_jrnl -%}
{{ member.First }} {{ member.Family }} | {{ member.Affiliation }}
{% endfor %}


# Conference Track Program Committee Members

| Name               | Affiliation        |
|--------------------|--------------------|
{% for member in site.data.pc_conf -%}
{{ member.First }} {{ member.Family }} | {{ member.Affiliation }}
{% endfor %}

# Visualization Notes Program Committee Members

| Name               | Affiliation        |
|--------------------|--------------------|
{% for member in site.data.pc_notes -%}
{{ member.Name }} | {{ member.Affiliation }}
{% endfor %}