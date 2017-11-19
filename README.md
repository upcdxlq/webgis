<html>
<head>
<meta charset="utf-8">
<link rel="stylesheet"href="https://arcgis.js.com/4.5/esri/css/main.css">
<script src="https://arcgis.js.com/4.5"></script>
<style>
html,body,
#viewDiv{
padding:0;
margin:0;
width:100%;
heigth:100%;
}
</style>
</head>

<body>
<script>
require(["esri/Map","esri/views/MapView","dojo/domReady!"],function(Map,MapView){
  var map = new Map({
      basemap:"topo"
  });
  
  var view = new MapView({
    container:"viewDiv",
    map:map
  });
  
});
</script>
<div id="viewDiv">
</div>
</body>
</html>
