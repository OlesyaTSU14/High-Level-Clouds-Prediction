# High-Level Clouds Prediction
This study considers the possibility of detecting high-level clouds (HLCs) using machine learning methods based on the meteorological observations, ERA5 reanalysis and atmospheric lidar sensing data. 

1) Statistic_hypotesis: investigating the potential for integrated use of meteorological observations and LiDAR sensing data.

2) HLC_probabilities: Development of an ML model for predicting the presence or absence of HLCs..

### Dataset Features

[Copernicus Climate Data Store.](https://cds.climate.copernicus.eu) (Available online).  Feature altitude profiles. 
The dataset contains vertical profiles of meteorological parameters measured at various altitudes (from 0 to 14,000 meters with a 500-meter step). Annotation file is easy to use and contains some useful columns, see HLC_probabilities/era5_data.csv file, where:
* abs_humidity{altitude} — Absolute humidity at the specified altitude (g/m<sup>2</sup>).  
* rel_humidity{altitude} — Relative humidity at the specified altitude (%).
* pressure{altitude} — Atmospheric pressure at the specified altitude (hPa).
* wind_speed{altitude} — Wind speed at the specified altitude (m/s).
* wind_direction{altitude} — Wind direction at the specified altitude (degrees).
[Russian Research Institute of Hydrometeorological Information – World Data Centre (RIHMI–WDC).](http://meteo.ru) (Available online). Target variable: binary classification of HLCs cover, see HLC_probabilities/k_data.csv 
The dataset contains ground-based synoptic observations, including cloud types, coverage, and weather conditions recorded at specific time intervals. 
The model was evaluated using real experimental atmospheric sensing data as the control sample obtained from [High-Altitude Matrix Polarization Lidar.](https://ckp-rf.ru/catalog/usu/73573/) Target variable: binary classification of HLCs cover (Available upon request).  

#### Authors 
Maxim Penzin
Olesia kuchinskaia 
Ivan Akimov 
Denis Romanov


