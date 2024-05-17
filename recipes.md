---
layout: page

title: "Recipes"

---

{% for post in site.recipes %}

<h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> </h2>

  {% endfor %}


