---
layout: "page"
title: "Fretboard Journal"
permalink: "fretboard-journal"
technologies:
 - Wordpress
 - Elementor
logo: "/assets/images/elementor.webp"
image: "/assets/images/fretboard-journal.webp"
site_url: "https://site3.wpxslavi.xyz/"
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">Guitar based blog built with Elementor.
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		{% include project_image.md %}
	</div>
</div>
