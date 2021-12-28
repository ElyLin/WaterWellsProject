# WaterWellsProject
![Water pump](https://static.wikia.nocookie.net/dayz_gamepedia/images/2/29/WaterPump_Blue_1a.png/revision/latest/scale-to-width-down/1000?cb=20200902182842)

## Project Overview
This project contains our steps to solving a data science predictive classification problem, which is the Tanzanian water well access limitations. Our main goal was to create a highly accurate predictive model to determine which water wells in Tanzania require repairs.

## Data Overview
We obtained our data set from the Driven Data competition, originally sourced from the Tanzanian Ministry of Water and supplied by Taarifa. Our objective is to build a model that predict if the pump is functional or non functional or functional need repair. The data consist of 59,400 rows, 30 categorical columns and 10 numerical columns. we will be working with most of the data given and drop the redundant information.

## Methodology
The methodology we used for building the model are:
- Logistic Regression
- Knn nearest neighbor
- Decision Tree Classifier
- Random Forest Classifier
- CatBoost Classifier

## Project Result
Category Catboost Model predict an accuracy score of 80% on the holdout data. The model can be use to locate water wells that need repairs and determine the high risk area.

## Next Steps
- Explore features and trends
- Identify improvement opportunity
- Optimize for maintenance cost by clustering

## Repository Navigation
- Data
- Notebook
- WaterWellsProjectNotebook
- Presentation
- Readme

## Authors
- Ely Lin
- Samantha Nasti
- Titilayo Amuwo
