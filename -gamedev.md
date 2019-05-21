---
title: Game Development
layout: landing
description: 'Lorem ipsum dolor sit amet nullam consequa<br />sed veroeros. tempus adipiscing nulla.'
image: assets/images/gamedev.png
nav-menu: true
permalink: /gamedev
---

<section id="one" class="tiles">
  {% for post in site.gamedev limit:site.tiles-count %}
  <article>
    <span class="image">
      <img src="{{ post.image }}" alt="" />
    </span>
    <header class="major">
      <h3><a href="{{ post.url  | relative_url }}" class="link">{{ post.title }}</a></h3>
      <p>{{ post.description }}</p>
    </header>
  </article>
  {% endfor %}
</section>
