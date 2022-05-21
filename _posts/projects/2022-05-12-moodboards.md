---
category: projecten
tags: interieurontwerp
layout: single-portfolio-simple
title: Moodboards
date:   2022-05-12 13:09:46 +
cover: /assets/images/posts/projects/moodboards/cover@450.jpg
image_namespace: moodboards/gallery
gallery_display: carousel
---
{% assign slider_images = site.static_files | where_exp: "item", "item.path contains page.image_namespace" %}
