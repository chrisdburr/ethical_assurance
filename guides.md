---
layout: default
title: Guides
permalink: /guides/
---

Here you will find a series of guides to help you get started with ethical assurance.

  {% for guide in site.guides %}
  <div class="col" style="margin-bottom: 10px;">
    <div class="card">
      <a href="{{ guide.url }}">
        <img src="{{ guide.image_path }}" class="card-img-top">
      </a>
      <div class="card-body">
        <a href="{{ guide.url }}">
          <h5 class="card-title">{{ guide.title }}</h5>
        </a>
        <p class="card-text">{{ guide.excerpt }}</p>
      </div>
    </div>
  </div>
  {% endfor %}
