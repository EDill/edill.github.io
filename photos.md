---
layout: default
title: Pictures
permalink: /photos/
---

I take photographs of things, here are some of them. 

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h2></h2></h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
