---
layout: "page"
title: "Royal Carp Tackle"
permalink: 'royal-carp-tackle'
technologies:
 - Wordpress
 - Bootstrap
logo: "/assets/images/rct.png"
image: ""
site_url: "http://royalcarptackle.nl"
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">Coming soon..
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		{% include project_image.md %}
	</div>
</div>