# {{ etitle }}

|                         | Dates          |
| ------------------------|----------------|
{% for date in important_dates -%}
{%- if date['Event Type'] == etype -%}| {{ date.Event }} | {{ date.Date }} |
{% else -%}{%- endif -%}
{% endfor %}
