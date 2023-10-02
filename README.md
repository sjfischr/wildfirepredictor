# Wildfire Predictor

## Business Problem Overview
Our team set out to develop an AI model that predicts the likelihood and spread of wildfires in a region. Specifically, this entails the following business problems:
- The likelihood of wildfire impacting a given property in a specific timeframe
- How prior wildfires data can serve as a feature for future predictions
- The extent to which excess vegetation surrounding a property influences the risk factors

## Datasets Researched
|# |Dataset Name | URL | Significance | Comments |
|----|----|----|----|----|
|1| National Interagecy Wildfire Data| https://data-nifc.opendata.arcgis.com/ | provides wildfire data, including historical fire perimeters and weather information| N/A |
|2| 1.88 Million US Wildfires |https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires | 24 years of geo-referenced wildfire records | N/A|
|3| USDA Wildfire Risk| https://www.fs.usda.gov/rds/archive/catalog/RDS-2016-0034-3 |Spatial datasets of probabilistic wildfire risk components for the United States (270m) (3rd Edition) Data publication contains GIS data| N/A|
|4| Normalized Difference Vegetation Index (NDVI)|https://www.earthdata.nasa.gov/learn/find-data/near-real-time/hazards-and-disasters/vegetation|NASA LANCE near real-time data can be used for monitoring vegetation and crop conditions.|N/A|
|5| USDA Vegscape|https://nassgeo.csiss.gmu.edu/VegScape/|VegScape is a geospatial data service which offers automated updates of vegetative condition at daily, weekly, and biweekly intervals. VegScape delivers interactive vegetation indices that enable quantification of U.S. crop conditions for exploring, visualizing, querying, and disseminating via interactive maps.|N/A|
|6| NASA North American Land Data Assimilation System (NLDAS-2)|https://catalog.data.gov/dataset/nldas-vic-land-surface-model-l4-monthly-0-125-x-0-125-degree-v002-nldas-vic0125-m-at-ges-d|This data set contains a series of land surface parameters simulated from the VIC land-surface model (LSM) for Phase 2 of the North American Land Data Assimilation System (NLDAS-2). The data are in 1/8th degree grid spacing and range from January 1979 to present. The temporal resolution is monthly.|N/A|
|7| US Forest Service Monitoring Trends in Burn Severity MTBS|https://catalog.data.gov/dataset/monitoring-trends-in-burn-severity-burned-area-boundaries-feature-layer-27201|The Monitoring Trends in Burn Severity MTBS project assesses the frequency, extent, and magnitude (size and severity) of all large wildland fires (includes wildfire, wildland fire use, and prescribed fire) in the conterminous United States (CONUS)|N/A|
