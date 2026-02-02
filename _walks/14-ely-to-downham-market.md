---
layout: map
title: Ely to Downham Market
background: /assets/images/3/willow_farm.jpg
description: Distance 28 km
stage: 14
loadFunction: loadOVWLeg(52.5007314504582, 0.36680632463759716,12,['Ely to Downham Market'])
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
At Ely the Ouse Valley Way combines with the [Fen Rivers Way](https://www.norfolk.gov.uk/article/42895/Fen-Rivers-Way-Kings-Lynn-to-Cambridge){:target="_blank"} and heads along Sandy's Cut to past the town of Littleport, which is useful for any provisions not acquired in Ely and on towards Brandon Creek, where the Great Ouse is joined by the Little Ouse.

The [Ship Inn](https://www.theshipbrandoncreek.com/){:target="_blank"} is a good option for food and drink.


<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/3/ship_inn.jpg" alt="Ship Inn">
<small>courtesy of Ship Inn</small>
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/ship_inn_2.jpg" class="rounded card-img-top" alt="Ship Inn">
<small>courtesy of Ship Inn</small>
</div>
</div>

The path continues along the Great Ouse which, if you are wondering how long this stretch of modified river is, is also known as Ten Mile River. It leads to the village of Ten Mile Bank with its modest church, which oddly predates the 19th Century village by six hundred years... 

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/3/ten_mile_bank.jpg" alt="Ten Mile Bank">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/ten_mile_church.jpg" class="rounded card-img-top" alt="Ten Mile Church">
</div>
</div>

Walking along the Ten Mile River drives home how flat the Fens are and only offers a vague glimpse into what the area may have been like before reclamation.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/3/ten_mile_river.jpg" alt="Ten Mile River">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/ten_mile_river_2.jpg" class="rounded card-img-top" alt="Ten Mile Church">
</div>
</div>

Finally, the path reaches the Denver Sluice where it is joined by the New and Old Bedford Rivers.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/3/denver_sluice.jpg" alt="Denver Sluice">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/denver_sluice_2.jpg" class="rounded card-img-top" alt="Denver Sluice">
</div>
</div>

The Sluice is a key part of the great system of fenland water control. The river, combining with the Old and New Bedford Rivers which were last seen at Earith, is then split between a tidal and non-tidal flow and the path passes between the two.

A little further on is the pleasant town of [Downham Market](/_places/downham_market.html), which these days is as much commuter town to Cambridge as it is a market. Unfortunately, the distinctive Castle Hotel is now private residences, perhaps for some of those Cambridge commuters...

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/downham_market.jpg" alt="Downham Market">
<small>courtesy of Uksignpix</small>
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/downham_market.jpg" class="rounded card-img-top" alt="Downham Market">
<small>courtesy of FromMorningToMidnight</small>
</div>
</div>

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
There are trains every 30 mins Between Ely and Downham Market. [National Rail](https://www.nationalrail.co.uk/journey-planner/)

<hr>


Next leg: [Downham Market to Kings Lynn](/walks/15-downham-market-to-kings-lynn.html)

Back to [overview](/walks/ousevalleyway.html)