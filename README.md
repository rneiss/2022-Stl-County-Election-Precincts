# 2022-Stl-County-Election-Precincts

Shapefiles for St. Louis County Missouri's Election Precincts. GeoJSON data extracted from: https://stlouiscovotes.maps.arcgis.com/apps/instant/lookup/index.html?appid=bac4fce0c3854e9aaa84e1fb10b8ecd2

Converted to SHP files with `ogr2ogr -f "ESRI Shapefile" stl_county_elex_precincts.shp "query.json"`
