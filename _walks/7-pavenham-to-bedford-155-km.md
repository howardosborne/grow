---
layout: map
title: Pavenham to Bedford
background: /assets/images/1/pew_carvings_2.jpg
description: Distance 15.5 km
stage: 7
loadFunction: loadOVWLeg(52.16158520906302, -0.532256429278968,12,['Pavenham to Bedford'])
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
From Pavenham the route follows the river. Make sure you stick to the high ground as springs from the limestone ridge to your right keep sections of the path marshy all year round. It may by an annoyance for walkers but is a delight for bio-diversity. As a result, it has earned its status as a [Site of Special Scientific Interest](https://en.wikipedia.org/wiki/Stevington_Marsh).

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/pavenham_sssi.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/pavenham_sssi_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The constant flow of water to the river takes on a different significance at Stevington. Here you might see people who have come from miles away to fill up Jerrycans of water from a holy well which passes under St Mary's church (and graveyard). One person I spoke to only drinks water from here.

<div class="row">
<div class="col-lg-8 col-md-8 col-sm-12 col-xs-12">
<img src="/assets/images/1/st_mary_stevington.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">
<img src="/assets/images/1/holy_well.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The church is well worth a look inside as its pews have some lively medieval carvings.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/pew_carvings_1.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/pew_carvings_2.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The village has a community-run shop in the village hall and if you are passing through on a Wednesday, you are welcome to join the locals for lunch.

The route carries on crossing over the old railway line and past the Stevington postmill.

<img src="/assets/images/1/stevington_postmill.jpg" class="rounded card-img-top" alt="...">

Continuing into Bromham, the route meets back up with the Great Ouse at Bromham Mill. It's now a nice park and popular cafe and is next to Bromham Bridge which is attractive but not pedestrian friendly.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/bromhan_mill.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/bromham_bridge.jpg" class="rounded card-img-top" alt="...">
</div>
</div>

The official route continues along the riverside and is accompanied by the unrelenting sound of traffic from the A6 before ducking unexpectedly into a housing estate at Great Denham. Alternative routes have been marked on the map...

Heading into town, you'll pass near to the [Guru Nanak Gudwara Temple](http://gngbedford.org/){:target="_blank"} which welcomes passersby and the Eagle Brewery which, alas, does not. If you are desperate for a brewery tour, then you could visit their new facility at [Brewpoint](https://www.brewpoint.co.uk/){:target="_blank"}

Bedford makes the most of its river setting and a stroll through the parks that run along the river is a chance to see how it is actively used by local schools and enthusiats alike for rowing and kayaking.

You could also hire a canoe here to complete the next leg from [Canoe Trail](https://www.canoetrail.co.uk/canoe-kayak-sup-hire/canoe-hire){:target="_blank"} who regularly run canoe excursions to Great Barford.

Spending time in Bedford is also a chance to visit the [John Bunyan Museum](https://www.bunyanmeeting.co.uk/museum){:target="_blank"} and visit the [Panacea Society](http://panaceamuseum.org/){:target="_blank"}.

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
The No. 25 bus goes between Pavenham and Bedford.

Bus times: [Grant Palmer](https://www.grantpalmer.com/).

<hr>

Next Leg: [Bedford to Great Barford](/walks/1-bedford-to-great-barford-11-km.html)

Back to [overview](/walks/ousevalleyway.html)