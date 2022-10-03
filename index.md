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

| ❗❗❗ <span style='color:Blue'><b>Important Updates on HW1!</b></span> <br> We made some minor changes on HW1 write-up, more information could be found [here](https://campuswire.com/c/GE36D51A4/feed/43). The updated version is aviliable on the course website around 8:15 pm Oct 2nd. If you download the write-up prior to this time, please check out the Campuswire post carefully.
| ❗ <span style='color:Blue'><b>Important note on the discussion sessions:</b></span> <br> The first discussion session will be on Monday, October 3rd 2022.

{{ site.staffersnobio }}

[Lecture Recordings](https://podcast.ucsd.edu/){: .btn .btn-blue } 

<!-- [Assignment Solutions](https://campuswire.com/c/GF82D3B2E/feed/73){: .btn .btn-purple } -->



{% for module in site.modules %}
{{ module }}
{% endfor %}
