---
layout: page
title: Archive
---

### Seminars ###
- Department Colloquium
    - [Spring 2015]({{ site.baseurl }}/colloquiumSpring2015)
- Algebra, Combinatorics, Geometry, and Topology (ACGT) Seminar
    - [Spring 2015]({{ site.baseurl }}/acgtSpring2015)
- Applied Math Seminar (AMS)
    - [Spring 2015]({{ site.baseurl }}/amsSpring2015)
- Friday Afternoon Mathematics Undergraduate Seminar (FAMUS)
    - [Spring 2015]({{ site.baseurl }}/famusSpring2015)
- Teaching Showcase
    - [Fall 2014]({{ site.baseurl }}/teachingFall2014)
    - [Spring 2015]({{ site.baseurl }}/teachingSpring2015)

### Weekly Posts ###
{% for post in site.posts %}
- {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ site.baseurl }}/{{ post.url }})
{% endfor %}
