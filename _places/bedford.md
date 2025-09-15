---
layout: place
title:  "Bedford"
categories: places
lat: 52.13834442793227
lng: -0.4674572440035926
background: /assets/images/bedford.jpg
---
Bedford, as the name suggests, came about because it was a ford across the river and became a prospeous market town thanks to the river being made navigable. 

It's a place that has made the most of its river setting and many locals take advantage of the strollable Embankment and Priory Country Park. 

You will also ususally see rowers on the river from local schools and enthusiasts alike.

If you fancy a paddle yourself then you can hire a canoe, kayak or paddleboard from [Canoe Trail](https://www.canoetrail.co.uk/canoe-kayak-sup-hire/bedford). You can even hire a canoe to paddle to Great Barford which is all part of the Ouse Valley Way.

But is is safe to go in the river? One group who are most likely to have the answers are [BedsGOVET](https://www.bedsgovet.org/) who regularly monitor for water quality.

The [John Bunyan Museum](https://www.bunyanmeeting.co.uk/museum) is a good place to learn more about the preacher and author.

It's also worth spending some time at the fascinating [Panacea Museum](https://panaceatrust.org/) where a group of locals spent the bulk of the 20th Century preparing for the second coming in a very English way.

### Audio downloads

{% for recording in site.data.recordings.panacea %}

<div class="card mb-3" >
  <div class="row g-0">
    <div class="col-md-4">
    <img src="{{ recording.image }}" class="card-img-top" alt="{{ recording.heading }}">
    </div>
    <div class="col-md-8">
      <div class="card-body">
    <h5 class="card-title">{{ recording.heading }}</h5>
    <p class="card-text">{{ recording.about }}</p>
        <audio controls>
          <source src="{{ site.baseurl }}{{ recording.filepath }}" type="audio/mpeg">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </div>
</div>

{% endfor %}

{% for recording in site.data.recordings.guru_nanak_temple %}
<div class="card mb-3" >
  <div class="row g-0">
    <div class="col-md-4">
    <img src="{{ recording.image }}" class="card-img-top" alt="{{ recording.heading }}">
    </div>
    <div class="col-md-8">
      <div class="card-body">
    <h5 class="card-title">{{ recording.heading }}</h5>
    <p class="card-text">{{ recording.about }}</p>
        <audio controls>
          <source src="{{ site.baseurl }}{{ recording.filepath }}" type="audio/mpeg">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </div>
</div>

{% endfor %}

In the 1950's, the London Brick Company, which had a brickworks nearby, looked to Italy for recruitment. As a result, 30% of modern day Bedford folk have Italian descent. Significant immigration from other parts of the world have made modern day Bedford an ethnically diverse place to be. Finding something interesting to eat isn't an issue...

### Accommodation
[booking.com](https://www.booking.com/searchresults.en-gb.html?ss=Bedford)

### Getting there
Bedford is reasonably well connected by train and bus to the rest of the country.
[National Rail](https://www.nationalrail.co.uk/live-trains/departures/bedford/)
[Bus departures](http://www.stagecoachbus.com/)

For getting between legs:

The X5 travels through Stony Stratford and Buckingham
The No. 25 bus goes between Bedford and Odell via [Pavenham](./pavenham.html), Harrold and Carlton.
The 905 bus goes between Bedford and Cambridge via [Great Barford](./great-barford.html), Roxton, Wyboston, Eaton Socon and [St Neots](./st-neots.html).
To travel to [Godmanchester](./godmanchester.md), change buses at St Neots where a No 66 will take you to Huntingdon.
