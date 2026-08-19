---
layout: "page"
title: "Center for Experiential Learning"
permalink: "celbg"
technologies:
 - Wordpress
 - Bricks
logo: "/assets/images/bricks.webp"
image: "/assets/images/cel.webp"
site_url: "https://celbg.org/"
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">
			Center for Experiential Learning – innovative educational methods for sustainable development. Discover how learning through experience is changing the world!
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		{% include project_image.md %}
	</div>
</div>