---
category: projecten
tags: meubelontwerp
layout: single-portfolio-simple
title: Meubelschetsen
date:   2022-05-09 13:09:46 +
cover: /assets/images/posts/projects/meubels/cover_tall.jpg
image_namespace: meubels/gallery
gallery_display: slider
---
{% assign slider_images = site.static_files | where_exp: "item", "item.path contains page.image_namespace" %}
