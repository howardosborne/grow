---
layout: page
title: About
background: /assets/images/about.jpg
---
<div class="row row-cols-3" id="pictures"></div>
<button onclick="loadPictureGrid()">get photos</button>

<script src="https://cdn.jsdelivr.net/npm/@turf/turf@7/turf.min.js"></script>
<script>
async function loadPictureGrid(){
  const response = await fetch("/assets/data/picture_data_lean.json");
  pictureData = await response.json();
  pictureData.forEach(of => {
    let filename = of.url;
    filename = decodeURIComponent(filename.substring(filename.lastIndexOf("/")+1));
    let row = `<div class="col card">
          <img src="${of.url}" class="img-fluid rounded-start" alt="${of.name}" title = "${of.name}">
          <ul class="list-group">
          <li class="list-group-item">${of.id}: ${decodeURIComponent(of.name)}</li>
          <li class="list-group-item">${filename}</li>
</ul>
          </div>`;
    document.getElementById("pictures").insertAdjacentHTML('beforeend',row);
  });     
}    
</script>
<script>
let obstaclesData;
let navigationData;
let wcpData;
let cameoData;
let ouseObstacles = [];
async function loadCatchment(){
  const navigationResponse = await fetch("/assets/data/ubocp.geojson");
  navigationData = await navigationResponse.json();
  wcpResponse = await fetch("/assets/data/wcp.geojson");
  wcpData = await wcpResponse.json();
  const cameoResponse = await fetch("/assets/data/cameo.geojson");
  cameoData = await cameoResponse.json();  
}
async function loadObs(){
  const obstaclesResponse = await fetch("/assets/data/River_Obstacles_view2_-8611833760021409824.geojson");
  obstaclesData = await obstaclesResponse.json();
}
function findObstacles(){
    navigationData['features'].forEach(feature => {
        if(feature.geometry.type=="Polygon"){
            let poly = turf.polygon(feature.geometry.coordinates);
            obstaclesData['features'].forEach(of => {
            let pt = turf.point(of.geometry.coordinates);
                if(turf.booleanPointInPolygon(pt,poly)){
                    ouseObstacles.push(of);
                }
           });  
        }  
    });
    wcpData['features'].forEach(feature => {
        if(feature.geometry.type=="Polygon"){
            let poly = turf.polygon(feature.geometry.coordinates);
            obstaclesData['features'].forEach(of => {
            let pt = turf.point(of.geometry.coordinates);
                if(turf.booleanPointInPolygon(pt,poly)){
                    ouseObstacles.push(of);
                }
           });  
        }  
    });
    cameoData['features'].forEach(feature => {
        if(feature.geometry.type=="Polygon"){
            let poly = turf.polygon(feature.geometry.coordinates);
            obstaclesData['features'].forEach(of => {
            let pt = turf.point(of.geometry.coordinates);
                if(turf.booleanPointInPolygon(pt,poly)){
                    ouseObstacles.push(of);
                }
           });  
        }  
    });
}

</script>