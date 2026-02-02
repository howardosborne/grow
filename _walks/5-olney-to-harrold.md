---
layout: map
title: Olney to Harrold
background: /assets/images/1/to_turvey.jpg
description: Distance 12 km
stage: 5
loadFunction: loadOVWLeg(52.16695535798543, -0.6249535720779718,12,['Olney to Harrold'])
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
From Olney the route heads across meadows where locals often go paddling and swimming despite warnings not to and up the hill to the village of Clifton Reynes.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/olney_meadows.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/path_to_clifton_reynes.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The village has a community pub, a theatre and a church with some eye-catching tombs.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/clifon_reynes.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/clifon_reynes_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

<img src="/assets/images/1/clifton_reynes_3.jpg" class="rounded card-img-top" alt="...">

The way then continues to Turvey in Bedfordshire

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/to_turvey.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/to_turvey_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

where the Great Ouse marks the county border.

<img src="/assets/images/1/turvey_border.jpg" class="rounded card-img-top" alt="...">

Turvey is a pleasant village, despite having to manage a fair weight of passing traffic, and is a good place to get provisions.

<img src="/assets/images/1/turvey.jpg" class="rounded card-img-top" alt="...">

The church also contains a curious mauseleum for the local big-wigs which suggests that there is more to it than meets the eye - look at the bricked-in door at the front...

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/Turvey%20memorial.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/Turvey%20memorial%202.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The route leaves the river behind and continues over farmland to Carlton where [The Fox](http://www.thefoxatcarlton.pub/){:target="_blank"} will serve up lunch, or a real ale liquid lunch - it prides itself on its CAMRA awards.

<img src="/assets/images/1/fox.jpg" class="rounded card-img-top" alt="Fox">

The route then drops down to Harrold via a bridge that is well used to dealing with flooding.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/harrold_bridge.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/harrold_bridge_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

[Harrold Odell Country Park](https://hocp.co.uk/){:target="_blank"} is one of several accessible nature-rich habitats that have been created thanks to quarrying for sand and gravel. There's a visitor centre, cafe and pay-by-donation car park. The bridge is also a popular place for bathers and paddlers heading towards Felmersham.

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
Travel between Olney and Harrold requires travelling into Bedford (No. 41) and back out again (No. 41). The No. 41 goes via Turvey which is half-way along the route.

Bus times: [Grant Palmer](https://www.grantpalmer.com/).

<hr>

Next leg: [Harrold to Pavenham](/walks/6-harrold-to-pavenham.html)

Back to [overview](/walks/ousevalleyway.html)