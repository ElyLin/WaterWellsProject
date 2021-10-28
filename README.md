# WaterWellsProject

## Project Overview
This project contains our steps to solving a data science predictive modeling classification problem, which is the Tanzanian water well access limitations. Our goal was to create a highly accurate predictive model to determine which water wells in Tanzania require repairs.

## Data Overview
This is a competition from Driven Data, Pump it up: Data Mining the water table. We obtained our data set from the Driven Data competition, originally sourced from the Tanzanian Ministry of Water and supplied by Taarifa. Our objective is to build a model that predict if the pump is functional or non functional or functional need repair. The data consist of 59,400 rows and 30 categorical columns and 10 numerical columns. we will be working with most of the data given.

The data schema is as follows:

- status_group - tells us the status of each pump.
- amount_tsh - Total static head (amount water available to waterpoint)
- date_recorded - The date the row was entered
- funder - Who funded the well
- gps_height - Altitude of the well
- installer - Organization that installed the well
- longitude - GPS coordinate
- latitude - GPS coordinate
- wpt_name - Name of the waterpoint if there is one
- num_private -
- basin - Geographic water basin
- subvillage - Geographic location
- region - Geographic location
- region_code - Geographic location (coded)
- district_code - Geographic location (coded)
- lga - Geographic location
- ward - Geographic location
- population - Population around the well
- public_meeting - True/False
- recorded_by - Group entering this row of data
- scheme_management - Who operates the waterpoint
- scheme_name - Who operates the waterpoint
- permit - If the waterpoint is permitted
- construction_year - Year the waterpoint was constructed
- extraction_type - The kind of extraction the waterpoint uses
- extraction_type_group - The kind of extraction the waterpoint uses
- extraction_type_class - The kind of extraction the waterpoint uses
- management - How the waterpoint is managed
- management_group - How the waterpoint is managed
- payment - What the water costs
- payment_type - What the water costs
- water_quality - The quality of the water
- quality_group - The quality of the water
- quantity - The quantity of water
- quantity_group - The quantity of water
- source - The source of the water
- source_type - The source of the water
- source_class - The source of the water
- waterpoint_type - The kind of waterpoint
- waterpoint_type_group - The kind of waterpoint

## Methodology
The methodology we used for building the model are:
- Logistic Regression
- Knn nearest neighbor
- Decision Tree Classifier
- Random Forest Classifier
- CatBoost Classifier

## Project Result
Category Catboost Model predict an accuracy score of 80% on the holdout data.

## Next Steps
- Address relationship between the features
- Identify improvement opportunity
- optimize for maintenance cost by clustering

## Repository Navigation
- Data
- Notebook
- Presentation
- Readme

## AUthors
- Ely Lin
- Samantha Nasti
- Titilayo Amuwo
