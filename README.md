# World Wide Water - Predicting Well Functionality in Tanzania for UNICEF

World Wide Water analyzed thousands of water wells in Tanzania to find what attributes influence well failure the most. With our analysis, stakeholders like UNICEF, can gain better understanding about Tanzania's ongoing water crisis. 

## Organizational Objective
As it stands, much of the Tanzanian population lacks a basic access to consumable water. Many Tanzanian citizens collect water from groundwater sources or turn to private lenders to meet their needs. However, both options are risky and endanger consumers to illnesses like cholera and malaria. It is imperative for those who seek to improve water access in Tanzania to understand what factors are most influential in water well failure.

## Main Findings
We analyzed over fifty-four thousand water wells built between 1960-2013. We found three features that powerfully impact the functionality of water wells: 
1. Age of Well
2. Location of Well
3. Water Extraction Method

Our final model garnered a recall score of 78%, displaying a powerful ability to correctly categorize functional vs. non-functional wells.

## The Notebooks
The technical lead operated out of the mackoy branch, while technical associates assisted through pair programming. The main files for this project are in main_notebook.ipynb. 

## Data Cleaning
The dataset, tanzania_wells.csv, was the primary source of data used for this project. The dataset contained comprehensive information including but not limited to water quantity, latitude, longitude, donor information, population metrics, and extraction type. We featured engineered information for the age of the well. After a robust data cleaning effort and initial statistical analysis, the team modeled the data.

## Model Analysis
### EDA
The first analysis concerns the relationship between the percentage of non-functional water wells and the age of the respective water well.
