---
layout: page
permalink: /bookshelf/index.html
title: My Online Bookshelf
description: This is a list of books I have read and recommend. If you need inspiration on what to read next, I hope this can be your guide.
tags: [books, bruno belcastro, list, recommendations, ebooks, amazon, kindle, paperback, hardcover]
---

<ul>
{% for books in site.data.books %}
  <li>{{ books.title }}</li>
  <li>{{ books.author }}</li>
</ul>  
<p>{{ books.description }}</p>
<a href=""></a>
{% endfor %}
