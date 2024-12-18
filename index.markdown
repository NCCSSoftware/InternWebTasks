---
layout: default
title: "Hello World"
---

# InternWebTasks
Tasks For Intern Web


This is a repository that contains the tasts to be done by the team "InternWeb"
<ul>
{% for post in site.posts %}
{% if post.type == "task" %}
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
<hr>

Additional Resources:
<ul>
{% for post in site.posts %}
{% if post.type == "resource" %}
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
