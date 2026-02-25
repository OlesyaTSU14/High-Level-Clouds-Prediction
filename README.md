# High-Level Clouds Prediction
This study considers the possibility of detecting high-level clouds (HLCs) using machine learning methods based on the meteorological observations, ERA5 reanalysis and atmospheric lidar sensing data. 

### Data

Annotation file is easy to use and contains some useful columns, see _____.csv file:  

* Temperature
* Absolute humidity
* Relative humidity
* Pressure
* Wind speed
* Wind direction

***Data Source:***  
[Russian Research Institute of Hydrometeorological Information – World Data Centre (RIHMI–WDC).](http://meteo.ru) Target variable: binary classification of HLCs cover (Available online).  
[Copernicus Climate Data Store.](https://cds.climate.copernicus.eu) Feature altitude profiles (Available online).  
The model was evaluated using real experimental atmospheric sensing data as the control sample obtained from [High-Altitude Matrix Polarization Lidar.](https://ckp-rf.ru/catalog/usu/73573/) Target variable: binary classification of HLCs cover (Available upon request).  








### Models



#### Authors 

[1] Russian Research Institute of Hydrometeorological Information – World Data Centre (RIHMI–WDC). Main meteorological parameters. Available at: meteo.ru/data/basic-parameters

