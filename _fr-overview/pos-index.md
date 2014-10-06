---
layout: base
title:  'POS tags'
generated: 'true'
permalink: fr/pos/index.html
---

# POS tags

{% include fr-pos-table.html %}

----------

Alphabetical listing

<ul>
{% for p in site.fr-pos %}
  <li><a href="{{ p.title }}.html" class="doclabel">{{ p.title }}</a>: {{ p.shortdef }}</li>
{% endfor %}
</ul>