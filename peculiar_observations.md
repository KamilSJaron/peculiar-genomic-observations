---
Title: Peculiar Observations
layout: peculiar_observations
---

### List of observations

{% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> </li>
    {{ post.url }}
{% endfor %}