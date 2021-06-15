---
layout: page
permalink: /schedule/
title: schedule
description: Course schedule by week. Click for weekly details.
nav: true
---

### Session structure

How are we going to spend the 3-hour every week? The structure of weekly session ties to our [course purposes](/#purposes).

<div class="post">

    {% if page.news %}
      {% include news.html %}
    {% endif %}

</div>

### Week 1: Course introduction and replication
- Week 2: Research design of quantitative study 1/2

Before class:

  - Ruane, J. M. (2016). Measure by Measure: Developing Measures—Making the Abstract Concrete. In Introducing Social Research Methods: Essentials for Getting the Edge (pp. 93–116). Chichester, West Sussex, UK ; Hoboken, NJ: John Wiley & Sons Inc.
  - Ruane, J. M. (2016). All That Glitters Is Not Gold: Assessing the Validity and Reliability of Measures. In Introducing Social Research Methods: Essentials for Getting the Edge (pp. 117–138). Chichester, West Sussex, UK ; Hoboken, NJ: John Wiley & Sons Inc.

- Week 3: Research design of quantitative study 2/2

Before class:

  - Gerring, J. (1999). What Makes a Concept Good? A Criterial Framework for Understanding Concept Formation in the Social Sciences. Polity, 31(3), 357–393. doi:10.2307/3235246.
  - Shoemaker, P. J., Tankard, J. W., & Lasorsa, D. L. (2003). Theoretical Concepts: The Building Blocks of Theory. In How to Build Social Science Theories (pp. 15–36). SAGE Publications.
  - Shoemaker, P. J., Tankard, J. W., & Lasorsa, D. L. (2003). Theoretical Statements Relating Two Variables. In How to Build Social Science Theories. SAGE Publications.
  - Shoemaker, P. J., Tankard, J. W., & Lasorsa, D. L. (2003). Theoretical Statements Relating Three Variables. In How to Build Social Science Theories. SAGE Publications.


- Week 4: Data structure and descriptive statistics 1/2

Before class

  - Wickham, H. (2014). Tidy data. The Journal of Statistical Software, 59(10). http://www.jstatsoft.org/v59/i10/
  - Tukey, J. W. (1977). Exploratory Data Analysis. Addison-Wesley Publishing Company.


- Week 5: Descriptive statistics 2/2

Key concepts:

Before class:
  
  - MBB

- Week 7: Samples and probability distributions
  - Probability and Bayes' Rule.
  - Distributions: Normal, Poisson, and binominal

- Week 7: Inference 1/2

Key concepts:
  - Standard errors
  - Law of large numbers
  - Central Limit Theorem
  - Bootstrapping and CLT
  - Confidence Intervals
  - Student's t-distributions

- Week 8: Inference 2/2



- Week 9: Regression 1/2
- Week 10: Regression 2/2
- Week 11: Research design of mixed methods study and data collection
- Week 12: Case selection and causality in quantitative studies
- week 13: 
- Week 14: 
- Week 15:


## Learning resources

- R/Python/Excel track: [DataCamp](#)
- Stata track: http://geocenter.github.io/StataTraining/
- Other sources: Feel free to help your self!

### Weekly overview

$$p=2 \cdot b$$

Week 0: https://github.com/Jam3/math-as-code

<div class="post">
  <ul class="post-list">
    {% for post in paginator.posts %}
      <li>
        <h3><a class="post-title" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
        <!-- <p class="post-meta">{{ post.date | date: '%B %-d, %Y' }}</p> -->
        <p>{{ post.description }}</p>
      </li>
    {% endfor %}
  </ul>
</div>