---
order: 1
layout: page
permalink: /schedule/
title: Schedule
description: Course schedule by week. Click for weekly details.
nav: true
week: true
---

### Session structure

How are we going to spend the 3-hour every week? The structure of weekly session ties to our [course purposes](/#purposes).

---
<div class="post">

    {% if page.week %}
      {% include week.html %}
    {% endif %}

</div>
