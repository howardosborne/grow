---
layout: place
title:  "Buckingham"
categories: places
lat: 52.0019278	
lng: -0.986902381
background: /assets/images/buckingham.jpg
---
The old, but still growing, market town of Buckingham is worthwhile spending some time to have a wander around.

The architectural highlight is the Old Gaol which was built to help revive the town's fortunes after *the* great fire in 1725. Alas, it didn't do the trick and county town status has stayed with Aylesbury ever since. 

As if losing its status wasn't enough, the town has also lost its railway and its canal in the 20th Century.

Luckily each of these loses has come with a silver lining. The Gaol is now a small and friendly museum, the railway track has morphed into a pleasant stroll and parts of the Canal have been turned into a nature reserve. There are also big plans for the Canal which you can [hear about below](#audio-downloadsAudio downloads).

Locals have taken the initiative on looking after their river and its surroundings. Each year the local sub-aqua club help out with a river rinse.

The river wardens also monitor the river and its banks with regular monitoring. If you are coming through on a Friday, you can join them in one of their riverfly surveys.

If you are here on a Sunday, you could meet the locals who tend the Edible Garden. If you have forgotten to bring any provisions with you, why not see what they have to offer?

Market days are Tuesday and Saturday which take over Market Hill and the High Street cattle pens. 

### Audio downloads
{% for recording in site.data.recordings.buckingham %}
<div class="card">
  <img src="{{ recording.image }}" class="card-img-top" alt="buckingham">
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

### Accommodation
Two places to stay in town are [Villiers Hotel](https://www.villiers-hotel.co.uk/) and the 
[White Hart](https://www.greeneking.co.uk/pubs/buckinghamshire/white-hart) although other options are available through [Booking.com](https://www.booking.com/searchresults.en-gb.html?ss=Bedford)

### Getting there
Buckingham can be reached from Oxford, Milton Keynes, Bedford and Aylesbury. The X5 goes to Stony Stratford, Milton Keynes Central and Bedford. For getting to/from Syresham, change at Brackley (one bus a day goes directly).

[Bus departures](http://www.stagecoachbus.com/)
