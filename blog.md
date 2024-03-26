---
layout: default
title: Blog
permalink: /blog
---

# Our Latest 

{% assign post = site.posts.first %}

## {{ post.title }}   
    
{{post.exert}}

[Read More]({{ post.url }})