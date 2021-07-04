---
order: 1
layout: page
permalink: /schedule/
title: Schedule
description: Course schedule by week. Click for weekly details.
nav: true
week: true
---

# Session structure

How are we going to spend the 3-hour every week? The structure of weekly session ties to our [course purposes](/#purposes).

1. Lecture on reading materials and statistics

During the first hour of each week, I will typically give a lecture on the major points of the week. I will also answer any of your questions.

2. In class practice on empirical methods

We will solve problems in class.

3. In class preparation and presentation

The last hour helps you prepare your individual and group replication projects.


---
<div class="post">

    {% if page.week %}
      {% include week.html %}
    {% endif %}

</div>
