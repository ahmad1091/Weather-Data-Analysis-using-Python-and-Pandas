# Global Historical Climatology Network - Daily (GHCN-Daily) Data

This directory contains the Global Historical Climatology Network - Daily (GHCN-Daily) data set, which is maintained by the National Oceanic and Atmospheric Administration (NOAA) in the United States. The data set contains daily observations of temperature, precipitation, and other weather variables from stations around the world, dating back to the late 19th century.

## Data Source
The data set can be downloaded from the NOAA website. The full data set is quite large, but it can be downloaded in smaller chunks by selecting a specific range of years and/or regions of interest.

## Data Cleaning
The `data_cleaning.py` script in this directory can be used to clean and preprocess the data. This includes removing any missing or erroneous values, aggregating the data to monthly or yearly time scales, and calculating anomalies relative to a reference period. The cleaned data is saved as a CSV file in the `processed_data/` subdirectory.

## Data Analysis
The `data_analysis.py` script in this directory provides examples of how to analyze the cleaned data. This includes calculating global and regional temperature trends, identifying extreme weather events, and exploring correlations between weather patterns and other phenomena. The results are saved as visualizations in the `../visualizations/` subdirectory.
