---
layout: page
title:  "Watermills and landscape"
background: /assets/images/watermills/keith_and_bridget.jpg
date:   2025-07-31 15:00:00 +0100
categories: posts
---

The Ouse Valley Way passes through Houghton Mill, which owned by the National Trust and a popular tourist spot.

Here I met up with Keith Grimwade and Bridget Flannagan who have been digging into and researching the history of milling in the area and made some surprising findings. 

Here is our conversation broken down into bite-size chunks that you can download and listen to while walking through Houghton Mill:

**add a map in here with the locations of the recordings

{% for file in site.data.recordings %}
    {% if file.filepath contains '/assets/audio/watermills'%}
<div class="card col-6">
  <img src="{{ file.image }}" class="card-img-top" alt="Houghton Mill">
  <div class="card-body">
    <h5 class="card-title">{{ file.heading }}</h5>
    <p class="card-text">{{ file.about }}</p>
        <audio controls>
          <source src="{{ site.baseurl }}{{ file.filepath }}" type="audio/mpeg">
          Your browser does not support the audio element.
        </audio>
  </div>
</div>
    {% endif %}
{% endfor %}

Their book, The Watermills and Landscape of the River Great Ouse, Cambridgeshire, is available for sale at various bookstores including [here](https://www.oxbowbooks.com/9781914427411/the-watermills-and-landscape-of-the-river-great-ouse-cambridgeshire/).