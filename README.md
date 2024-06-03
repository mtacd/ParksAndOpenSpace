# Converting Parks and Open Space
When downloading Parks and Open Space data from NYC, the data comes through as CSVs with geometry fields that can't be read by ArcGIS. This script converts the CSVs to readable shapefiles using GeoPandas, which can then be uploaded into ArcGIS for mapping.

### Datasources: 
[Parks and open space](https://data.cityofnewyork.us/City-Government/NYC-Planimetric-Database-Open-Space-Parks-/g84h-jbjm)

[Other kinds of open space](https://data.cityofnewyork.us/Recreation/NYC-Planimetric-Database-Open-Space-Other-/pckb-8r2z)