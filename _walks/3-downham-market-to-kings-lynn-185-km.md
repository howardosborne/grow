---
layout: map
title: Downham Market to Kings Lynn
background: /assets/images/3/wiggenshalls_2.jpg
description: Distance 18.5 km
stage: 15
loadFunction: loadOVWLeg(52.67509474063244, 0.3692075631781401,12,['Downham Market to Kings Lynn'])
---
## Contents

- [<u>Route map</u>](#route-map)
- [<u>Route details</u>](#route-details)
- [<u>Audio downloads</u>](#audio-downloads)
- [<u>Public transport</u>](#public-transport)

<hr>

## Route map
<div id="map" class="col-md-12" style="height: 600px;"></div>
<hr>

## Route details
From Downham Market the way continues between the two 'rivers' through the Wiggenhalls. First Wiggenhall St Mary Magdalen (where there's a pub, the Cock Inn), then Wiggenhall St Peter where there is a ruined church.
<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/wiggenshalls.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/wiggenshalls_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

At Wiggenhall St Germans there's also is a pub to prepare for the final stretch.
<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/wiggenshalls_3.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/wiggenshalls_4.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

As the way draws towards Kings Lynn, the two 'rivers' (Great Ouse and its relief channel) combine and we pass the industrial outskirts before reaching the quay where the way ends. 

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/kings_lynn.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/kings_lynn_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

From there, the river flows out to sea.
<img src="/assets/images/3/kings_lynn_3.jpg" class="rounded card-img-top" alt="...">

For many, the commercial buildings are a fitting end to a journey along a river modified to bring prosperity and trade. However, if you want to sea the Wash and the sea, then why not continue along the [King Charles III Coastal Path](https://en.wikipedia.org/wiki/King_Charles_III_England_Coast_Path){:target="_blank"}?

### Audio downloads
<div class="row">
{% for item in site.data.recordings %}
{% if item[1].stage == page.stage %}
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<div class="card">
  <img src="{{ item[1].image }}" class="card-img-top" alt="stowe">
  <div class="card-body">
    <h5 class="card-title">{{ item[1].heading }}</h5>
    <p class="card-text">{{ item[1].about }}</p>
        <audio controls>
          <source src="{{ site.baseurl }}{{ item[1].filepath }}" type="audio/mpeg">
          Your browser does not support the audio element.
        </audio>
  </div>
</div>
</div>
{% endif %}
{% endfor %}
</div>

<hr>

## Public transport
There are trains every 30 mins between Downham Market and Kings Lynn. [National Rail](https://www.nationalrail.co.uk/journey-planner/)

<hr>

Back to [overview](/walks/ousevalleyway.html)