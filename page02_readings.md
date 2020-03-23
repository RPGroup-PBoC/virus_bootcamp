---
layout: page
title: Readings
img: reading.png 
permalink: code
caption: "DNA Sequence Chromatogram"
sidebar: true
---

---

{% for day in site.data.readings %}
## {{day[0]}}
{% for pub in day[1] %}
* [**{{pub.title}}**]({{site.url}}/{{site.baseurl}}/assets/pdfs/{{pub.link}}) by {{pub.authors}}({{pub.year}}) *{{pub.journal}}* {{pub.volume}}**{{pub.issue}}**. {{pub.year}}. {%if pub.description %}{{pub.description}}{%endif%}
{%endfor%}
{%endfor%}

<center>
<h1> Useful links</h1>
</center>

---

{%for link in site.data.links%}
* [**{{link.title}}**]({{link.address}}) {%if link.description %}{{link.description}}{%endif%}
{%endfor%}

