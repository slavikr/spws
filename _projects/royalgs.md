---
layout: "page"
title: "Royal GS"
permalink: "royal-gs"
technologies:
 - Wordpress
 - Foundation
logo: "/assets/images/rgs.png"
image: "/assets/images/royalgs_img.png"
site_url: "http://royalgs.nl"
---

<div class="row">
	<div class="col-md-4">	
		<h1 class="project_title">{{ page.title }}</h1>
		<span class="tech">{{ page.technologies | join: " - " }}</span>
		<p class="info">This young company was founded in July 2015.
			Decisive, professional and result-oriented are some of the characteristics of this company.
			When you leave the cleaning of your roller shutters or dormer windows and gutters from your house or company to Royal GS, you can be sure that you get motivated people at home, who will ensure that you have clean rolling shutters (and dormer windows and roof gutters) ) without having to worry about it!
			You can also leave it to us to clean your terrace, boat, caravan, furniture or polish your car.
		</p>
		<a class="site_url" href="{{ page.site_url }}" target="_blank">{{ page.title }}</a>
	</div>
	<div class="col-md-8">
		<img class="img-fluid" src="{{ page.image | relative_url }}" alt="{{ page.title }}">
	</div>
</div>
