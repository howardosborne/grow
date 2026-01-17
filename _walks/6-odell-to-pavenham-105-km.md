---
layout: map
title: Odell to Pavenham
background: /assets/images/1/pavenham_2.jpg
description: Distance 10.5 km
stage: 6
loadFunction: loadOVWLeg(52.20831535653447, -0.5531991172625262,12,['Odell Pavenham'])
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
The route from Odell to Pavenham makes a long loop, as does the wending river and yet they barely meet, which is a shame. Even the part which does follow the course of the river through a golf course is obscured by woodland.

<img class="rounded card-img-top" src="/assets/images/1/odell_church.jpg" alt="Odell Pavenham">

Nevertheless, Sharnbrook is a good place for pub-based provisions and accommodation. Making a detour into Felmersham is worth the walk. 

When Niklaus Pevsner surveyed Bedfordshire for his epic series of books on the architecture of Britain, he put St Mary's in Felmersham at the top of the list. 

<img class="rounded card-img-top" src="/assets/images/1/StMarysFelmersham.jpg" alt="Felmersham">

The bridge is also a place where people come to bathe and paddle which should hopefully be a bit safer since the upgrade of the Odell sewage treatment plant upstream.

A shorter alternative route is marked on the map in case you would like to spend your time on some of the special places to come.

The village of [Pavenham](/places/pavenham.html) is rare for having a phone box with an actual phone in it and in the true tradition of public phone boxes, it doesn't work.

It's also where we join another walking route, the [John Bunyan Trail](https://en.wikipedia.org/wiki/John_Bunyan){:target="_blank"}. The author of Pilgrim's Progress used to walk about these parts as a tinker before his religious calling when he swapped mending pots and pans for saving souls.

<div class="row">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/pavenham.jpg" class="rounded card-img-top" alt="...">
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
<img src="/assets/images/1/pavenham_2.jpg" class="rounded card-img-top" alt="...">
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
The No. 25 bus goes between Odell and Pavenham (and into Bedford).

Bus times: [Grant Palmer](https://www.grantpalmer.com/).

<hr>

Next leg: [Pavenham to Bedford](/walks/7-pavenham-to-bedford-155-km.html)

Back to [overview](/walks/ousevalleyway.html)