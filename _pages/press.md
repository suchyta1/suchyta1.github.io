---
layout: archive
author_profile: true
permalink: /press/
read_time: false
title: "Press"
---

It's not uncommon to stumble upon public-facing news stories, press releases, etc. related to the projects I work on.
Here's a far from comprehensive, but reasonably representative sample. 


<div class="grid__wrapper">
	{% assign sorted = (site.press | sort: 'date') | reverse %}
	{% for post in sorted %}
		{% include archive-single.html type="grid" %}
	{% endfor %}
</div>

<!--
http://www.darkenergysurvey.org/scientistoftheweek/eric-suchyta/
-->
