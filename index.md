---
layout: page
title: Welcome, friends!
tagline: Supporting tagline
---
{% include JB/setup %}

	I'm DarkNiight!!!!!

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



