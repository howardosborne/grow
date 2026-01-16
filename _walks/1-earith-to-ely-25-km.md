---
layout: map
title: Earith to Ely
background: /assets/images/3/ely_2.jpg
description: Distance 25 km
stage: 13
loadFunction: loadOVWLeg(52.35164556993051, 0.1996290639083427,12,['Earith to Ely'])
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
From Earith, the route seems to go in the wrong direction, heading East-South-East, around Upper Delphs, Ewell Fen, Holme Fen, Upper Cuts, Middle Cuts and Chear Fen - all names for stretches of reclaimed land. At Stretham Mere, the route heads back in the right direction past the [Stretham Old Engine](https://www.strethamoldengine.com/){:target="_blank"} which used to be one of many engines carrying out the drainage work in the Fens. The [Red Lion](https://www.theredlionstretham.co.uk/){:target="_blank"} in Stretham offers food, drink and a bed for the night, in case the journey to Ely is a fen too far.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/stretham.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/stretham_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The walk 'up' to Ely which, being 26 metres above sea level is the highest land around here, is rewarded with some great views and a suitably splendid Cathedral. If you arrive around May Bank holiday, you can join in the fun of [Eel Day](https://en.wikipedia.org/wiki/Ely_Eel_Day){:target="_blank"} when the city's namesake is celebrated.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/ely.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/ely_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/ely_3.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/ely_4.jpg" class="rounded card-img-top" alt="...">
</div>
</div>
<hr>

### Audio downloads
<div class="row">
{% for item in site.data.recordings %}
{% if item[1].stage == page.stage and item[1].draft == "false" %}
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
There is no direct bus between Earith and Ely, but you can catch a Tiger 12 bus to Sutton and ZIP2 to Ely.
Bus times: [Tiger bus routes](https://cambridgeshirepeterborough-ca.gov.uk/tiger-bus-routes/).

Alternatively, you could go via Cambridge.

<hr>
Next leg: [Ely to Downham Market](/walks/2-ely-to-downham-market-28-km.html)

Back to [overview](/walks/ousevalleyway.html)