# Data-Scientist-Capstone
# Data Scientist Capstone: Turkey Earthquakes General Overview on Dataset

### Blog:
https://medium.com/@ibrahimal-khurayyif/turkeys-earthquake-awakening-unraveling-the-impact-of-seismic-events-from-1991-to-202-d4c864e4ed1c

## About Dataset Turkey Earthquake Dataset (1991-2023) Description:

This dataset contains information about earthquakes that occurred in Turkey from 1991 to 2023. The data includes the date and time of each earthquake, its magnitude, depth, and the latitude and longitude of the epicenter.

### Content:

Each row in the dataset represents a single earthquake event. The columns in the dataset are as follows:

- Time: The date and time of the earthquake.
- Magnitude: The magnitude of the earthquake on the Richter scale.
- Depth: The depth of the earthquake's epicenter in kilometers (will be converted to meters).
- Latitude: The latitude of the earthquake's epicenter.
- Longitude: The longitude of the earthquake's epicenter.

### Acknowledgements:

The data was collected from the USGS Earthquake Catalog API.

### Usage Policy:

This dataset is provided for educational and research purposes only. It should not be used for commercial purposes.

Source: [Turkey Earthquakes (1915-2023) | Kaggle](https://www.kaggle.com/datasets/atasaygin/turkey-earthquakes-1915-2023)

## About My Project

In this project, I will analyze seismic data from 1991 to 2023 to answer three questions:

1. Can a pattern be found for the largest seismic magnitude over the years?
2. Is the pattern of magnitudes constant or variable, and how does it appear?
3. Do the depths of the earthquake epicenters remain constant at a certain level or do they vary?

I have created special functions to calculate elevation, depth below sea level, and weights. These functions can be used to enhance the analysis.

- elevation_function: To calculate elevation values for geographic coordinates and add them to a DataFrame.
- depth_below_sea: To calculate depth of the earthquake's epicenter values below sea level and add them to a DataFrame.
-  weighit:: To calculate weights.

## Conclusions

In this project, I analyzed seismic data from 1991 to 2023 to answer three questions:

1. Can a pattern be found for the largest seismic magnitude over the years?
   - From the analysis, it does not appear that there is a pattern that can be traced from the seismic measurements for the largest magnitude each year.

2. Is the pattern of magnitudes constant or variable, and how does it appear?
   - From the analysis, we find that the weight of the magnitude suddenly increased in 2009 and became somewhat constant at a higher level.

3. Do the depths of the earthquake epicenters remain constant at a certain level or do they vary?
   - From the analysis, we find that the earthquake epicenter somewhat increases suddenly and specifically in the years 2009, 2014, 2019, and 2023. This may indicate the presence of a periodic pattern.
