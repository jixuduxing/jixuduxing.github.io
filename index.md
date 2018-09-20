---
layout: default
---


<div class="posts">
  {% for post in site.posts %}
    <article class="post">
    <small>{{ post.date | date: "%-d %b, %Y" }}</small>
    <h1></h1>
    <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
    </article>
    <p/>
  {% endfor %}
</div>
