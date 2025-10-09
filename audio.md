---
layout: map
title: Audio Companion
background: /assets/images/swimming.jpg
loadFunction: loadChatMap()
---
<div class="row">
    <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
        Discover more about the people and places along the Ouse Valley way. 
        <br>
        <i>Podcast coming soon</i>
    </div>
    <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
        <div id="map" class="col-md-12" style="height: 300px;"></div>
    </div>
</div>
<hr>
<div class="row">
{% for item in site.data.recordings %}
{% if item[1].draft == "false" %}
    <div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">
        <div class="card">
            <img src="{{ item[1].image }}" class="card-img" alt="{{ item[1].heading }}">
            <h3 class="card-title" >{{ item[1].heading }}</h3>
            <p class="card-text" >{{ item[1].about }}</p>
            <audio controls>
                <source src="{{ site.baseurl }}{{ item[1].filepath }}" type="audio/mpeg">
                    Your browser does not support the audio element.
            </audio>
        </div>
    </div>
{% endif %}
{% endfor %}
</div>