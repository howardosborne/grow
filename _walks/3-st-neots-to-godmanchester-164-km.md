---
layout: map
title: St Neots to Godmanchester
background: /assets/images/2/paxton_pits.jpg
description: Distance 16.4 km
stage: 10
loadFunction: loadOVWLeg(52.28910893512988, -0.21304488747717346,12,['St Neots to Godmanchester'])
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
This is a well-marked trail, however, the start can be a little confusing in negotiating the St Neots streets to get to the Way.

It's a short walk to Great Paxton and the pits that have become a nature reserve.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/paxton_pits.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/paxton_pits_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

There are also other trails through the nature reserve that are worth a diversion.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/paxton_pits_3.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/paxton_pits_4.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

Not all of the way to Godmanchester is as accessible as it could be with fallen trees and other impediments.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/obstacles.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/obstacles_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The East Coast Mainline railway runs parallel to the river and increasingly makes its presence felt until you're close enough to do some trainspotting. On the far side are the twin villages of Offord Cluny and Offord d'Arcy. Each has a church that's big enough for both except one is a spire making it *slightly* more impressive. 

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/Offord_cluny.jpg" class="rounded card-img-top" alt="...">
<small>Offord Cluny</small>
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/Offord_darcy.jpg" class="rounded card-img-top" alt="...">
<small>Offord D'Arcy</small>
</div>
</div>

Whatever sibling rivalry used to go on is now a thing of the past and the two villages share communal resources, including just one church, with the other one mothballed and under the care of the [Churches Conservation Trust](https://www.visitchurches.org.uk/){:target="_blank"}.

Buckden also offers some diverting walks and [Buckden Towers](https://www.buckden-towers.org.uk/){:target="_blank"}, former home of the bishops of Lincoln is worth a look.

The route then continues past Brampton Mill which has a pub (and an Environment Agency site) and across the common to Godmanchester. At this point, it is as easy to go to Huntingdon as Godmanchester which is where most of the facilities are, as well as the bus and railway stations. It's also a chance to pop to the pleasingly compact [Oliver Cromwell Museum](https://www.cromwellmuseum.org/){:target="_blank"}.

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
Trains run between St Neots and Huntingdon which is on the other side of the Great Ouse from Godmanchester.
Alterntively, the No 66 bus also runs between St Neots and Huntingdon. 

Train times: [National Rail](https://www.nationalrail.co.uk/journey-planner/)

Bus times: [Whippet bus](https://www.whippetbus.co.uk/)
<hr>
Next leg: [Godmanchester to St Ives](/walks/4-godmanchester-to-stives.html)

Back to [overview](/walks/ousevalleyway.html)