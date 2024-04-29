---
layout: default
---

# Today's Specials

## Latest Blog Post

{% for post in site.posts limit:1 %}

<h3><a href="{{ post.url }}">{{ post.title }}</a> | {{post.date | date: "%d %B %Y"}}</h3>

<article> {{ post.content }} </article>

{% endfor %}

## Current Project
I'm currently working on [Pets and Fedoras](projects/pets-and-fedoras-slides).

You are fedora-wearing special agents of the NNSA (Never Named Spy Agency) with cover identities as ordinary house pets belonging to a pair of genius children, Linneaus and Fern. Your mission, as always, is to find out what your evil scientist nemesis, Dr. Goofenheim, is up to and put a stop to it!

This work is a dice-less, GM-less, story-game directly inspired by the cartoon Phineas and Ferb.

## Latest Completed Project

<iframe frameborder="0" src="https://itch.io/embed/2676441" width="552" height="167"><a href="https://mrzech.itch.io/hot-mutant-vigilantes">Hot Mutant Vigilantes by Mr Zech</a></iframe>

You are a [HOT MUTANT VIGILANTE](/projects/hot-mutant-vigilantes). More specifically, you are a student at a school for gifted youngsters where the extra-curricular activities involve dressing up in spandex and defending the world. The school has zero legal authority to do this, hence the label ‘vigilante’. The government and the humans hate you. This work is a hack of [Grant Howitt’s Sexy Battle Wizards](https://gshowitt.itch.io/sexy-battle-wizards) and is directly inspired by the X-men.
