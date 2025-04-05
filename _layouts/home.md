---
layout: default
---

<header class="masthead" style="background-image: url('/assets/images/main.jpg')">
    <div class="overlay"></div>
    <div class="container">
      <div class="row">
        <div class="col-lg-8 col-md-10 mx-auto">
          <div class="page-heading">
            <h1>{{ site.title }}</h1>
            {% if site.description %}
            <span class="subheading">{{ site.description }}</span>
            {% endif %}
          </div>
        </div>
      </div>
    </div>
  </header>

  <div class="container">
    <div class="row">
    <div class="col-lg-8 col-md-9 mx-auto">
            {{ content }}
    </div>
    <div class="col-lg-4 col-md-3 mx-auto">

        <!-- Pager -->
        <div class="clearfix">
          <a href="{{"/posts" | relative_url }}">Latest news &rarr;</a>
        </div>
        <!-- Home Post List -->
        {% for post in site.posts limit : 5 %}

        <article class="post-preview">
          <a href="{{ post.url | prepend: site.baseurl | replace: '//', '/' }}">
            <h2 class="post-subtitle">{{ post.title }}</h2>
          </a>
          <p class="post-meta">{% include read_time.html content=post.content %}            
          </p>
        </article>

        <hr>

        {% endfor %}

      </div>
    </div>
  </div>
