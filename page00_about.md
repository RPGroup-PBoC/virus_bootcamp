---
layout: page
title: About
description: 
img: corona_virus_goodsell.jpg 
caption: "Courtesy of David S. Goodsell"
permalink: index.html
sidebar: true
---

# {{site.data.about.title}}
{{site.data.about.authors}}

{% for entry in site.data.about %}

{% if entry[0] != 'title' %}
{% if entry[0] != 'authors' %}
## {{entry[0]}}
{{entry[1]}}
{% endif %}
{% endif %}
{% endfor %}


| **Date** | **Topic** | **Link to Recorded Lecture** |
|:--: | :--: | :--: |
| Mon. 3/23/2020 | What are viruses? A brief history and biology. |  |
| Tue. 3/24/2020 | Diversity in viral genetic material and life cycles. | [Lecture 2 (`.mp4`)](http://rpdata.caltech.edu/lecture_slides/pbov_2020/pbov_2020_lecture_2.mp4) |
| Wed. 3/25/2020 | Physical mechanisms, assembly pathways, and energetic costs. | [Lecture 3 (`.mp4`)](http://rpdata.caltech.edu/lecture_slides/pbov_2020/pbov_2020_lecture_3.mp4) |
| Thu. 3/26/2020 | Global viral dynamics, SIR, and other models. | | 