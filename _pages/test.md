---
layout: page
permalink: /schedule/
title: schedule
description: Course schedule by week. Click for weekly details.
nav: true
pagination:
  enabled: true
  collection: posts
  permalink: /page/:num/
  per_page: 20
  sort_field: date
  sort_reverse: true
  trail:
    before: 1 # The number of links before the current page
    after: 3  # The number of links after the current page
---

### Session structure

How are we going to spend the 3-hour every week? The structure of weekly session ties to our [course purposes](/#purposes).

### Weekly overview

$$p=2 \cdot b$$

Week 0: https://github.com/Jam3/math-as-code

---

<div class="post">

  <div class="header-bar">
<!--     <h1>{{ site.blog_name }}</h1>
    <h2>{{ site.blog_description }}</h2> -->
    <h2>Weekly Schedule</h2>
    click for details
  </div>

  <ul class="post-list">
    {% for post in paginator.posts %}
      <li>
        <h3><a class="post-title" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
        <!-- <p class="post-meta">{{ post.date | date: '%B %-d, %Y' }}</p> -->
        <p>{{ post.description }}</p>
      </li>
    {% endfor %}
  </ul>

  <!-- {% include pagination.html %} -->

</div>