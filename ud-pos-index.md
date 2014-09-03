---
layout: base
title:  'Universal POS tags'
generated: 'true'
---

# Universal POS tags

Alphabetical listing

<ul>
{% for p in site.ud-pos %}
  <li><a href="{{ p.url | remove_first:'/' }}">{{ p.title }}</a>: {{ p.shortdef }}</li>
{% endfor %}
</ul>