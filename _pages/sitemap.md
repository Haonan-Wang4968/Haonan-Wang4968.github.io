---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: false
---

<ul>
  {% for link in site.data.navigation.main %}
    <li><a href="{{ link.url | relative_url }}">{{ link.title | escape }}</a></li>
  {% endfor %}
</ul>
