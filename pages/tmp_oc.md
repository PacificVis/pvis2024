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
<div style="display: inline-block; width: 32%; text-align: center;">
<!-- img src="{{site.url}}{{site.baseurl}}/assets/images/oc/{{ member.Photo }}" -->
<!-- http://localhost/pvis2024/assets/images/oc/issei_fujishiro.jpg -->
<img src="http://localhost//pvis2024/assets/images/oc/{{ member.Photo }}"
     class="circle" width="150" height="150" /><br />
{{ member.Name }}<br/>
({{ member.Affiliation }})
</div>
{% endfor %}

---

# Journal Track Program Committee Members

(TBA)

| Name               | Affiliation        |
|--------------------|--------------------|
{% for member in site.data.pc_jrnl -%}
{{ member.First }} {{ member.Family }} | {{ member.Affiliation }}
{% endfor %}


# Conference Track Program Committee Members

(TBA)

| Name               | Affiliation        |
|--------------------|--------------------|
{% for member in site.data.pc_conf -%}
{{ member.First }} {{ member.Family }} | {{ member.Affiliation }}
{% endfor %}

# Visualization Notes Program Committee Members

(TBA)
