---
title: Website Development
layout: landing
description: 'Portofolio of websites developed by me'
image: assets/webdev/severegamingza/images/severe.png
nav-menu: true
date: 2019-05-01 14:40:45
permalink: /webdev
---

<section id="one" class="tiles">  
  {% assign sortedPosts = site.webdev | sort: 'date' | reverse %}
  {% for post in sortedPosts %}
  <article>
    <span class="image">
      <img src="{{ post.image }}" alt="" />
    </span>
    <header class="major">
      <h3><a href="{{ post.url  | relative_url }}" class="link">{{ post.title }}</a></h3>
      <p>{{ post.description }}</p>
      <p>{{ post.techstack }}</p>
    </header>
  </article>
  {% endfor %}
</section>