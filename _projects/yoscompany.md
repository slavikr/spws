---
layout: "page"
title: "Yos Company"
permalink: "yos-company"
technologies:
 - Wordpress
 - Foundation
logo: "/assets/images/yosc.png"
image: "/assets/images/yos_img.png"
site_url: "http://yoscompany.nl"
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">Yoscopmany is a young dynamic company that wants to be your partner. Being your partner means good consultation about the assignment in advance so that your professional requirements are fully realized.
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		{% include project_image.md %}
	</div>
</div>