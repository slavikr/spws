---
layout: "page"
title: "Sofia Electric Enduro"
permalink: "see"
technologies:
 - Astro
logo: "/assets/images/see_logo.webp"
image: "/assets/images/see.webp"
site_url: "https://see.momchevmomchil.workers.dev/"
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">Unrivaled offroad trips in Sofia. Experience the Stara mountains with high-power ATVs, electric Sur-Rons, and modified 4x4 Jeeps.
			This is a version 2 of that site and it is currently in development.
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		{% include project_image.md %}
	</div>
</div>
