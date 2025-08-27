---
layout: place
title:  "Stowe"
categories: places
lat: 52.0220025
lng: -1.0085824
background: /assets/images/stowe.jpg
---

The first leg of the Ouse Valley Way skirts around Stowe Gardens which is probably *the* quintessential English Landscape Garden.

They were designed and nutured by gardening gurus William Kent and Capability Brown back in the 18th Century and are now owned and run by the National Trust.

{% for recording in site.data.recordings.stowegardens %}
<div class="card col-6">
  <img src="{{ recording.image }}" class="card-img-top" alt="stowe">
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

The Gardens are also filled with temples and monuments that are filled with meaning.

Why not stop at for a cuppa at the cafe, browse the giftshop and their pretty impressive second-hand bookshop.

[About Stowe](https://www.youtube.com/watch?v=fdJ6wj6vEs4)

[Stowe School](https://www.stowe.co.uk/)

[Stowe Gardens](https://www.nationaltrust.org.uk/visit/oxfordshire-buckinghamshire-berkshire/stowe-gardens)

## Getting there
The nearest bus stop is in Chackmore where the 134 bus goes between Buckingham and Westbury via Chackmore and Dadford. 

[Traveline](https://www.traveline.info/)
