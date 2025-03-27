---
layout: about
title: Apropos
permalink: /about
description: Here's a list of projects I've completed or participated in.
nav: true
nav_order: 3

---
{% assign about = site.abouts | first %} {{ about.content }}