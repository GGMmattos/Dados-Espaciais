<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_a08628c7a23239d537fb541bb59c757f {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>
        
    <script src="https://cdn.jsdelivr.net/gh/python-visualization/folium@main/folium/templates/leaflet_heat.min.js"></script>
</head>
<body>
    
    
            <div class="folium-map" id="map_a08628c7a23239d537fb541bb59c757f" ></div>
        
</body>
<script>
    
    
            var map_a08628c7a23239d537fb541bb59c757f = L.map(
                "map_a08628c7a23239d537fb541bb59c757f",
                {
                    center: [15.0, 30.0],
                    crs: L.CRS.EPSG3857,
                    ...{
  "zoom": 2,
  "zoomControl": true,
  "preferCanvas": false,
}

                }
            );

            

        
    
            var tile_layer_279b6a3f7b28eca4857e7f595739c302 = L.tileLayer(
                "https://{s}.basemaps.cartocdn.com/dark_all/{z}/{x}/{y}{r}.png",
                {
  "minZoom": 0,
  "maxZoom": 20,
  "maxNativeZoom": 20,
  "noWrap": false,
  "attribution": "\u0026copy; \u003ca href=\"https://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors \u0026copy; \u003ca href=\"https://carto.com/attributions\"\u003eCARTO\u003c/a\u003e",
  "subdomains": "abcd",
  "detectRetina": false,
  "tms": false,
  "opacity": 1,
}

            );
        
    
            tile_layer_279b6a3f7b28eca4857e7f595739c302.addTo(map_a08628c7a23239d537fb541bb59c757f);
        
    
            var heat_map_ad63f0c6db0988be9050de5f9793999d = L.heatLayer(
                [[-1.467, -78.442], [63.63, -19.62], [14.381, -90.601], [16.708, 145.78], [2.78, 125.48], [3.17, 98.392], [-7.542, 110.442], [-1.467, -78.442], [-7.942, 112.95], [-7.542, 110.442], [31.93, 130.87], [12.77, 124.05], [2.78, 125.48], [-1.467, -78.442], [-40.59, -72.117], [13.37, 41.7], [63.63, -19.05], [1.358, 124.792], [0.8, 127.325], [19.425, -155.292], [19.425, -155.292], [55.83, 160.33], [-7.542, 110.442], [-8.32, 121.708], [13.257, 123.685], [-8.32, 121.708], [-16.355, -70.903], [31.58, 130.67], [3.17, 98.392], [-38.12, 176.5], [3.17, 98.392], [-7.93, 112.308], [35.9, 137.48], [19.425, -155.292], [14.95, -24.35], [0.8, 127.325], [3.17, 98.392], [-41.326, -72.614], [2.78, 125.48], [-4.1, 145.061], [3.17, 98.392], [-38.12, 176.5], [3.17, 98.392], [3.17, 98.392], [44.43, -110.67], [-8.42, 116.47], [32.88, 131.1], [37.734, 15.004], [3.17, 98.392], [14.473, -90.88], [-7.2, 109.92], [40.827, 14.139], [-15.4, 167.83], [-7.542, 110.442], [3.17, 98.392], [-3.62, 144.62], [13.257, 123.685], [36.62, 138.55], [19.425, -155.292], [-3.62, 144.62], [-8.058, 114.242], [19.425, -155.292], [-15.4, 167.83]],
                {
  "minOpacity": 0.5,
  "maxZoom": 18,
  "radius": 25,
  "blur": 15,
}
            );
        
    
            heat_map_ad63f0c6db0988be9050de5f9793999d.addTo(map_a08628c7a23239d537fb541bb59c757f);
        
</script>
</html>
