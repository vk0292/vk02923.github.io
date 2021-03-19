<html>
<head>
  <title>A Leaflet map!</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.5.1/leaflet.css">
	<link rel="stylesheet" href="css/jquerymobile1.4.5min.css">

<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
	<script src="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.5.1/leaflet.js"></script>
	<script src="L.TileLayer.BetterWMS.js"></script>
  <style>
    #map{ height: 80% }
  </style>
</head>
<body>

  <div id="map"></div>
<div data-role="page" style="position:relative;">
  <div data-role="header">
    <h1>Species Selector</h1>
  </div>

  <div data-role="main" class="ui-content">
    <form method="post">
      <div data-role="rangeslider">
        <label for="price-min">Minimum Species:</label>
        <input type="range" name="price-min" id="price-min" value="100" min="0" max="500">
        <label for="price-max">Maximum Species:</label>
        <input type="range" name="price-max" id="price-max" value="400" min="0" max="500">
      </div>
        <input type="submit" data-inline="true" id="sub" value="Submit" onclick="myfunc()">
      </form>
  </div>
</div> 

  <script>
  var x;
  var y;
  var st;
  function myfunc(){
  var min = document.getElementById("price-min").value; 
x=min;  
	var max = document.getElementById("price-max").value;
	y=max;
	alert (x+","+y);
	st='min:'+x+';max:'+y;
	alert (st)
  load();
   // $.ajax({
  // url: 'richness.php',
  // type: 'get',
  // crossDomain: true,
  // data: {min:min, max:max},
  // success: function (response) {
   // alert(response);
   // //check(response);
   // jsneagle= JSON.parse(response);
   // lyertst= L.geoJSON(jsneagle).addTo(map);
  // }
  // });
};  
  
  // initialize the map
  var map = L.map('map').setView([20.5937, 78.9629], 4);

  // load a tile layer
  L.tileLayer(
    "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
    {
      minZoom: 2,
      maxZoom: 19,
      id: "osm.streets"
    }
  ).addTo(map);
  //vector layer
  species = L.tileLayer.betterWms('http://localhost:8080/geoserver/cite/wms', {
        layers: 'cite:fsi_new',
        transparent: true,
        format: 'image/png',
		viewparams: st
      });
	  species.addTo(map);

function load(){
	map.removeLayer(species)
	L.tileLayer.betterWms('http://localhost:8080/geoserver/cite/wms', {
        layers: 'cite:rich',
        transparent: true,
        format: 'image/png',
		viewparams: st
      }).addTo(map);
}
  </script>
</body>
</html>