---
title: "Peer Assessment 1"
author: Nada Hossam
date: "24 February 2020"
output: 
  html_document:
    keep_md: true
---



```r
library(leaflet)
```

```
## Warning: package 'leaflet' was built under R version 3.6.2
```

```r
my_map <- leaflet() %>%
        addTiles

my_map <- my_map %>%
        addMarkers(lat=51.452437, lng=-0.298503,
                   popup="The Roebuck (Best view for drinking your pint in London)")
my_map
```

<!--html_preserve--><div id="htmlwidget-593140044638555abd12" style="width:672px;height:480px;" class="leaflet html-widget"></div>
<script type="application/json" data-for="htmlwidget-593140044638555abd12">{"x":{"options":{"crs":{"crsClass":"L.CRS.EPSG3857","code":null,"proj4def":null,"projectedBounds":null,"options":{}}},"calls":[{"method":"addTiles","args":["//{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",null,null,{"minZoom":0,"maxZoom":18,"tileSize":256,"subdomains":"abc","errorTileUrl":"","tms":false,"noWrap":false,"zoomOffset":0,"zoomReverse":false,"opacity":1,"zIndex":1,"detectRetina":false,"attribution":"&copy; <a href=\"http://openstreetmap.org\">OpenStreetMap<\/a> contributors, <a href=\"http://creativecommons.org/licenses/by-sa/2.0/\">CC-BY-SA<\/a>"}]},{"method":"addMarkers","args":[51.452437,-0.298503,null,null,null,{"interactive":true,"draggable":false,"keyboard":true,"title":"","alt":"","zIndexOffset":0,"opacity":1,"riseOnHover":false,"riseOffset":250},"The Roebuck (Best view for drinking your pint in London)",null,null,null,null,{"interactive":false,"permanent":false,"direction":"auto","opacity":1,"offset":[0,0],"textsize":"10px","textOnly":false,"className":"","sticky":true},null]}],"limits":{"lat":[51.452437,51.452437],"lng":[-0.298503,-0.298503]}},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->
