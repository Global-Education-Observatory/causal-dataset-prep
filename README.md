# imagery-prep

Process:
1. Sign up for Planet API
2. Download imagery tiles
3. Download OSM data (LINK)
4. For each imagery tile:
   a. Grab the school 1km bounding boxes that overlap it
   b. For each school bounding box:
       I. Clip all of the


To clean the GeoNames data:
1. Download the country file from here: https://download.geonames.org/export/dump/
2. Read into excel as a CSV and copy in column titles from link above
3. Subset to 



Folder Structure:

- osm
  |---phl
  |---bra
- tiles
  |---phl
  |---bra
- saved_imagery
  |---phl
  |---bra
- masks
  |---phl
  |---bra
