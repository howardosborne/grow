---
layout: map
title: Audio Companion
background: /assets/images/swimming.jpg
loadFunction: loadOVW()
---
Discover more about the people and places along the Ouse Valley way. 
<br>
<i>Podcast coming soon</i>
<hr>
<div id="map" class="col-md-12" style="height: 300px;"></div>
<hr>
<div class="row">
{% for recording in site.data.recordingsarray %}
    <div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">
        <div class="card">
            <img src="{{ recording.image }}" class="card-img" alt="{{ recording.heading }}">
            <h3 class="card-title" >{{ recording.heading }}</h3>
            <p class="card-text" >{{ recording.about }}</p>
            <audio controls>
                <source src="{{ site.baseurl }}{{ recording.filepath }}" type="audio/mpeg">
                    Your browser does not support the audio element.
            </audio>
        </div>
    </div>
{% endfor %}
</div>