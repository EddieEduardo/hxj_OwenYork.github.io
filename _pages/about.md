---
permalink: /
title: "BETTER AI, BETTER LIFE"
layout: single
author_profile: true
redirect_from:
  - /about/
  - /about.html
header:
  overlay_image: /images/banner.png
  overlay_filter: 0.35
  overlay_color: "#000"
  text_color: "#fff"
  show_overlay_excerpt: false
---


## About Me

Hi! I’m a freshly graduated PhD from Harbin Institute of Technology (Control Science & Engineering). My interests lie in computer vision and multimodal foundation models. I enjoy exploring how to bring large-scale pretraining and representation learning into real-world settings—making models not only powerful, but also efficient and practical. I also keep an eye on model efficiency, including lightweight architectures, more efficient training/inference, and the little engineering “gotchas” that come up during deployment.

I prefer turning ideas into systems that actually work, and then validating them in real applications. I’ve also worked on topics like image segmentation and multi-object tracking. During my PhD, my main focus was visual defect detection in industrial scenarios—making models more accurate, stable, and usable on real production lines with complex textures, changing lighting, and frequently shifting operating conditions. Along the way, I dealt with challenges around distribution shifts, limited annotations, and reliability requirements. Feel free to reach out and chat!

## Research Interests

Foundation models (multi-modality foundation models), open-set recognition, computer vision (detection, segmentation, multiple object tracking), and deploying models into real-world applications.

## Publications

{% include base_path %}
{% assign pubs = site.publications | sort: "date" | reverse %}
{% for post in pubs %}
  {% include archive-single-publication-card.html %}
{% endfor %}

[View all publications]({{ base_path }}/publications/)
