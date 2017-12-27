Hi, this is a first update... 
and a second one...
again...
<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT8JooVUngi5NG2wbqvKR6GImZE1hxmEh8RTqmlZhSvAcgpswFMSU80pZ1pTKsmq34fwbVCFamL6HaL/pubchart?oid=1851654712&amp;format=interactive"></iframe>

...and now maps...
Now we start a map...
 
 <link rel="stylesheet" href="https://unpkg.com/leaflet@1.2.0/dist/leaflet.css"
   integrity="sha512-M2wvCLH6DSRazYeZRIm1JnYyh22purTM+FDB5CsyxtQJYeKq83arPe5wgbNmcFXGqiSH2XR8dT/fJISVA1r/zQ=="
   crossorigin=""/>
   
    <div id="mapid"></div>
    var mymap = L.map('mapid').setView([51.505, -0.09], 13);
   L.tileLayer('https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token={accessToken}', {
    attribution: 'Map data &copy; <a href="http://openstreetmap.org">OpenStreetMap</a> contributors, <a href="http://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="http://mapbox.com">Mapbox</a>',
    maxZoom: 18,
    id: 'mapbox.streets',
    accessToken: pk.eyJ1IjoicmljaXNvbGEiLCJhIjoiY2picGo2YXlvNXMxdjMzbXJsb243YWt3OCJ9.n3x81v5frWq5MG_rVTdk1Q 'your.mapbox.access.token'
}).addTo(mymap);
   
    <!-- Make sure you put this AFTER Leaflet's CSS -->
 <script src="https://unpkg.com/leaflet@1.2.0/dist/leaflet.js"
   integrity="sha512-lInM/apFSqyy1o6s89K4iQUKg6ppXEgsVxT35HbzUupEVRh2Eu9Wdl4tHj7dZO0s1uvplcYGmt3498TtHq+log=="
   crossorigin=""></script>
   
