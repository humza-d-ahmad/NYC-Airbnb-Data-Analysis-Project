# Airbnb Dataset Analysis Project

## Overview

This project serves to conduct a general analysis of Airbnb data sourced from InsideAirbnb as well as 2 other datasets related to Crime or Income. We are looking to create models to predict estimated number of bookings and build a classification model for whether a host is a superhost. We also make use of Feature Engineering techniques in hopes of adding useful predictor variables using the non-numerical/non-categorical columns from the datasets. An example of this is using the text from airbnb reviews to create a average review sentiment metric for listings.

## Datasets

The InsideAirbnb was accessed at <https://insideairbnb.com/get-the-data/>  
The data used was from New York City for the months May through September, we used the `listings.csv` and `reviews.csv` datasets from each month for the purposes of the analysis.  
License for InsideAirbnb Data : [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/)

New York City Complaint Data
Sourced from the City of New York Open Data: https://opendata.cityofnewyork.us/ 

NYC Condo Rental Income Dataset
Soured from Kaggle: https://www.kaggle.com/datasets/jinbonnie/condominium-comparable-rental-income-in-nyc 


## Repository Index

`Final Project Report.pdf`: pdf version of final project report

`Datasets` : Directory containing the datasets, inside there is a sub-directory for each dataset, and a subset of reviews data is included for running the notebooks

`PreProcessingAirbnb.ipynb` : Notebook that serves to combine, clean and preprocess the `listings.csv` datasets from InsideAirbnb

`FeatureEngineeringAirbnb.ipynb`: Notebook that does Feature Engineering based on the text based columns (such as reviews & descriptions) as well as converting other columns (such as amenities & host verifications) to categorical variables  

`EdaAirbnb.ipynb` : Notebook for exploratory Data Analysis of the Airbnb Dataset   

`EdaCrime.ipynb`: Notebook for exploratory Data Analysis of the Crime dataset 

`EdaIncome.ipynb`: Notebook for exploratory Data Analysis of Income Dataset  

`SuperhostModeling.ipynb`: Notebook for classifiying superhost status  

`ModelingNumBookings.ipynb`: Notebook for regression on the number of bookings 

`airbnb_map.html`: Interactive Html version of the map from the Airbnb EDA

`crimema.html`: Interactive Html version of the map from the Crime EDA

`Slideshow_presentation.pdf`: pdf version of presentation slides
