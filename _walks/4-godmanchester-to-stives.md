---
layout: map
title: Godmanchester to St Ives
background: /assets/images/2/houghton_mill.jpg
description: Distance 10 km
stage: 11
loadFunction: loadOVWLeg(52.32993564785955, -0.0873887597458531,12,['Godmanchester to St Ives'])
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
The path out of Godmanchester is a little bit confusing as it heads to, and then through, the Godmanchester Nature Reserve but becomes clearer as it follows the river along Hemingford Meadow. 

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/hemmingford_meadow.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/hemmingford_meadow_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The route heads through Houghton Mill which has become a popular spot to paddle and swim.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/houghton_mill.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/houghton_mill_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

<img src="/assets/images/2/houghton_mill_3.jpg" class="rounded card-img-top" alt="...">

Concerns over water quality have led a [local group](https://greatousevalleytrust.org.uk/our-work/caring-for-our-river/){:target="_blank"} to take matters into their own hands and they have started carrying out their own testing.

The route then carries alongside Houghton Meadows and the Great Ouse into St Ives, but not before passing [Holt Island](https://www.holtisland.org/){:target="_blank"} which is worth a detour. It's also a chance to learn about the [history of the island](https://www.holtisland.org/history-of-holt-island-wildlife/){:target="_blank"} and the philantropist who made a valuable donation to the town.

St Ives is an example of a place that grew in prosperity thanks to trade links despite its vulnerability to flooding. Sitting on a bench at the sleepy quayside, it's vauguely possible to imagine the town in its hayday, with goods being transferred from boat to cart and then crossing the bridge south towards London. But what did it feel like?

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/st_ives_2.jpg" class="rounded card-img-top" alt="st Ives bridge"></div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/st_ives_bridge.jpg" class="rounded card-img-top" alt="st Ives bridge"></div>
</div>

There are some clues. The chapel on the bridge was built in the 15th Century for giving thanks for safe passage. Over time, the need for this reduced and the chapel became a pub to service the port workers' need for beer. Despite rumours, it probably wasn't a [bawdy house](https://en.wikipedia.org/wiki/St_Ives_Bridge){:target="_blank"}.

It's worth considering taking a detour to visit the [Fen Drayton Lakes Reserve](https://www.rspb.org.uk/days-out/reserves/fen-drayton-lakes){:target="_blank"}.

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
The easiest approach is to catch the 'B' bus between Huntingdon and St Ives. [Stagecoach](https://www.stagecoachbus.com/)

<hr>
Next leg: [St Ives to Earith](/walks/5-stives-to-earith.html)

Back to [overview](/walks/ousevalleyway.html)