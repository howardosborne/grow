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
          <a href="{{ post.url | prepend: site.baseurl | replace: '//', '/' }}">
            <h2 class="post-title">{{ post.title }}</h2>
            {% if post.subtitle %}
            <h3 class="post-subtitle">{{ post.subtitle }}</h3>
            {% else %}
            <h3 class="post-subtitle">{{ post.excerpt | strip_html | truncatewords: 15 }}</h3>
            {% endif %}
          </a>
          <p class="post-meta">Posted by
            {% if post.author %}
            {{ post.author }}
            {% else %}
            {{ site.author }}
            {% endif %}
            on
            {{ post.date | date: '%B %d, %Y' }} &middot; {% include read_time.html content=post.content %}            
          </p>
        </article>

        <hr>

        {% endfor %}

      </div>
    </div>
  </div>
