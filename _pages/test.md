---
layout: page
permalink: /schedule/
title: Schedule
description: Course schedule by week. Click for weekly details.
nav: true
---

<ul class="post-list">
{% for post in paginator.posts %}
  <li>
    <h3><a class="post-title" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
    <!-- <p class="post-meta">{{ post.date | date: '%B %-d, %Y' }}</p> -->
    <p>{{ post.description }}</p>
  </li>
{% endfor %}
</ul>

### Weekly overview

$$p=2 \cdot b$$

Week 0: https://github.com/Jam3/math-as-code