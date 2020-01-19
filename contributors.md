---
layout: pages
title: Contributors
permalink: /contributors/
---

## Authors

ADD HERE THE LIST

{% for author in site.data.authors %}
    <li><a href="{{ author.url }}">{{ author.name }}</a> </li>
{% endfor %}
