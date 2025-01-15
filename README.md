# urban_seismic

## place Points on Line

- Select single Line object 
- Enter starting number for the label of the points
- Enter point spacing in m
- Enter number increment
- Enter a shift from the start of the line (e.g first point not at the start of the line but shifted along the line)
- Enter filename for generated shp file and crs
- load points in your QGIS canvas

  ## project points onto multiline
  - Select points object
  - Select Multiline object
  - Define max distance for projection
  - Define step for search (distance in m)
  - Define threshold for distance between projected point and Multiline (distance less than threshold then projected point is good)
  - Entre filename for generated shp file and crs
  - load points in QGIS canvas
 
  ## calculate cmp
  - select source points
  - select receiver points
  - enter max offset
  - enter filename for generated shp file and crs
  - load points in QGIS canvas
 
  ## export csv for Stryde
  - select points for sources
  - select code for source
  - select number shots per point
  - enter filename for csv

  
