---
layout: default
title: All Posts
---

<p style='text-align:center;'> I'm keeping a log of my projects. Here they are! </p>

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
