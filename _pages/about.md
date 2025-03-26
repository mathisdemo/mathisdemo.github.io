---
layout: about
title: About
permalink: /about/

profile:
  align: right
  image: flo_pic.png
  image_circular: false

news: false
selected_papers: false
social: true
---
{% assign about = site.abouts | first %}
{{ about.content }}
