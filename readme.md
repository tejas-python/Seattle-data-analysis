# Predict the power consumption of a building
Values Skills: Data pre-processing, descriptive statistics, Python

Skills: Regression methods, Prediction methods.
[web link](https://tejas-python.github.io/Seattle-data-analysis/)

# TASK

## You work for the city of Seattle. To achieve its goal of a carbon-neutral city in 2050, your team is taking a close interest in emissions from non-residential buildings. For this, careful records were made by your agents in 2015 and 2016.However, these surveys are expensive to obtain, and from those already done, you want to try to predict the emissions of buildings whoseemissionshave not yet been measured.Two measures interest you: CO2 emissions and total energy consumption. You also want to evaluate the interest in the emission prediction of the ENERGYSTAR Score(which is complicated to calculate)with the approach currently used by your team.
# PART A
## EDA
# Tech 
 Google colab -To perform Data analysis.
 # Installation or  Libraries
```bash
pip intsall pandas 
pip intsall matplotlib
pip3 install folium
pip install seaborn
pip install numpy
 ```
### Importing the libraries 
 ```python
 import pandas as pd
 import matplotlib.pyplot as plt
 import seaborn as sns
 import folium 
 import numpy as np
from folium import plugins
 ```
## Heat maps for 2015 and 2016 data
![heat map](./image/heat2015.png)

##### The above image gives the heat map for 2015 
![heat map](./image/heat2016.png)

##### The above image gives the heat map for 2016

## Bar plot comparision for 2015 and 2016 with respect to building type for GHE emmision
![bar plot](./image/bar2015.png)

## Bar plot comparision for 2015 and 2016 with respect to building type for GHE emmision intensity
![bar plot](./image/bar2016.png)

## Plotting on the world map using location 

* Following [plot](https://tejas-python.github.io/Seattle-data-analysis/maps/2015map.html) gives GHE emission with respect to location.

* Following
[plot](https://tejas-python.github.io/Seattle-data-analysis/maps/2015heatmap.html) gives GHE emission heat map with respect to Seatle.

* Following [plot](https://tejas-python.github.io/Seattle-data-analysis/maps/2016map.html) gives GHE emission with respect to location.

* Following
[plot](https://tejas-python.github.io/Seattle-data-analysis/maps/2016heatmap.html) gives GHE emission heat map with respect to Seatle.

colour value for 'GHGEmissions(MetricTonsCO2e)' in world map 
* Green -  GHE emission< 10
* lightgreen - 10<GHE emission>20
* pink - 20<GHE emission>30
*  black - 30<GHE emission>40
* purple - 40<GHE emission>50
* grey - 50<GHE emission>100
* brown - 100<GHE emission>150
* yellow - 150<GHE emission>200
* lightblue - 200<GHE emission>250
* dark blue- 250<GHE emission>500
* orange - 500<GHE emission>1000
* red - GHE emission>1000
## Google colab link 
[link](https://github.com/tejas-python/Seattle-data-analysis/blob/master/partA/colab_file.ipynb)

[download](https://tejas-python.github.io/partA/colab_file.ipynb)
## Links
[Data](https://www.kaggle.com/city-of-seattle/sea-building-energy-benchmarking#2015-building-energy-benchmarking.csv)
