---
layout: page
title: Places
background: /assets/images/places.jpg
---

Here are the great places along the Great Ouse with practical details of how to get there and where to stay.

{%- for item in site.data.places %}

<div class="row g-0">
    <div class="col-md-4">
      <img src="{{ item.last.image }}" class="card-img" style="max-height:300px" alt="{{ item.last.title }}">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title"><a href="{{ item.last.pagelink }}">{{ item.last.title }}</a></h5>
        <p class="card-text"></p><p>{{ item.last.description }}</p>
      </div>
    </div>
  </div>

{% endfor -%}
