## NEARSHORE WAVE HEIGHT PREDICTION WITH MACHINE LEARNING

### MOTIVATION
The motivation for this project comes from my passion for surfing. Living in Hawaii for about seven years, I really got into surfing. As surfers we are always looking for the next good time to go surf. As such we check the surf forecast from websites such as magicseaweed, surfline etc... These professinal surf forecasting websites use complicated and complex hydrodynamic numerical models which requires extensive and indepth domina knowledge for implementation. My goal for this project is to explore machine learning as an alternative to these complex hydrodynamic models, to predict near shore wave heights using offshore buoy wave data. As such I went looking for data ...

### DATA
The main source of data for this project is National Data Buoy Center(NDBC) of US National Oceanic and Atmospheric Administration ([NOAA](http://www.ndbc.noaa.gov/)), which provides offshore wave data measurements for specific locations in the Pacific and Atlantic Ocean. NOAA keeps historic data for many buoy locations along the pacific ocean, together with real time data that comes in about every 15-20 minutes.

I used the NDBC API and gathared wave data from a number of buoys along the California coast and offshore in the Pacific Ocean.In order to get an idea of which buoys have the most complete data sets with minimal missing data I created a heat map whcih shows the percentage of missing data for each buoy. The figure below shows the heat map. Vertical axis shows the buoys and the horizontal axis shows some of the predictors that will be used to train/test the model. 

![Title](img/Figure_Percentage_Missing.png)

The figure above helped me in pin pointing a couple of buoys with which to move forward with the project. To this end, I chose Buoy 46059(A) and Buoy 46026(B). Figure below shows the location of these two buoys. Both are located off the coast of San Francisco shoreline.  Buoy A is located about 650 km off the coastline and buoy B is located close to Ocean Beach, a famous surf beach located along the  San Francisco shoreline. Figure below shows the location of the Beach. 

![Title](img/ocean_beach.png)

### DATA CLEANING AND PREPARING FOR TRAINING

![Title](img/ocean_beach.png)
















