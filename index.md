---
title: Home
---
# Welcome!
This is a test of the remote theme.

{% include alert.html type="info" content="It works!" %}

## Projects

<ul class="project-list">
{% for proj in site.projects %}
  <li><a href="{{ proj.url | relative_url }}">{{ proj.title }}</a></li>
{% endfor %}
</ul>