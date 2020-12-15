---
layout: page
title: Data Science
permalink: /blog/tags/Data_Science
---

<h5> Posts by Tag : {{ page.title }} </h5>

<div class="card">
{% for post in site.tags.jekyll %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>
