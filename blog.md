---
layout: default
title: Blog
permalink: /blog
---

# Our Latest 

<ul>
  {% for post in site.posts %}
    <li>
      [ {{ post.title }} ](  {{ post.url }} )  
      {{ post.excerpt }} 
      [Read More]({{ site.baseurl }}{{ post.url }})
    </li>
  {% endfor %}
</ul>