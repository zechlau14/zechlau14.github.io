---
layout: default
---

# Today's Specials

## Latest Blog Post

{% for post in site.posts limit:1 %}

<h3><a href="{{ post.url }}">{{ post.title }}</a> | {{post.date | date: "%d %B %Y"}}</h3>

<article> {{ post.content }} </article>

{% endfor %}

## Latest Book Review

Back in January, I read [Dodger](/Book-Review/Dodger) by Terry Prachet.

## Latest Recipe Uploaded

I've updated the yellow cake recipe that I've been using with a new [Gluten-Free version](/recipes/Yellow-Cake). When I made it recently, I frosted it with this [Chocolate Buttercream](/recipes/Chocolate-Buttercream), which I might iterate further in the future.

## Current RPG Project
I'm not currently working on any RPG work.
