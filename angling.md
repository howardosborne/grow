---
layout: map
title: Angling
background: /assets/images/angling.jpg
loadFunction: loadAngling()
---
It's hard to think of a section of our society that has done more to draw attention to the problems with our rivers.

If you want to have a go with a rod, then why not get in touch with one of these angling groups? 

<div id="map" class="col-md-12" style="height: 600px;"></div>

## Fishing Clubs

{%- for item in site.data.angling %}

<div class="row g-0">
    <div class="col-md-4">
      <img src="{{ item.image }}" class="card-img" style="max-height:300px" alt="{{ item.name }}">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title"><a href="{{ item.link }}">{{ item.name }}</a></h5>
        <p class="card-text"></p><p>{{ item.details }}</p>
      </div>
    </div>
  </div>

{% endfor -%}

## Useful sites
[Anglers Trust](https://www.anglerstrust.org/){:target="_blank"}

