# Data Analysis

This folder contains the scripts, notebooks, and data related to my data analysis work.

## Data Sources

The data used in this analysis comes from the Emirates Mars Mission (EMM) and the Emirates Mars Infrared Spectrometer (EMIRS) instrument.  Specifically, we utilize Level 3 data products.  See `docs/data_sources.md` for more detailed information and links to the data.  In a broader sense, data sources can vary widely depending on the specific application, including experimental data, survey data, financial databases, and public datasets, all of which are encountered in scientific, business, and coursework contexts.

## Program: Seasonal & Temporal Analysis of Band Depth to search for Patterns 

The general workflow for this analysis is as follows:

1.  **Data Acquisition:** Download the required L3 data products from the EMM data archive.  This step corresponds to the process of obtaining data from various sources, a common starting point in any data analysis project.
2.  **Data Cleaning:** Use the scripts in `scripts/` (e.g., `data_cleaning.py`) to clean and filter the raw data.  This involves removing noise, handling missing values, and applying quality control measures.  Data cleaning is a fundamental step, as emphasized in data analysis coursework and practiced in scientific and business settings.
3.  **Band Depth Calculation:** Calculate the band depth using the `band_depth_calculation.py` script.  This step demonstrates the application of specific algorithms or formulas to extract relevant information from the data.
4.  **Analysis and Visualization:** Use the Jupyter Notebooks in `notebooks/` (e.g., `methane_analysis.ipynb`) to perform the main analysis. This includes:
    * Loading and processing the cleaned data.
    * Calculating relevant statistics.
    * Generating plots and visualizations to explore spatial and temporal patterns in the band depth.  This encompasses the core analytical techniques taught in data analysis courses and used in research and industry.
5.  **Result Interpretation:** Interpret the results of the analysis, draw conclusions about the presence or absence of methane signatures, and document the findings.  The ability to interpret results and communicate them effectively is a key skill developed in coursework and applied in scientific and business contexts.

