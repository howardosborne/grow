---
layout: map
title: Buckingham to Stony Stratford
background: /assets/images/1/Great%20Ouse%20from%20Buckingham.jpg
description: Distance 15 km
stage: 2
loadFunction: loadOVWLeg(52.023508802629614, -0.8961279318601949,12,['Buckingham to Stony Stratford'])
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
The path leaving Buckingham starts with a short stretch along the old Buckingham Canal which has been turned into a wildlife habitat. If you pass through on a Tuesday or Thursday you might see members of the [Canal Society](https://www.buckinghamcanal.org.uk/){:target="_blank"} carrying out maintenance.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/path_to_Buckingham_canal_2.jpg" alt="buckingham canal">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/Buckingham%20canal.jpg" class="rounded card-img-top" alt="buckingham canal">
</div>
</div>

Much of the route to up to Thornton follows the old canal and note how the old canal bed provides a haven for different species.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/Walk_along_Buckingham_canal.jpg" alt="buckingham canal">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/plants%20growing%20in%20former%20canal%20at%20Thornton.jpg" class="rounded card-img-top" alt="buckingham canal">
</div>
</div>

The route passes Thornton College which is a private boarding school and until 2025 was also a convent. The nuns have since moved to their mother house in Felixtowe. You can visit the Grade I listed church in the grounds by asking for a key at the College reception. From Thornton the route becomes trickier and the current issues have been marked on the map. 

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/path_runs_between_two_trees.jpg" alt="thornton">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/clear_path_towards_Beachampton.jpg" class="rounded card-img-top" alt="thornton">
</div>
</div>

At Beachampton, St Mary the Virgin church is often open if you fancy having a look around (or a sit down) and there are also a couple of benches in the surrounding graveyard.

<img class="rounded card-img-top" src="/assets/images/1/Beachampton%20church%202.jpg" alt="Beachampton">

The path onwards to Stony Stratford also has some confusing bits which can be made trickier by the presence of cattle. These have been marked on the map.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/confusing_paths_2.jpg" alt="confusion">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/confusing_paths.jpg" class="rounded card-img-top" alt="confusion">
</div>
</div>

Arriving at the Lower Wield of [Calverton](https://en.wikipedia.org/wiki/Calverton,_Buckinghamshire){:target="_blank"} marks the entry into the city of Milton Keynes.

<img src="/assets/images/1/Lower_Wield.jpg" class="rounded card-img-top" alt="calverton">

Milton Keynes (MK as the locals call it) takes its name from one of the 13 villages and towns that were incorporated into the new conurbation and if your only notion of MK is roundabouts and concrete cows, you will be in for a surprise.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/Stony%20Stratford.jpg" alt="syresham to buckingham">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/Stony%20Stratford%20Great%20Ouse%20path.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

It's just a short wander into the ancient coaching town of [Stony Stratford](/places/stony.html) which was, as the name suggests, the place where Watling Street crossed the Great Ouse (street ford).

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/bull_hotel.jpg" alt="bull">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/Great_Ouse_at_Stony_Stratford.jpg" class="rounded card-img-top" alt="ouse">
</div>
</div>

It's a good place to stay, or at least get something to eat and drink, and why not do as travellers in the past did and go to either the Cock Inn or the Bull Hotel and tell your own [Cock and Bull story](https://en.wikipedia.org/wiki/Cock_and_bull_story){:target="_blank"}.

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
The X6 can be used to getting between the start and end points. Bus times [Arriva](https://www.arrivabus.co.uk/buy-tickets/region/beds-and-bucks)

It's also worth noting that the X5 runs from Oxford to Bedford via Buckingham.
<hr>

Next leg: [Stony Stratford to Newport Pagnell](/walks/3-stony-stratford-to-newport-pagnell.html)

Back to [overview](/walks/ousevalleyway.html)