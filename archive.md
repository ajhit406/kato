---
layout: default
title: kaitlin solimine
lnav: News
---

# News Archive

<ul class="posts">
  {% for post in site.posts %}
  	<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>