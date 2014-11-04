---
layout: page
title: Welcome to our JDH C School
---
{% include JB/setup %}
    
##  Let's learn about 'C Programming'

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




