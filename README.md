# Lab 1
We have built a pipeline for predicting air quality (PM2.5) in Regensburg, Germany. The pipeline runs daily to fetch new air quality and weather data. Each sensor has a separate model. The feature groups, feature view and models are stored in Hopsworks. 

The historical data for each sensor was downloaded manually from [aqicn.org](https://aqicn.org) and a record of the sensor locations and URLs is stored in `sensors.json`. The data is preprocessed and stored in Hopsworks feature store using a Jupyter notebook. The models are trained using XGBoost in another notebook.

The dashboard is availible at [Air Quality Dashboard](https://www.sandlov.com/mlfs-book/air-quality/)

