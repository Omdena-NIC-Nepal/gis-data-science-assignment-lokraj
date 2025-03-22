### Objective:
- The goal of this assignment is to assess GIS Data Science skills by analyzing climate data for Nepal. This involves reading, visualizing, and exploring GIS-based climate datasets using Python. The analysis will focus on temperature, precipitation, and other climate variables to identify trends and patterns over time and across different regions.

#### Environment Setup

##### Step 1: install python and anaconda
##### Step 2: install required libraries
- pip install jupyter pandas geopandas matplotlib seaborn folium ipywidgets


If using JupyterLab, install:
- pip install jupyterlab

##### Step 3: clone the project

- git clone git@github.com:Omdena-NIC-Nepal/gis-data-science-assignment-lokraj.git



### Data sources and preprocessing steps
#### Data Sources
The climate data used in this project is sourced from publicly available datasets and repositories. Below are the primary sources:



Dataset from: Nepal_Climate_Change
https://opendatanepal.com/dataset/district-wise-daily-climate-data-for-nepal/resource/39cd1c13-2051-4d4c-9ea3-ba8106833166

This dataset contain climate data for districts of Nepal at monthly interval

Date: 1981-01-01 to 2019-12-31

No of Rows: 29016

No of Columns: 24

Interval: Monthly

No of Parameters: 18


#### Data Preprocessing Steps
Once the data was collected, the following preprocessing steps were performed:

1: Load the Climate Data
2:  Check for missing values
3: Fill missing values with column mean
4: Ensure Correct Data Types
