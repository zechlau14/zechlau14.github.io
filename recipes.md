---
layout: page

title: "Recipes"

---

{% for post in site.recipes %}

<h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> | {{post.date | date: "%d %B %Y"}} </h2>

  <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>

</article>

{% endfor %}


