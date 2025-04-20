---
layout: default
---

<!-- Page Header -->
{% if page.background %}
<header class="masthead" style="background-image: url('{{ page.background | prepend: site.baseurl | replace: '//', '/' }}')">
  {% else %}
  <header class="masthead">
    {% endif %}
    <div class="overlay"></div>
    <div class="container">
      <div class="row">
        <div class="col-lg-8 col-md-10 mx-auto">
          <div class="page-heading">
            <h1>{{ page.title }}</h1>
            {% if page.description %}
            <span class="subheading">{{ page.description }}</span>
            {% endif %}
          </div>
        </div>
      </div>
    </div>
  </header>

  <div class="container">
    <div class="row">
      <div class="col-lg-8 col-md-10 mx-auto">

        {{ content }}

      </div>
    </div>
  </div>

<script>
  const map = L.map('map').setView([50, 0], 5);
  const tiles = L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {maxZoom: 19,	attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'}).addTo(map);
    var my_icon = L.icon({iconUrl: "../assets/images/place.png",iconSize: [24, 24], iconAnchor: [12,24]});
    var markers = L.layerGroup();
    map.addLayer(markers);
    marker = L.marker([{{ page.lat }}, {{ page.lng }}],{icon:my_icon});
    marker.properties = {};
    marker.addTo(markers);
    map.flyTo([{{ page.lat }}, {{ page.lng }}],11)
</script>
