# Radar-Vegetation-Index-S1
Project Title:
Sentinel-1 Data Processing and Analysis with Google Earth Engine

Description:
This project focuses on processing Sentinel-1 Ground Range Detected (GRD) data using Google Earth Engine (GEE). It includes steps for filtering, preprocessing (https://github.com/adugnag/gee_s1_ard), calculating the Ratio Vegetation Index (RVI), and generating a time series chart for vegetation analysis.

Code Overview:
The code script processes Sentinel-1 GRD data, applies speckle filtering, and calculates the RVI for vegetation assessment. It also generates a time series chart to visualize the RVI values over a specified region.

Dependencies:
1. Google Earth Engine API
2. 'users/adugnagirma/gee_s1_ard:wrapper' module

Instructions:
Ensure you have access to Google Earth Engine.
Copy and paste the provided code into the GEE Code Editor.
Modify parameters as needed (e.g., date range, region of interest).
Run the script to preprocess Sentinel-1 data, calculate RVI, and generate the time series chart.

Data Sources:
Sentinel-1 GRD data from COPERNICUS/S1_GRD collection
Digital Elevation Model (DEM) from USGS/SRTMGL1_003

Results:
The script outputs preprocessed Sentinel-1 data, RVI values, and a time series chart showing vegetation dynamics over time.

Contributing:
Feel free to contribute by suggesting improvements, reporting issues, or adding new features. 
