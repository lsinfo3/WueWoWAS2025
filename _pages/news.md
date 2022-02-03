---
title: News
permalink: /news/
---

  {% for post in site.posts %}
  <div>
      <a style="background-color: #FEFEFE; color: #252A34; width: 90%; height: 40px; text-align: center; text-decoration: none; display: inline-block;" href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <br />
      <span style="font-size: 12px"> {{ post.excerpt }} </span>
  </div>
  {% endfor %}
