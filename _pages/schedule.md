---
order: 1
layout: page
permalink: /schedule/
title: Schedule
description: Course schedule by week. Click for weekly details.
nav: true
week: true
---

A typical weekly session will have three components:

1. _Lecture on reading materials and statistics._ During the first hour, I will typically give a lecture to cover the major points of the week. I will also answer any of your questions.

2. _In class practice on empirical methods_. We will solve problems and practice empirical methods in class.

3. _In class preparation and presentation._ The last hour helps you prepare your replication project.

<div class="post">

    {% if page.week %}
      {% include week.html %}
    {% endif %}

</div>
