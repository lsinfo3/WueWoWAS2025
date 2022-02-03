---
title: News
permalink: /news/
---

<ul>
  {% for post in site.posts %}
    <li>
      <a style="background-color: #f44336; color: white; width: 90%; height: 20px; text-align: center; text-decoration: none; display: inline-block;" href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <br />
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
