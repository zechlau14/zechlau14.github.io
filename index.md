---
layout: default
---

# Today's Specials

## Latest Blog Post

{% for post in site.posts limit:1 %}

<h3><a href="{{ post.url }}">{{ post.title }}</a> | {{post.date | date: "%d %B %Y"}}</h3>

<article> {{ post.content }} </article>

{% endfor %}

## Latest Recipe Uploaded

I made these gluten-free [Almond Chocolate Chip Cookies](recipes/Gluten-Free-Almond-Chocolate-Chip-Cookies) for my wife recently. It was my first time baking with almond flour, and I liked it enough to add it to the recipe book.

## Current RPG Project
I'm not currently working on any RPG work.
