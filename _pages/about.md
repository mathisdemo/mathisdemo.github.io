---
layout: about
title: About
permalink: /about
nav: true
nav_order: 3
profile:
  align: right
  image: tri_pic.png
  image_circular: false
news: false
selected_papers: false
social: true
---
{% assign about = site.abouts | first %} {{ about.content }}
