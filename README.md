# Data Analysis

This folder contains the scripts, notebooks, and data related to my data analysis work.

## Data Sources

The data used in this analysis comes from the Emirates Mars Mission (EMM) and the Emirates Mars Infrared Spectrometer (EMIRS) instrument.  Specifically, we utilize Level 3 data products. We also use data from MARS models such as MCD (Mars Climate Database) for Surface Temperature, KRC for Thermal Inertia etc. 

## Program: Seasonal & Temporal Analysis of Band Depth to search for Patterns 

The general workflow for this analysis is as follows:

1.  **Data Acquisition:** Download the required L3 data products from the EMM data archive.  
2.  **Data Cleaning:** Clean and filter the raw data.  This involves removing noise, handling missing values, and applying quality control measures. 
3.  **Analysis and Visualization:** Use the Jupyter Notebook seasonal_temporal_analysis_BD_for_pattern.ipynb to perform the main analysis. This includes:
    * Loading and processing the cleaned data.
    * Calculating relevant statistics.
    * Generating plots and visualizations to explore spatial and temporal patterns in the band depth.  
5.  **Result Interpretation:** Interpret the results of the analysis, draw conclusions about the presence or absence of methane signatures, and document the findings.
   
## Program: Temporal Analysis of Temperature Difference between EMIRS and MCD (v6.1)

The general workflow for this analysis is as follows:

1.  **Data Acquisition:** Download the required L3 data products within the analysis period from the EMM data archive.  Feed this data to MCD to get and store the resultant output temperature in a csv. 
2.  **Analysis and Visualization:** Use the Jupyter Notebook - Temporal_Analysis_Temperature_Difference_EMIRS_MCD.ipynb to perform the main analysis. This includes:
    * Loading and processing the cleaned data.
    * Calculating relevant statistics.
    * Generating plots and visualizations to explore spatial and temporal patterns in the band depth.  
5.  **Result Interpretation:** Interpret the results of the analysis, draw conclusions about the presence or absence of methane signatures, and document the findings.  
