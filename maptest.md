---
layout: default
---

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
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_5f60191edd2c434941a980f7835a9d23 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>
        
</head>
<body>
    
    
            <div class="folium-map" id="map_5f60191edd2c434941a980f7835a9d23" ></div>
        
</body>
<script>
    
    
            var map_5f60191edd2c434941a980f7835a9d23 = L.map(
                "map_5f60191edd2c434941a980f7835a9d23",
                {
                    center: [40.65261, -73.94576],
                    crs: L.CRS.EPSG3857,
                    zoom: 14,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_d9ac2c21f8b521692800bf1c50f09d7d = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca target=\"_blank\" href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca target=\"_blank\" href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_5f60191edd2c434941a980f7835a9d23);
        
    
            var marker_24ad2bf9402842c58242d3f192f0373e = L.marker(
                [40.645753, -73.9540491],
                {}
            ).addTo(map_5f60191edd2c434941a980f7835a9d23);
        
    
            var icon_495f9e178ceee1663668cc7a8ecae590 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_24ad2bf9402842c58242d3f192f0373e.setIcon(icon_495f9e178ceee1663668cc7a8ecae590);
        
    
        var popup_feb9ba540c740034180f2fcaeafee305 = L.popup({"maxWidth": "100%"});

        
            
                var html_c2a049fb3df2e509e73f8fb5e800aca1 = $(`<div id="html_c2a049fb3df2e509e73f8fb5e800aca1" style="width: 100.0%; height: 100.0%;">Street Name: Lott St<br>Family: Lott</div>`)[0];
                popup_feb9ba540c740034180f2fcaeafee305.setContent(html_c2a049fb3df2e509e73f8fb5e800aca1);
            
        

        marker_24ad2bf9402842c58242d3f192f0373e.bindPopup(popup_feb9ba540c740034180f2fcaeafee305)
        ;

        
    
    
            var marker_0fb02633155cc113bbd6bf13b27e51a0 = L.marker(
                [40.6515944, -73.9516199],
                {}
            ).addTo(map_5f60191edd2c434941a980f7835a9d23);
        
    
            var icon_d4d78588adf269f957c48d1015cb714d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_0fb02633155cc113bbd6bf13b27e51a0.setIcon(icon_d4d78588adf269f957c48d1015cb714d);
        
    
        var popup_995cdaade4e98b3340bc2976c33f8336 = L.popup({"maxWidth": "100%"});

        
            
                var html_7b6eecfdc804328e16f0fe486b970f9d = $(`<div id="html_7b6eecfdc804328e16f0fe486b970f9d" style="width: 100.0%; height: 100.0%;">Street Name: Martense St<br>Family: Martense</div>`)[0];
                popup_995cdaade4e98b3340bc2976c33f8336.setContent(html_7b6eecfdc804328e16f0fe486b970f9d);
            
        

        marker_0fb02633155cc113bbd6bf13b27e51a0.bindPopup(popup_995cdaade4e98b3340bc2976c33f8336)
        ;

        
    
    
            var marker_2f493ffcda28ee1cc9b71461f846f691 = L.marker(
                [40.6622602, -73.952316],
                {}
            ).addTo(map_5f60191edd2c434941a980f7835a9d23);
        
    
            var icon_0db959f05d7ea34558f940fb62abee71 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "orange", "prefix": "glyphicon"}
            );
            marker_2f493ffcda28ee1cc9b71461f846f691.setIcon(icon_0db959f05d7ea34558f940fb62abee71);
        
    
        var popup_f2ba226ab310536d56b524d3b75e3c3a = L.popup({"maxWidth": "100%"});

        
            
                var html_71ced05edbaec802ffb757065058be42 = $(`<div id="html_71ced05edbaec802ffb757065058be42" style="width: 100.0%; height: 100.0%;">Street Name: Lefferts Ave<br>Family: Lefferts</div>`)[0];
                popup_f2ba226ab310536d56b524d3b75e3c3a.setContent(html_71ced05edbaec802ffb757065058be42);
            
        

        marker_2f493ffcda28ee1cc9b71461f846f691.bindPopup(popup_f2ba226ab310536d56b524d3b75e3c3a)
        ;

        
    
    
            var marker_cc31c247f6127f99987c2ccb4a41d8e1 = L.marker(
                [40.6420544, -73.9555352],
                {}
            ).addTo(map_5f60191edd2c434941a980f7835a9d23);
        
    
            var icon_4bffc8f6f08846a3092d4b27fa6b9b14 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "pink", "prefix": "glyphicon"}
            );
            marker_cc31c247f6127f99987c2ccb4a41d8e1.setIcon(icon_4bffc8f6f08846a3092d4b27fa6b9b14);
        
    
        var popup_232570276ab8d17f8945829b05506f36 = L.popup({"maxWidth": "100%"});

        
            
                var html_53ecb3299eca61ba6c64b498d330f760 = $(`<div id="html_53ecb3299eca61ba6c64b498d330f760" style="width: 100.0%; height: 100.0%;">Street Name: Vanderveer Pl<br>Family: Vanderveer</div>`)[0];
                popup_232570276ab8d17f8945829b05506f36.setContent(html_53ecb3299eca61ba6c64b498d330f760);
            
        

        marker_cc31c247f6127f99987c2ccb4a41d8e1.bindPopup(popup_232570276ab8d17f8945829b05506f36)
        ;

        
    
    
            var marker_1534217018e1fffa611724230353016b = L.marker(
                [40.6571323, -73.9247969],
                {}
            ).addTo(map_5f60191edd2c434941a980f7835a9d23);
        
    
            var icon_18e34406abba538543319287c97f3634 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_1534217018e1fffa611724230353016b.setIcon(icon_18e34406abba538543319287c97f3634);
        
    
        var popup_26713c611dd1be2832dc0ba626f3feda = L.popup({"maxWidth": "100%"});

        
            
                var html_03db8c68e96a4967bf97c88e4d496edd = $(`<div id="html_03db8c68e96a4967bf97c88e4d496edd" style="width: 100.0%; height: 100.0%;">Street Name: Remsen Ave<br>Family: Remsen</div>`)[0];
                popup_26713c611dd1be2832dc0ba626f3feda.setContent(html_03db8c68e96a4967bf97c88e4d496edd);
            
        

        marker_1534217018e1fffa611724230353016b.bindPopup(popup_26713c611dd1be2832dc0ba626f3feda)
        ;

        
    
    
            var marker_50a5e6c0bf60eeea31bf9a77486c3734 = L.marker(
                [40.6561492, -73.9381911],
                {}
            ).addTo(map_5f60191edd2c434941a980f7835a9d23);
        
    
            var icon_452ef19253d72f0a07351bb84267d865 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "gray", "prefix": "glyphicon"}
            );
            marker_50a5e6c0bf60eeea31bf9a77486c3734.setIcon(icon_452ef19253d72f0a07351bb84267d865);
        
    
        var popup_da6ad27c1e62bc3eba6aecff09fd83a5 = L.popup({"maxWidth": "100%"});

        
            
                var html_4d2e2d8e7f23b9ab00518e025440d6b3 = $(`<div id="html_4d2e2d8e7f23b9ab00518e025440d6b3" style="width: 100.0%; height: 100.0%;">Street Name: Clarkson Ave<br>Family: Clarkson</div>`)[0];
                popup_da6ad27c1e62bc3eba6aecff09fd83a5.setContent(html_4d2e2d8e7f23b9ab00518e025440d6b3);
            
        

        marker_50a5e6c0bf60eeea31bf9a77486c3734.bindPopup(popup_da6ad27c1e62bc3eba6aecff09fd83a5)
        ;

        
    
    
            var marker_6fd5de6eacf88c76c51ad0a247f973f6 = L.marker(
                [40.6443458, -73.9507203],
                {}
            ).addTo(map_5f60191edd2c434941a980f7835a9d23);
        
    
            var icon_244c4d9c581410c45c7e23b840370010 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "beige", "prefix": "glyphicon"}
            );
            marker_6fd5de6eacf88c76c51ad0a247f973f6.setIcon(icon_244c4d9c581410c45c7e23b840370010);
        
    
        var popup_239024f43ff9256e31a197600b6d5dcb = L.popup({"maxWidth": "100%"});

        
            
                var html_62f581f753fd13dd965417dcd2929884 = $(`<div id="html_62f581f753fd13dd965417dcd2929884" style="width: 100.0%; height: 100.0%;">Street Name: Cortelyou Rd<br>Family: Cortelyou</div>`)[0];
                popup_239024f43ff9256e31a197600b6d5dcb.setContent(html_62f581f753fd13dd965417dcd2929884);
            
        

        marker_6fd5de6eacf88c76c51ad0a247f973f6.bindPopup(popup_239024f43ff9256e31a197600b6d5dcb)
        ;

        
    
    
            var marker_3053d6361cd4fa5a5f44ade54f94e79d = L.marker(
                [40.6404325, -73.9562272],
                {}
            ).addTo(map_5f60191edd2c434941a980f7835a9d23);
        
    
            var icon_4988bae161036e0635372822e96618aa = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3053d6361cd4fa5a5f44ade54f94e79d.setIcon(icon_4988bae161036e0635372822e96618aa);
        
    
        var popup_e67476037f205a101ca40166b4a84a8e = L.popup({"maxWidth": "100%"});

        
            
                var html_f358dbc488bd8f26e9de71e518a1007a = $(`<div id="html_f358dbc488bd8f26e9de71e518a1007a" style="width: 100.0%; height: 100.0%;">Street Name: Ditmas Ave<br>Family: Ditmas</div>`)[0];
                popup_e67476037f205a101ca40166b4a84a8e.setContent(html_f358dbc488bd8f26e9de71e518a1007a);
            
        

        marker_3053d6361cd4fa5a5f44ade54f94e79d.bindPopup(popup_e67476037f205a101ca40166b4a84a8e)
        ;

        
    
</script>
</html>