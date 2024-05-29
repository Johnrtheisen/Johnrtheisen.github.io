---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<embed src="http://johnrtheisen.github.io//files//Theisen_CV.pdf" width="500" height="600" 
 type="application/pdf">

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>