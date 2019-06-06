---
layout: "page"
title: "Hivemind Podcast"
permalink: 'hive-mind'
technologies:
- Wordpress 
- Bootstrap
logo: "/assets/images/hvmd.png"
image: "/assets/images/hvmd_img.png"
site_url: "http://hvmd.eu"
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">HiveMind is an artistic musical collective, which aims to connect audiophiles. This project has the mission to discover up-and-coming talents and spread their unique vibe to the community. You can expect a steady flow of diverse mixes, live broadcasts and events.
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		{% include project_image.md %}
	</div>
</div>