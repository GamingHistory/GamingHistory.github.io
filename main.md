---
layout: default
title: GamingHistory Blog!
---

{% for post in site.posts %}
<hr/>
<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
{{ post.date | date_to_long_string }}
{{ post.content }}
{% endfor %}
