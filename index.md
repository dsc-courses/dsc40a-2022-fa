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

| ❗❗❗ <span style='color:Blue'><b>Important Updates on HW1!</b></span> <br> We made some minor changes on HW1 write-up. The updated version 2 is aviliable on the course website around 2 pm Oct 4th. If you download the write-up prior to this time, please check out the Campuswire post carefully.<br>


|📅<span style='color:Blue'><b>Midterm Schedule:</b></span> <br> The Midterm is scheduled for **28th October 2022**. The midterm will be **in-person for a duration of 1 hour**. It will take place during lecture hours of each batch at the same location as that of the lectures. **Students must attend the session they are enrolled in**.

{{ site.staffersnobio }}

[Lecture Recordings](https://podcast.ucsd.edu/){: .btn .btn-blue } 

<!-- [Assignment Solutions](https://campuswire.com/c/GF82D3B2E/feed/73){: .btn .btn-purple } -->



{% for module in site.modules %}
{{ module }}
{% endfor %}
