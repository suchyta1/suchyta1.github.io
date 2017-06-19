---
layout: archive
author_profile: true
permalink: /press/
read_time: false
title: "Press"
---

From time to time, I stumble upon public-facing news stories, press releases, etc. related the projects I work on.
Here's a far from comprehensive, but reasonably representative sample. 


<div class="grid__wrapper">
	{% assign sorted = (site.press | sort: 'date') | reverse %}
	{% for post in sorted %}
		{% include archive-single.html type="grid" %}
	{% endfor %}
</div>

<!--
http://www.npr.org/sections/thetwo-way/2016/10/11/497071139/a-friend-for-pluto-astronomers-find-new-dwarf-planet-in-our-solar-system
http://www.darkenergysurvey.org/darchive/mass-and-galaxy-distributions-of-four-massive-galaxy-clusters-from-dark-energy-survey-science-verification-data/
http://www.darkenergysurvey.org/scientistoftheweek/eric-suchyta/
-->
