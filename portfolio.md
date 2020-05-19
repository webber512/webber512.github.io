---
layout: page
path: portfolio
title: Portfolio
---

{% for project in site.projects %}
<h2>
<a href="{{project.url}}">
{{project.name}}
</a>
</h2>
<p>{{ project.content | markdownify}}</p>
{% endfor %}