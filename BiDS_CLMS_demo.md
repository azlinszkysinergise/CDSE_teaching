***https://tinyurl.com/CLMSBiDS***

Demo:

- CLMS website https://land.copernicus.eu/en
- CDSE Blog Post https://dataspace.copernicus.eu/cases/straight-point-copernicus-land-monitoring-services-data
- Copernicus Browser: https://browser.dataspace.copernicus.eu/

- Global land cover: https://link.dataspace.copernicus.eu/d9lj
- Soil moisture, la Rioja, Spain: https://link.dataspace.copernicus.eu/f6nu (outline {"type":"Polygon","coordinates":[[[-1.659333,42.329108],[-1.950394,42.461967],[-2.246946,42.593533],[-2.624501,42.586455],[-2.982835,42.616781],[-3.03226,42.440688],[-2.785133,42.433593],[-2.760421,42.532844],[-2.532515,42.470071],[-2.509175,42.311847],[-2.186537,42.212245],[-1.806236,42.106374],[-1.659333,42.329108]]]})

- Snow cover https://link.dataspace.copernicus.eu/rt5d (add data from 09.28)
- LST Riga, 21 July, with custom evalscript and hour setting https://link.dataspace.copernicus.eu/nmli
- FAPAR, LAI, NDVI, NPP
- Productivity and seasonality indices - australia https://link.dataspace.copernicus.eu/qup9
- Water quality - timelapse https://link.dataspace.copernicus.eu/pf77

- Configuration / OGC: https://shapps.dataspace.copernicus.eu/dashboard/#/configurations
- Requests builder: https://shapps.dataspace.copernicus.eu/requests-builder/
  - First, LOG IN
  - BYOC ID here: https://documentation.dataspace.copernicus.eu/APIs/SentinelHub/Data/clms/bio-geophysical-parameters/temperature-and-reflectance/land-surface-temperature/lst_global_5km_hourly_v2.html
  - Evalscript here: https://github.com/azlinszkysinergise/customscripts_test_az/blob/main/lst_celsius_for_stat.js
  - Bounding box POLYGON ((23.348554 56.419978,25.107359 56.419978,25.107359 57.124314,23.348554 57.124314,23.348554 56.419978))
- Jupyter https://github.com/eu-cdse/notebook-samples/blob/main/sentinelhub/BIDs_2025_multitemporal_analysis_CLMS_data.ipynb
