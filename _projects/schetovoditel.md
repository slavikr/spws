---
layout: "page"
title: "Schetovoditelbg"
permalink: "schetovoditelbg"
technologies:
 - Wordpress
 - Gutenberg
 - Spectra
logo: "/assets/images/elementor.webp"
image: "/assets/images/schetovoditelbg.webp"
site_url: "https://schetovoditelbg.net/"
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">schetovoditelbg.net is the official site of Rositsa Daskalova, an economist-accountant offering professional accounting, payroll administration, and business consulting services in Bulgaria.
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		{% include project_image.md %}
	</div>
</div>
