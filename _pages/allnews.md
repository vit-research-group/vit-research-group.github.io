---
title: "News"
layout: textlay
excerpt: "VIT Group at CMS College"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }} <br><em><p>
{{ article.headline | markdownify}}</em></p>
{% endfor %}
