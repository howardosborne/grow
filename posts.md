---
layout: page
title: Latest
background: /assets/images/latest.jpg
---

  <div class="container">
    <div class="row">
      <div class="col-lg-8 col-md-10 mx-auto">

        <!-- Home Post List -->
        {% for post in site.posts %}

        <article class="post-preview">
         <div class="row g-0">
          <div class="col-md-4">
            <img src="{{ post.background }}" class="card-img" style="max-height:300px" alt="{{ post.title }}">
          </div>
          <div class="col-md-8">
          <a href="{{ post.url | prepend: site.baseurl | replace: '//', '/' }}">
            <h2 class="post-title">{{ post.title }}</h2>
            {% if post.subtitle %}
            <h3 class="post-subtitle">{{ post.subtitle }}</h3>
            {% else %}
            <h3 class="post-subtitle">{{ post.excerpt | strip_html | truncatewords: 15 }}</h3>
            {% endif %}
          </a>
          <p class="post-meta">{% include read_time.html content=post.content %}            
          </p>
          </div>
          </div>
        </article>

        <hr>

        {% endfor %}

      </div>
    </div>
  </div>
