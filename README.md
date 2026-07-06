# Long-term Pan-Arctic Snowmelt Timing Analysis (1988–2022)

## Project Overview

This repository contains the analysis codes used in our study on long-term snowmelt timing over the Pan-Arctic region (north of 60°N) using passive microwave satellite observations.

The main objectives of this study are:

1. To develop a passive microwave-based snowmelt timing dataset by estimating three snowmelt metrics from brightness temperature (Tb):
   - Melt Onset Date (MOD)
   - Melt End Date (MED)
   - Melt Duration (MD)

2. To evaluate the proposed snowmelt timing products by comparing them with existing snowmelt timing datasets over the 1988–2022 period and identifying their strengths and limitations.

3. To investigate long-term changes in snowmelt timing across the Pan-Arctic over the past 35 years and examine their relationships with post-snowmelt vegetation phenology using NDVI.

4. To identify the environmental factors associated with snowmelt timing through statistical and machine-learning analyses.

---

## Repository Structure

Each folder contains codes for a specific stage of the analysis. Detailed descriptions of each folder and script are provided below.

---

## Requirements

Most preprocessing and analysis scripts rely on the HydroAI repository developed by our research group. Before running the codes in this repository, please clone the HydroAI repository:

https://github.com/Hyunglok-Kim/HydroAI

Some scripts also require additional Python packages, including NumPy, SciPy, xarray, netCDF4, scikit-learn, Cartopy, and SHAP.
