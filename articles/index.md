---
layout: page
title: Work
excerpt: "Projects"
image:
  feature: katahdinbar.jpg
search_omit: true
---

<ul class="post-list">
{% for post in site.categories.articles %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

## Work projects 

<center>
<a href="https://github.com/dflynn-volpe" class="btn">Volpe Center GitHub Account</a>
</center>

## Personal project 

<center>
<a href="https://github.com/flynn-d" class="btn">Personal GitHub Account</a>
</center>

## Publications

<center>
<a href="https://scholar.google.com/citations?user=otWCBH8AAAAJ&hl=en" class="btn">Google Scholar Profile</a>
</center>
