---
layout: map
title: Stony Stratford to Newport Pagnell
background: /assets/images/1/Stony%20Stratford.jpg
description: Distance 16.5 km
stage: 3
loadFunction: loadOVWLeg(52.065058871999796, -0.8057663750276123,12,['Stony Stratford to Newport Pagnell'])
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
Crossing Milton Keynes is a chance to see how the tricky business of creating a new city has been tackled.

## Ouse Valley Way or the Redways?
The Ouse Valley Way avoids much of Milton Keynes and even takes a curious detour to Little Linford rather than using the Redways, a network of walkable (and cycleable) routes. They are a great way to explore a city that was designed to be traversable by foot, bike or horse. Some highlights have been marked on the map so why not hire a bike or scooter and go explore?

[download redways map](https://getaroundmk.org.uk/wp-content/uploads/2020/06/MK_Redway_Poster.pdf){:target="_blank"} 

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/E-bike.jpg" alt="Ouse Valley Park">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/ruined_church_at_Stantonbury.jpg" class="rounded card-img-top" alt="Ouse Valley Park">
<small>Former church of St Peters, Stantonbury</small>
</div>
</div>

However you choose to cross MK, the initial part of the Ouse Valley Way route is worth taking as it goes through the expansive and well-managed Ouse Valley Park. It is owned and maintained by the [Parks Trust](https://www.theparkstrust.com/){:target="_blank"}, a unique self-funding body which looks after MK's green spaces.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/manor-farm-ouse-valley.jpg" alt="Ouse Valley Park">
<small>courtesy of Parks Trust</small>
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/media-ffnr.jpg" class="rounded card-img-top" alt="Ouse Valley Park">
<small>courtesy of Parks Trust</small>
</div>
</div>

The Park includes dedicated flood plains and lakes along the banks of the Great Ouse. A good option is to follow the Grand Union Canal to Great Linford Manor (marked on the map) and head into Newport Pagnell on the Redways.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/great_linford.jpg" alt="Great Linford">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/pond_at_Great_Linford_Manor.jpg" class="rounded card-img-top" alt="Great Linford">
</div>
</div>

However, should you choose to stick to the Ouse Valley Way, you will pass Haversham Weir and on to Little Linford.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/haversham_weir.jpg" alt="Haversham">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/little_linford.jpg" class="rounded card-img-top" alt="Little Linford">
</div>
</div>

One advantage of this route is seeing the attractive Linford Lakes, although the tunnel under the M1 is less than salubrious.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/Linford_lakes_3.jpg" alt="Linford Lakes">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/under_M1.jpg" class="rounded card-img-top" alt="under M1">
</div>
</div>

The end point is the town of Newport Pagnell which mirrors Stony Stratford as an old place at the edge of MK. It has the only vellum manufacturer in the United Kingdom and is the original home of Aston Martin.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/newport_pagnell.jpg" class="rounded card-img-top" alt="Newport Pagnell"></div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/newport.jpg" class="rounded card-img-top" alt="Newport Pagnell"></div>
</div>

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
There is no direct bus between Stony and Newport, but you can catch a 6 or X6 into town and change for a No. 2. Bus times [Arriva](https://www.arrivabus.co.uk/buy-tickets/region/beds-and-bucks).

It's also worth noting that the X5 runs from Oxford to Bedford via Milton Keynes Central Station.
<hr>

Next leg: [Newport Pagnell to Olney](/walks/4-newport-pagnell-to-olney.html)

Back to [overview](/walks/ousevalleyway.html)