---
title: "Blog"
permalink: /blog/
layout: archive
author_profile: true
---

Technical notes, tutorials, and thoughts on aerospace engineering, machine learning, Python, and clean aviation. Written for engineers and data scientists.

{% assign posts = site.posts %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}
