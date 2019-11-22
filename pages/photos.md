---
layout: page
title: Gallery
permalink: /photos
section: photos
---

<ul class="photo-gallery">
	{% assign sorted_photos = site.photo_gallery %}
	{% for image in sorted_photos %}
	<li>
		<img src="{{ image.image_path }}" alt="{{ image.image_title }}">
	</li>
	{% endfor %}
</ul>
