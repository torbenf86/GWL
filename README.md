# GWL
Classification of European Weather Pattern (Hess and Brezowsky Grosswetterlagen) based on machine learning.

Prerequisites
---
Python with Scikit, Matlplotlib (including MPL Toolkits), NETCDF4, Numpy and Pygrib.

Visualization
----
tbd

Train
----
Scikit is used to train a SVM model. The labels are the 29 european weather patterns of Hess and Brezowsky Grosswetterlagen. The labels are taken from the German Meteorological Service (DWD), which provide a daily overview for the weather patterns over the past years: https://www.dwd.de/DE/leistungen/grosswetterlage/grosswetterlage.html

The sea-level pressure and the geopotential at 500 hpa were selected as features. These variables are taken from the NCEP reanalysis at each node between 40°W / 40°E and 20°N / 70°N, which can be found at https://www.esrl.noaa.gov/psd/data/gridded/data.ncep.reanalysis.pressure.html. All variables are flattened to feature vector. 10 % of the data is used as test data. 

Prediction
----
tbd

Literature
----
tbd
