---
layout: base
title:  'Features'
generated: 'true'
permalink: el/feat/all.html
---

# Features

{% include el-feat-table.html %}

----------

{% for p in site.el-feat %}
<h2><code>{{ p.title }}</code>: {{ p.shortdef }}</h2>
{% if p.content contains "<!--details-->" %}    
{{ p.content | split:"<!--details-->" | first }}
<a href="{{ p.title }}">See details</a>
{% else %}
{{ p.content }}
{% endif %}
<a href="{{ site.git_edit }}/_el-feat/{{ p.title }}.md" target="#">edit {{ p.title }}</a>
{% endfor %}