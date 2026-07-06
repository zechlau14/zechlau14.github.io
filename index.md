---
layout: default
---

# Welcome!

I don't know how you wandered in, but I'm glad you are here.

While you're here, you can find [Mr Zech](/about)'s [recipebook](/recipes), [game portfolio](/games) and [blog](/blog), which will hopefully be mostly about tabletop role-playing games.

## Selected Games

<iframe frameborder="0" src="https://itch.io/embed/2968084" width="208" height="167"><a href="https://mrzech.itch.io/5-nights-of-overtime">5 Nights of Overtime by Mr Zech</a></iframe>

<iframe frameborder="0" src="https://itch.io/embed/2621161" width="208" height="167"><a href="https://mrzech.itch.io/i-love-you-but-we-must-fight">I love you but we must fight by Mr Zech</a></iframe>

<iframe frameborder="0" src="https://itch.io/embed/2676441" width="208" height="167"><a href="https://mrzech.itch.io/hot-mutant-vigilantes">Hot Mutant Vigilantes by Mr Zech</a></iframe>

## Selected Recipes
1. [Pizza](/recipes/Pizza-Base/)
2. [Japanese Hamburger](/recipes/Japanese-Hamburger/)
3. [Baked Donuts](recipes/Baked-Donuts/)

## My Best Writing
I'll put an article here, when I have one that deserves it!

## Latest Blog Post

{% for post in site.posts limit:1 %}

<h3><a href="{{ post.url }}">{{ post.title }}</a> | {{post.date | date: "%d %B %Y"}}</h3>

<article> {{ post.content }} </article>

{% endfor %}
