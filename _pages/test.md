---
layout: single
author_profile: true
permalink: /test/
title: "Publications"

t: other
arr:
   - testing
---

{% include group-by-array collection=site.posts field="categories" %}
{% assign posts = site.posts | where:"categories","software" %}

<div class='entry'>
	{% for post in posts %}
			 <h2 id="other" class="archive__subtitle">other</h2>
			{{ post.content | markdownify }}
	{% endfor %}
</div>

