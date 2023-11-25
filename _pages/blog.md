---
title: Blog
permalink: /blog
---

{% for post in site.posts %}
	{% include blog-listing.html %}
{% endfor %}
