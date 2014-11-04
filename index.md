---
layout: page
title: Welcome to our JDH C++ School
---
{% include JB/setup %}

## Why I Created C++
<iframe width="400" height="400" src="//www.youtube.com/embed/JBjjnqG0BP8" frameborder="0" allowfullscreen></iframe>

<br><br>
<h1> C++ Parts</h1>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




