---
layout: page
title: Places
background: /assets/images/places.jpg
---

Here is a list of places along the Great Ouse with practical details of how to get there and where to stay.

  <div class="container">
    <div class="row">
      <div class="col-lg-10 col-md-10 mx-auto">

        <!-- Place List -->
        {%- for place in site.places %}
        <div class="card">
          <div class="row g-0">
            <div class="col-md-4">
              <img src="{{ place.background }}" class="card-img" style="max-height:300px" alt="{{ place.title }}">
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h5><a href="{{ place.url | prepend: site.baseurl | replace: '//', '/' }}">{{ place.title }}</a></h5>
              </div>
            </div>
          </div>
        </div>
        {% endfor -%}

      </div>
    </div>
  </div>
