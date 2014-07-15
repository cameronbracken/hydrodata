hydrodata
=========

One stop shop for hydrologic data in R. Hydrologic data means any data involved in the water cycle so can include but is not limited to:

- Streamflow (natural and regulated)
- Precipitation (including snow)
- Soil 
- Climate
- Elevation
- Vegetation
- Dam/Reservoir Operations
- Basin Delineations
- Groundwater

This package aims to provide a unified interface for grabbing hydrologic data from the web. It solves the problem of data transmission and formatting but leaves the analysis, processing, and quality control to you. It is very similar in spirit to the Python package [ulmo](http://ulmo.readthedocs.org/en/latest/) but does things in an R-centric way. 

My wishlist at the moment is:

- NHD http://nhd.usgs.gov/
- WBD http://nhd.usgs.gov/wbd.html
- USGS flow http://waterdata.usgs.gov/nwis
- USGS geodata http://cida.usgs.gov/gdp/
- USGS gw data http://waterdata.usgs.gov/nwis/gw 
- HCDN 2009 (unimpared basins)
- GHCNd (daily met observations) http://www.ncdc.noaa.gov/oa/climate/ghcn-daily/
- CPC drought
- snotel (also part of ghcn)
- NDFD (climate forecasts)
- NID (dams)
- Natural flow data
- USBR water operations data
- USBR agrimet http://www.ncdc.noaa.gov/oa/climate/ghcn-daily/
- Army corps ops data
- CDEC http://cdec.water.ca.gov/index.html
