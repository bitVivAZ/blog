---
title: Game Development
layout: landing
description: 'Portofolio of games developed by me'
image: assets/images/gamedev.png
nav-menu: true
permalink: /gamedev
---

<section id="one" class="tiles">
{% assign sortedPosts = site.gamedev | sort: 'date' | reverse %}
  {% for post in sortedPosts %}
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
