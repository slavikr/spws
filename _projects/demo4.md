---
layout: "page"
title: "Inspiration for travel"
permalink: "travel-blog"
technologies:
 - Wordpress
 - Elementor
logo: "/assets/images/elementor.webp"
image: "/assets/images/travel.webp"
site_url: "https://site4.wpxslavi.xyz/"
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">Travel blog page built with Elementor.
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		{% include project_image.md %}
	</div>
</div>
