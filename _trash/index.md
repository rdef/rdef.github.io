---
title: coding blog
description: robbie fordyce - coding and research blog 
---
<h2>Latest Posts</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
