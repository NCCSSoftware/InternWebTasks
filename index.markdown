---
layout: default
title: "Tasks for Learning Laravel"
---

# Intern Web Tasks

This is a repository that contains the tasts to be done by the team "InternWeb"
<table>
  <tr>
    <th>Title</th>
    <th>Deadline</th>
  </tr>
  {% assign sorted_tasks = site.posts | where: "type", "task" | sort: "date" %}
  {% for post in sorted_tasks %}
  <tr>
    <td><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></td>
    <td>{{ post.deadline }}</td>
  </tr>
  {% endfor %}
</table>
<hr>

Additional Resources:
<ul>
{% for post in site.posts %}
{% if post.type == "resource" %}
<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
