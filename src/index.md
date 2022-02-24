---
title: My first page
layout: base.njk
---

## Blog Posts

<!-- {% for post in collections.posts %}
{{ post.data.title }}
{% endfor %} -->

{% include "postlist.njk" %}

{% for fact in facts | randomItem %} {% endfor %}

## Cat of the Day

<img src="{{ catpic }}" />