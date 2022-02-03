---
title: News
permalink: /news/
---

  {% for post in site.posts %}
  <div style="margin-bottom: 20px;">
      <a style="background-color: #FEFEFE; color: #252A34; width: 100%; height: 40px; text-align: left; padding-left: 20px; text-decoration: none; display: inline-block;" href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <br />
      <div style="font-size: 14px; margin-top: 10px;"> {{ post.excerpt }} </div>
  </div>
  {% endfor %}
