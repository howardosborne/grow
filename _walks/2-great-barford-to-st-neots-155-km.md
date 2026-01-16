---
layout: map
title: Great Barford to St Neots
background: /assets/images/2/eaton_socon_weir.jpg
description: Distance 15.5 km
stage: 9
loadFunction: loadOVWLeg(52.18296647897254, -0.3083600078899254,12,['Great Barford to St Neots'])
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
From Great Barford, the route diverts along the road past the sewage works and then through a series of fields to Roxton. There are also some properties which it's hard not to be envious of.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/great_ouse_to_roxton.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/private__diving_board.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

As the route reaches Roxton Weir, passing a well-manicured lake on the left, the path heads into Roxton. Roxton Congregational church is worth a nosey.

<div class="row">
<div class="col-lg-9 col-md-9 col-sm-12 col-xs-12">
<img src="/assets/images/2/roxton_church.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-3 col-md-3 col-sm-12 col-xs-12">
<img src="/assets/images/2/roxton_church_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

From Roxton, the character of the walk changes dramatically. The route leaves the Great Ouse to follow a path across the Great North Road (A1).

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/new_roads.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/new_infrastructure.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

Major developments are underway in this area with new road and rail infrastructure, along with a substantial increase in housing. Locals are not happy.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/protest.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/protest_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The approach to Wyboston gives the impression of it being a quiet village - and most of it is.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/wyboston.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/wyboston_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

However, at the eastern end of the village, the noise of traffic increases as we approach the A1.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/A1.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/A1_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The route continues along the A1 roadside and for a while. It's pretty unpleasant. After time spent by the river, it's a powerful reminder of how mobile we now are and the way our modern economy works. 
There's a crossing point at Eaton Socon and again the path rejoins the Great Ouse.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/eaton_socon.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/eaton_socon_weir.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

From this point on, the trail is in pretty good shape with good signage and other resources, thanks in large part to the [Great Ouse Valley Trust](https://greatousevalleytrust.org.uk/ouse-valley-way/){:target="_blank"}.

<img src="/assets/images/2/great_ouse_signage.jpg" class="rounded card-img-top" alt="...">

Eaton Socon is split from St Neots by the Great Ouse and walks from here into St Neots take you through the flood plains that help manage the water.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/eaton_st_neots.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/st_neots_greenway.jpg" class="rounded card-img-top" alt="...">
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
The 905 bus runs between Bedford and Cambridge stopping at Great Barford and St Neots.[Stagecoach](https://www.stagecoachbus.com/)
<hr>

Next leg: [St Neots to Godmanchester](/walks/3-st-neots-to-godmanchester-164-km.html)

Back to [overview](/walks/ousevalleyway.html)