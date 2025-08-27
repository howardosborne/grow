---
layout: place
title:  "Houghton Mill"
categories: places
lat: 52.33098398325377
lng: -0.12063160290674026
background: /assets/images/2/houghton_mill_2.jpg
---
The Ouse Valley Way passes through Houghton Mill, which owned by the National Trust and a popular tourist spot.


### Audio download

Here I met up with Keith Grimwade and Bridget Flannagan who have been digging into and researching the history of milling in the area and made some surprising findings. 

Here is our conversation broken down into bite-size chunks that you can download and listen to while walking through Houghton Mill:

**add a map in here with the locations of the recordings

{% for recording in site.data.recordings.watermills %}
<div class="card col-6">
  <img src="{{ recording.image }}" class="card-img-top" alt="Houghton Mill">
  <div class="card-body">
    <h5 class="card-title">{{ recording.heading }}</h5>
    <p class="card-text">{{ recording.about }}</p>
        <audio controls>
          <source src="{{ site.baseurl }}{{ recording.filepath }}" type="audio/mpeg">
          Your browser does not support the audio element.
        </audio>
  </div>
</div>
{% endfor %}

Their book, The Watermills and Landscape of the River Great Ouse, Cambridgeshire, is available for sale at various bookstores including [here](https://www.oxbowbooks.com/9781914427411/the-watermills-and-landscape-of-the-river-great-ouse-cambridgeshire/).

### Accommodation
Here are some ideas for places to stay:

[Eagle Mill](https://maps.app.goo.gl/X1R5L6BzfLZDGjJP7)

[Burnham House](https://www.booking.com/hotel/gb/superb-4bd-stay-in-wyton-and-houghton-village.en-gb.html)

### Getting there
You can catch a [B bus](https://www.stagecoachbus.com/) to/from [Huntingdon](./godmanchester.md) or [St Ives](./st-ives.html).