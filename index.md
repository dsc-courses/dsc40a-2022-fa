---
layout: home
title: Home
nav_exclude: false
nav_order: 1
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }} 🥑
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

| 🎉 <span style='color:Blue'><b>Welcome to the Fall 2022 offering of DSC 40A!</b></span> <br> This site is still under construction, information are subject to change.

{{ site.staffersnobio }}

<!-- [Lecture Recordings](https://podcast.ucsd.edu/watch/fa21/dsc40a_a00){: .btn .btn-blue } [Assignment Solutions](https://campuswire.com/c/GF82D3B2E/feed/73){: .btn .btn-purple }-->



{% for module in site.modules %}
{{ module }}
{% endfor %}
