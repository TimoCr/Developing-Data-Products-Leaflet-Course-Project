---
title: "Rhinetower Düsseldorf"
date: "July 3, 2021"
output: 
  html_document:
    keep_md: yes
---


```r
library(leaflet)
```

```
## Warning: package 'leaflet' was built under R version 4.0.5
```

```r
map<-leaflet()%>%
  addTiles()
Rhinetower=addMarkers(map,lng=6.761680,lat=51.217942,popup="<a href='https://www.rheinturm.de/en'>Rhinetower Düsseldorf</a>")
Rhinetower
```

```{=html}
<div id="htmlwidget-ff00a2df9974c12e112e" style="width:672px;height:480px;" class="leaflet html-widget"></div>
<script type="application/json" data-for="htmlwidget-ff00a2df9974c12e112e">{"x":{"options":{"crs":{"crsClass":"L.CRS.EPSG3857","code":null,"proj4def":null,"projectedBounds":null,"options":{}}},"calls":[{"method":"addTiles","args":["//{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",null,null,{"minZoom":0,"maxZoom":18,"tileSize":256,"subdomains":"abc","errorTileUrl":"","tms":false,"noWrap":false,"zoomOffset":0,"zoomReverse":false,"opacity":1,"zIndex":1,"detectRetina":false,"attribution":"&copy; <a href=\"http://openstreetmap.org\">OpenStreetMap<\/a> contributors, <a href=\"http://creativecommons.org/licenses/by-sa/2.0/\">CC-BY-SA<\/a>"}]},{"method":"addMarkers","args":[51.217942,6.76168,null,null,null,{"interactive":true,"draggable":false,"keyboard":true,"title":"","alt":"","zIndexOffset":0,"opacity":1,"riseOnHover":false,"riseOffset":250},"<a href='https://www.rheinturm.de/en'>Rhinetower Düsseldorf<\/a>",null,null,null,null,{"interactive":false,"permanent":false,"direction":"auto","opacity":1,"offset":[0,0],"textsize":"10px","textOnly":false,"className":"","sticky":true},null]}],"limits":{"lat":[51.217942,51.217942],"lng":[6.76168,6.76168]}},"evals":[],"jsHooks":[]}</script>
```

