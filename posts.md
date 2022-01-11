---
layout: default
title: Posts
permalink: /posts/
---

Here you will find a series of posts about ethical assurance:

<div class="row row-cols-1 row-cols-sm-2 row-cols-xl-3 g-4">
  {% for post in site.posts %}
  <div class="col">
    <div class="card">
      <a href="{{ post.url }}">
        <img src="{{ post.image_path }}" class="card-img-top">
      </a>
      <div class="card-body">
        <a href="{{ post.url }}">
          <h5 class="card-title">{{ post.title }}</h5>
        </a>
        <p class="card-text">{{ post.excerpt }}</p>
        <p class="card-text">
        <small class="text-muted">Tags:
        {% for item in post.tags %}
          #{{ item }}
        {% endfor %}
        </small>
      </p>
      </div>
    </div>
  </div>
  {% endfor %}
</div>
