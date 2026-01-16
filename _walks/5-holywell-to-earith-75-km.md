---
layout: map
title: Holywell to Earith
background: /assets/images/3/earith_3.jpg
description: Distance 7.5 km
stage: 12
loadFunction: loadOVWLeg(52.32983074362752, 0.002046817816754357,12,['Holywell to Earith'])
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
Leaving Holywell, the path heads along a dry ridge which is clearly useful in this floodable area

<img src="/assets/images/2/holywell_6.jpg" class="rounded card-img-top" alt="...">

and through the [Pike & Eel Hotel and Marina](http://www.pikeandeel.com/){:target="_blank"}, which is also an option for refreshments and overnighting.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/pike_and_eel.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/pike_and_eel_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The route carries on past the Browshill staunch and sluice, which is the first significant part of the water management system that has helped maintain the Fens as they are today. The path then heads to the village of Earith where we can now safely say, we are in the Fens. This is the point where managing water has been the No. 1 priority for the last 300 years. 

While here, there's a chance to look as the Civil War fortification, the Earith Bulwark, which is now a rabbit warren. It's hard to make sense of the place and what it used to be like.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/earith_bulwark.jpg" class="rounded card-img-top" alt="earith bulwark">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/earith_bulwark_2.jpg" class="rounded card-img-top" alt="earith bulwark">
</div>
</div>

However, times of flood bring the bulwark back to life.

<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/bbc_earith_bulwark.jpg" class="rounded card-img-top" alt="bbc earith bulwark">
<small>Courtesy of the BBC</small>
</div>

The Fens were drained by creating two parallel drains, called the Old and New Bedford Rivers. 
<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/old_bedford_river.jpg" class="rounded card-img-top" alt="...">
<small>Old Bedford River</small>
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/new_bedford_river.jpg" class="rounded card-img-top" alt="...">
<small>New Bedford River</small>
</div>
</div>

The land between them, the Ouse Washes, acts as temporary resevoir during times of flood. 

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/ouse_washes.jpg" class="rounded card-img-top" alt="Ouse Washes">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/2/ouse_washes_2.jpg" class="rounded card-img-top" alt="Ouse Washes">
</div>
</div>

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/earith.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/3/earith_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

It's a haven for birds and you can see for yourself by walking along either the Old or New Beford Rivers all the way to Denver.  There is an [RSPB site](https://www.rspb.org.uk/days-out/reserves/ouse-washes){:target="_blank"} on the Old Bedford River and [WWT Welney](https://www.wwt.org.uk/wetland-centres/welney){:target="_blank"} is situated on the New Bedford River. If you want to spend some time walking by the Ouse Washes, but also want to go to Ely, a route has been marked out.

Also, for a glimpse of how things used to be before the Dutch engineers arrived, you could visit the [Ouse Fen Reserve](https://www.rspb.org.uk/reserves-and-events/reserves-a-z/ouse-fen/){:target="_blank"}.

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
Public transport is not practical between Holywell and Earith.

<hr>
Next leg: [Earith to Ely](/walks/1-earith-to-ely-25-km.html)

Back to [overview](/walks/ousevalleyway.html)