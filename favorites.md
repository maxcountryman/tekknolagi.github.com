---
layout: post
title: Favorite Things
---

Here are some of my favorite personal websites:

<ul>
  {% for website in site.data.sites %}
  <li><a href="http://{{ website.url }}/">{{ website.url }}</a></li>
  {% endfor %}
</ul>

Here are some of my favorite books:

<ul>
  {% for book in site.data.books %}
  <li><i>{{ book.title }}</i> by {{ book.author }}</li>
  {% endfor %}
</ul>

Here are some of my favorite films:

<ul>
  {% for film in site.data.films %}
  <li>{{ film.title }}</li>
  {% endfor %}
</ul>