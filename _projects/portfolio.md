---
layout: "page"
title: "Portfolio"
permalink: 'portfolio'
technologies:
 - Jekyll
 - Bootstrap
 - Sass
logo: "/assets/images/s1.png"
image: "/assets/images/s1.png"
site_url: ""
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">Personal webpage and blog, where i post my web projects and a couple of my thoughts.
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		<img class="img-fluid" src="{{ page.image | relative_url }}" alt="{{ page.title }}">
	</div>
</div>