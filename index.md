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
<iframe frameborder="0" src="https://itch.io/embed/2636261" width="552" height="167"><a href="https://mrzech.itch.io/hot-dog-borg">Hot Dog Borg by Mr Zech</a></iframe>

Hot Dog Borg is a silly hack of Mork Borg, in which you play as a Hot Dog Karate-ka, and my submission for the [Noun Borg Get Rich Quick Jam](https://itch.io/jam/noun-borg). 
