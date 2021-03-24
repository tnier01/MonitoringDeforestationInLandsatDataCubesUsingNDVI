# Monitoring Deforestation in Landsat Data Cubes Using NDVI

Deforestation of the rainforest, especially in Brazil, is a recurring topic in science and public. 
Illegal deforestation is often detected far too late to prevent it.
With this work we present a reproducible approach to detect deforestation in near real time by NDVI computation of satellite imagery. 
Using appropriately cloud-adjusted and deseasonalized reference data, critical NDVI changes were calculated for past deforestation events.
Taking these values and selecting an appropriate quantile for them above which an NDVI change is considered as critical, two satellite images can be examined for deforestation.

This application was developed as part of the class "Analysis of Spatio-Temporal Data" in the winterterm 2020/21 at [ifgi](https://www.uni-muenster.de/Geoinformatics/en/index.html) at the [University of Münster](https://www.uni-muenster.de/en/).
The corresponding paper describing the implementation can be found in the [main.html](https://github.com/tnier01/MonitoringDeforestationInLandsatDataCubesUsingNDVI/blob/main/main.html) and the corresponding ERC can be found [here](https://o2r.uni-muenster.de/#/erc/geQfc). The ERC is manipulable via the menu item *MANIPULATE*.  

