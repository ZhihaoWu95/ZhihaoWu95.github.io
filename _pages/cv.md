---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<h2>Education</h2>

* Ph.D in Electrical Information (Control Engineering), Zhejiang University, 2024 (expected)
* M.S. in Control Science and Engineering, Zhejiang Sci-Tech University, 2020
* B.S. in Electrical Engineering and Automation, Zhejiang Sci-Tech University, 2017

<h2>Publications</h2>

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<h2>Talks</h2>

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
  
