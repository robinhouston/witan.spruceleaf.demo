# Witan and Projections

### What is this?

I've been meaning to play with [Spruceleaf ](https://github.com/MastodonC/spruce-leaf) for a while, and one gig I'm working on seemed to a decent one to try it out on.

## TODO

- build the shapes (work out how to get geojson of London wards)
  - find shapefiles
  - find notes and refresh memory of half-remembered ogr2ogr and gdal commands
  - do the same for topojson and geojson
  - make a Makefile this time
  - use commands to make this stuff and PUT IT IN THE MAKEFILE
- find sample CSV file with data in correct shape
  - tidy up CSV if necessary
- dick about in atom and a browser

### Build the shapes

I got my hands on the layers from ONS.

I open ed it up in QGIS. It's not the prettiest app, but it was able to help me understand what I'm looking at.

```
ogrinfo -al -so ./data/GB/district_borough_unitary_ward_region.shp
```
