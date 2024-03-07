---
title: "VIT Group - Publications"
layout: gridlay
excerpt: "VIT Group -- Publications."
sitemap: false
permalink: /publications/
---


# Publications


(For complete list of our publications see [below](#full-list-of-publications) or go to [**Google Scholar**](https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=Q9QgjcEAAAAJ&sortby=pubdate), [**ORCHID**](https://orcid.org/0000-0003-3928-2319))


{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
