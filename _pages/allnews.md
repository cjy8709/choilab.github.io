---
title: "News"
layout: textlay
excerpt: "Choi Lab at the University of Kansas"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
{{ article.headline}}</p>
{% endfor %}
