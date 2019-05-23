---
title: Software Development
layout: landing
description: 'Portofolio of software developed by me'
image: assets/images/softwaredev.jpeg
nav-menu: true
date: 2019-05-20 14:40:45
permalink: /softwaredev
---

<section id="one" class="tiles">
  {% for post in site.softwaredev limit:site.tiles-count %}
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