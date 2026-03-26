Wildfire Analysis

If you want to reproduce this report, 
clone this repo
download the FPA-FOD SQLite file from the link in the report
open `final_report.Rmd` in RStudio
install whichever required packages if needed, should be outlined in the report as well

For the Midquarter Report:

This project looks at the spatial and temporal patterns of wildfires in the US, as the covariate I've also included a focus for 5 target states, CA, TX, GA, NV, and KS. 
The analysis is a combination of wildfire records and weather data to explore how environmental factors relate to fire frequency

Dataset:
Wildfire Data: 100k sample from the 1.88 mil wildfire;
Weather Data: NOAA station data 3 station per state (5 states);

Methods:
Lineplots, heatmaps, scatterplots, boxplots, violin plots
Bubble plot with the shiny package

For the Final Report:
This project develops a prediction model for notable wildfire incidence across the US using FPA-FOD dataset(1992–2015). Aim is to predict whether a notable wildfire (>=300 acres) will occur in a given 1° x 1° geographic grid cell in the following month, utilizing NOAA weather station data across five high-risk states as a covariate.

3 main models for the AUC:
Logistic Regression
LASSO Logistic Regression
Random Forest

Data:
The FPA-FOD SQLite database is too large to include in this repository. 
Download it from Kaggle: https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires

Weather Data: The link in the Final Report will not work
Instead, download from this link: https://drive.google.com/file/d/1pCM0DdP9ZgGO5PBgqhHnTrufAuzrJg5O/view?usp=sharing





