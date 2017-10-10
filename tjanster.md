---
layout: page
title: TJÄNSTER
description: 
image: assets/images/service.jpg
nav-menu: true
published: true
permalink: tjanster
---

<section id="one" class="tiles">
	{% for page in site.pages %}
	{% if page.service %}
        <article>
                <span class="image">
                        <img src="{{ page.image }}" alt="" />
                </span>
                <header class="major">
                        <h3><a href="{{ page.url | relative_url  }}" class="link">{{ page.title }}</a></h3>
                        <p>{{ page.description }}</p>
                </header>
        </article>
	{% endif %}
	{% endfor %}
</section>
