---
layout: page
title: Arhivă
permalink: /archives/
---

# Arhiva Postărilor

{% assign posts_by_year = site.posts | group_by_exp: "post", "post.date | date: '%Y'" | sort: "name" | reverse %}

{% for year in posts_by_year %}
## {{ year.name }}

{% for post in year.items %}
- {{ post.date | date: "%d %B" }} — [{{ post.title }}]({{ post.url | relative_url }}){% if post.categories %} • {{ post.categories | join: ", " }}{% endif %}
{% endfor %}

{% endfor %}