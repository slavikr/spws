---
layout: "page"
title: "Koch‑Chemie Elementor Page"
permalink: "demo1"
technologies:
 - Wordpress
 - Elementor
logo: "/assets/images/elementor.webp"
image: "/assets/images/kochchemie.webp"
site_url: "https://site1.wpxslavi.xyz/"
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">
			Demo page of koch-chemie.com created with WordPress and Elementor.
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		{% include project_image.md %}
	</div>
</div>