---
layout: default
---

# Today's Specials

## Latest Blog Post

{% for post in site.posts limit:1 %}
<a href="{{ post.url }}">{{ post.title }}</a>

<p>{{post.date | date: "%d %B %Y"}}</p>

{{ post.content }} 

{% endfor %}

## Current Project
I'm currently working on [Pets and Fedoras](pets-and-fedoras), a hack of [Lasers and Feelings](https://johnharper.itch.io/lasers-feelings).

You are spies with cover identities of regular house pets.  Your mission, as always, is to find out what your evil scientist nemesis is up to and put a stop to it!  
This work is directly inspired by the cartoon Phineas and Ferb.