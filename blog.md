---
layout: page
permalink: /blog/index.html
title: Blog
---

Thoughts on AI, intelligence, and whatever else I am working through. A list I expect to keep growing.

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})

*{{ post.date | date: "%B %d, %Y" }} &nbsp;·&nbsp; {{ post.content | number_of_words }} words &nbsp;·&nbsp; {{ post.content | number_of_words | divided_by: 200.0 | ceil }} min read*

{% if post.description %}{{ post.description }}{% else %}{{ post.content | strip_html | strip_newlines | truncate: 160 }}{% endif %}

{% endfor %}
