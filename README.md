# PFAS_Project
#### This project involves the utilization of Random Forest Classifiers to assess the relationship between the presence of PFAS-handling industries and surrounding socioeconomic conditions in order to identify areas with high vulnerability to PFAS exposure and prioritize future testing accordingly. 
#### Files were transferred from a collaborative google drive folder

# File Directory
## scripts
### PFAS_Scraping_Script.ipynb 
#### Contains all code for collecting EJScreen socioeconomic data, PFAS manufacturer data, and PFAS testing location data.

### No_Pop_Socioeconomic_Maps.ipynb 
#### Contains all code for developing socioeconomic maps

### No_Pop_New_PFAS_Models.ipynb 
#### Contains all code for model development and deployment.

### Testing_Sites_Comparison_Script.ipynb
#### Contains all code for comparing testing sites and PFAS manufacturer data.

## preprocessing
### Contains most of the important datasets used throughout the projects

## final_data
### Contains final PFAS data with Random Forest predictions as well as a file containing the top 1000 cities that need testing based on model prediction confidence.

## scrapes
### Contains scrapes of EJScreen socioeconomic data around cities for specified indices (run scraping script to fill up this folder)

## analysis 1
### Contains US Maps with testing location data, PFAS manufacturer (industry) data, city PFAS data, binary city PFAS data, binary model prediction data, and binary model confusion matrix data.

## analysis 2
### Contains US Maps with socioeconomic data

## analysis 3
### Contains pearson correlation matrix and most of the analyses from Random Forest Classifier, including grid search data, a feature importance matrix, and partial dependence plots.

## analysis 4
### Contains polynomial regressions and analysis from SHAP visualizations of the Random Forest Classifier, including SHAP summary plots, SHAP value distributions, and SHAP decisions plots. 

## testing_locations_analysis
### Contains comparison between testing location data and PFAS manufacturer (industry) data throughout the US, shows why we used industry data for most analyses.

## Finalized_PFAS_Figures
### Contains all figures in png/csv/xlsx format from different versions of publication
