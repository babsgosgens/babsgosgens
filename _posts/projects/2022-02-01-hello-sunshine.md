---
category: projecten
tags: interieurontwerp
layout: single-portfolio-simple
title: Hello Sunshine
date:   2022-02-01 13:00:00 +
cover: /assets/images/posts/projects/lichtval-studie/cover@450w.jpg
image_namespace: lichtval-studie/gallery
---
{% assign slider_images = site.static_files | where_exp: "item", "item.path contains page.image_namespace" %}
