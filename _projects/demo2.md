---
layout: "page"
title: "KM0 Detailing Studio"
permalink: "demo2"
technologies:
 - Wordpress
 - Elementor
logo: "/assets/images/elementor.webp"
image: "/assets/images/detailing-studio.webp"
site_url: "https://site2.wpxslavi.xyz/"
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">
			A WordPress and Elementor clone of km0detailingstudio.
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		{% include project_image.md %}
	</div>
</div>