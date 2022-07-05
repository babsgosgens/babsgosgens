---
category: projecten
tags: interieurontwerp
layout: single-portfolio-simple
title: Home Sweet Home
date:   2022-05-10 13:09:46 +
cover: /assets/images/posts/projects/een-kijkje-in-ons-huis/cover@450w.jpg
image_namespace: een-kijkje-in-ons-huis/gallery
gallery_display: slider
---
{% assign slider_images = site.static_files | where_exp: "item", "item.path contains page.image_namespace" %}
