---
layout: page
title: Places
background: /assets/images/places.jpg
---

Here is a list of places along the Great Ouse with practical details of how to get there and where to stay.

  <div class="container">
    <div class="row">
      <div class="col-lg-8 col-md-10 mx-auto">

        <!-- Place List -->
        {% for place in site.places %}

        <article class="post-preview">
          <a href="{{ place.url | prepend: site.baseurl | replace: '//', '/' }}">
            <h2 class="post-title">{{ place.title }}</h2>
          </a>
        </article>

        <hr>

        {% endfor %}

      </div>
    </div>
  </div>
