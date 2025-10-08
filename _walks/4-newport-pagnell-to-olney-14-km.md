---
layout: map
title: Newport Pagnell to Olney
background: /assets/images/1/Haystack%20near%20Sherington.jpg
description: Distance 14 km
stage: 4
loadFunction: loadOVWLeg(52.10851788150435, -0.7040708104620679,12)
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
From Newport Pagnell the route crosses the Great Ouse at the weir and heads to Sherington where a curious event took place in 1935.

<img class="rounded card-img-top" src="/assets/images/1/Great%20Ouse%20at%20Newport%20Pagnell.jpg" alt="NP">

Delegations from long time rivals Oxford and Cambridge Universities met here to dig a hole and place a small axe in it. What better way to symbolise the ending of their rivalries by 'burying the hatchet'.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/Sherington%20burying%20the%20hatchett%202.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/Sherington%20burying%20the%20hatchett.jpg" alt="syresham to buckingham">
</div>
</div>

There's also a nice path up to the church.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img class="rounded card-img-top" src="/assets/images/1/Path%20to%20Sherington%20church.jpg" alt="syresham to buckingham">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/Path%20to%20Sherington%20church%202.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

<img src="/assets/images/1/Sherington%20church.jpg" class="rounded card-img-top" alt="...">

The official route takes a long detour towards Tyringham, but doesn't quite reach John Soane's striking [Tyringham Hall](https://en.wikipedia.org/wiki/Tyringham_Hall){:target="_blank"}. 

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/points/tyringham_bridge.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/Tyringham_Hall.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The house isn't open to the public but you can see the gatehouse and bridge and a diversion to these has been added to the map. Alternatively, a more direct route is also marked on the map in case you would rather spend your time amusing and [amazing](https://cowperandnewtonmuseum.org.uk/){:target="_blank"} yourself in [Olney](/places/olney.html). The route also goes through Emberton Country Park which leads up to a weir and sluice system for managing water.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/Emberton%20Country%20park%202.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/Olney%20weir.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

Olney is a comfortable Georgian town and as the signs say, the 'home of Amazing Grace'. You might want to spend some time here finding out more at the [Cowper and Newton museum](https://cowperandnewtonmuseum.org.uk/){:target="_blank"}.

It's also home to [pancake racing](http://olneypancakerace.org/){:target="_blank"}, but if you're here at the wrong time of year, you could always make up your own race with something from the [Pancake Parlour](https://www.olneypancakeparlour.co.uk/){:target="_blank"}.

<div class="row">
<div class="col-lg-8 col-md-8 col-sm-12 col-xs-12">
<img src="/assets/images/1/Olney%20sign.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">
<img src="/assets/images/1/Olney%20Pancake%20Race%20sculpture.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

<div class="row">
<div class="col-8">
</div>
<div class="col-4">
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
The No. 21 runs hourly between Newport Pagnell and Olney. Bus times: [Red Rose](https://www.redrosetravel.com/).

<hr>

Next leg: [Olney to Odell](/walks/5-olney-to-odell-13-km.html)

Back to [overview](/walks/ousevalleyway.html)