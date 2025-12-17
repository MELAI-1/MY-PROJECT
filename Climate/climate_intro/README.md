
***

# Using Climate Data for Impact Assessment

This repository contains tutorial material on using climate data for investigating climate-related impacts.

It has been created for an **[Impact Lab](https://www.impactlab.org.uk/)** event targeted at SMEs in South West England, focusing on the business and economic impacts of climate change.

## Dataset Overview

The analysis primarily utilizes two major climate projection datasets:
*   **[CMIP6](https://www.wcrp-climate.org/wgcm-cmip/wgcm-cmip6):** The Coupled Model Intercomparison Project Phase 6 (Global climate projections).
*   **[UKCP18](https://www.metoffice.gov.uk/research/approach/collaboration/ukcp/index):** The UK Climate Projections 2018 (High-resolution data specific to the UK).

## Repository Contents

The tutorial is broken down into three step-by-step Jupyter Notebooks:

### [01_introduction_to_climate_change.ipynb](./01_introduction_to_climate_change.ipynb)
An introduction to the physical science of climate change. This notebook explores historical temperature trends and sets the context for why climate data analysis is necessary for modern businesses.

### [02_climate_data_and_impacts.ipynb](./02_climate_data_and_impacts.ipynb)
A technical guide on how to access and handle climate data. This notebook introduces the specific data structures of CMIP6 and UKCP18, demonstrating how to load, filter, and visualize raw climate model output using Python.

### [03_climate_change_impact-examples.ipynb](./03_climate_change_impact-examples.ipynb)
Applied examples relevant to South West England. This notebook takes the data processing skills learned in the previous steps and applies them to investigate potential economic and business impacts, such as extreme heat events, precipitation changes, or flooding risks.

## Prerequisites & Getting Started

The notebooks use standard Python data science tools for analysis and visualization (including `pandas`, `matplotlib`, and likely `xarray` for climate data).

If you are new to Python or need a refresher on the associated tools for data analysis, we recommend reviewing the tutorial material prepared for a previous Impact Lab event:
*   **Intro to Python for Data Analysis:** [https://github.com/informatics-lab/intro_python_data_analysis](https://github.com/informatics-lab/intro_python_data_analysis)

### Running the Material
To run these notebooks locally, ensure you have a Python environment set up with Jupyter installed.

```bash
# Example installation (if using pip)
pip install jupyter notebook pandas matplotlib xarray netCDF4

# Launch Jupyter
jupyter notebook
```