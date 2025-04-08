---
layout: page
title: Places
background: /assets/images/places.jpg
---

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
