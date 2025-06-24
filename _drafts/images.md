---
layout: page
title: About
background: /assets/images/about.jpg
---
{% for image in site.static_files %}
    {% if image.path contains '/assets/OuseValleyWay'%}
<img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}

<script src="https://cdn.jsdelivr.net/npm/@turf/turf@7/turf.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/exif-js"></script>
<script>
async function getFileInfo(){
  var imgFiles = document.getElementsByTagName("img");
  var imgFileSummary = {}
  for (let imgFile of imgFiles) {
    try{
      EXIF.getData(imgFile, function() {
            var allMetaData = EXIF.getAllTags(this);
            imgFileSummary[imgFile.src] = allMetaData;
            imgFileSummary[imgFile.src]['lat'] = allMetaData['GPSLatitude'][0] + allMetaData['GPSLatitude'][1] / 60 + allMetaData['GPSLatitude'][2] / 3600
            imgFileSummary[imgFile.src]['lng'] = allMetaData['GPSLongitude'][0] + allMetaData['GPSLongitude'][1] / 60 + allMetaData['GPSLongitude'][2] / 3600
            if(allMetaData['GPSLongitudeRef'] == "W"){imgFileSummary[imgFile.src]['lng'] = -1*imgFileSummary[imgFile.src]['lng']}
        });
    }
    catch(error){console.log(`couldn't process: ${imgFile.src}`)}
    }
  console.log(imgFileSummary);
}
</script>