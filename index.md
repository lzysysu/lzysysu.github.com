---
layout: index
title: Down To This
tagline: You get the ankles and I'll get the wrists.
---
{% include JB/setup %}
# Intros
Hi!My name is Litchi lee
<a href="{{ BASE_PATH }}{{ site.posts.first.url }}"><h2>{{ site.posts.first.title }}</h2></a>

{{ site.posts.first.content | strip_html | truncatewords: 25 }} <a href="{{ BASE_PATH }}{{ site.posts.first.url }}">Read More</a>

<hr width="30%">
{% include recent.html %}
