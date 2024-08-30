# TANZANIAN WATER WELLS PROJECT

![image](https://github.com/user-attachments/assets/4b5fbbe5-73a9-4bf1-b5ad-a25c88292882)


## Introduction
This project aims to develop a predictive model that can accurately predict the functionality of water wells in Tanzania for each record in the dataset. The model will be used to guide resource allocation and improve access to clean water in Tanzanian communities.

## Dataset Information
The original data was obtained from the https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/23/ competition, which aggregates data from the Tanzania Ministry of Water. It is divided into three CSV files: a training set containing 59,400 observations (80%) and a test set containing 14,850 observations (20%).
The dataset used in this project is a collection of water well data from Tanzania, including features such as:

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

The dataset is available in CSV format.
The labels in this dataset are simple. There are three possible values:

- functional - the waterpoint is operational and there are no repairs needed
- functional needs repair - the waterpoint is operational, but needs repairs
- non functional - the waterpoint is not operational


## Contents
1. Business understanding
2. Data understanding
3. Data preparation
4. Exploratory data analysis
5. Data pre-processing
6. Modelling and evaluation
7. Conclusion
8. Future research

Metric: The primary metric used for evaluation was accuracy. 

The code includes the following steps:

- Data Understanding: The code starts by importing the necessary libraries and loading the dataset. It then explores the structure of the dataset, including the number of rows and columns, data types, and summary statistics.
- Data Preparation: The code prepares the dataset for modeling by removing unnecessary columns, handling missing values, and encoding categorical variables.
- Exploratory Data Analysis: The code performs exploratory data analysis to understand the relationships between the variables and the target variable.
- Data Preprocessing: The code preprocesses the data by creating dummies for categorical columns and performing a train-test split.
- Modeling and Evaluation: The code trains and evaluates three different models: K-Nearest Neighbors, Logistic Regression, and Decision Tree.

## Findings
The results of the models are as follows:

- K-Nearest Neighbors: The model has an accuracy of 68%.
- Logistic Regression: The model has an accuracy of 68%.
- Decision Tree: The model has an accuracy of 70%.

## Future research
- Feature engineering: Consider adding additional features that could be relevant to the problem.
- Hyperparameter tuning: Consider tuning the hyperparameters using techniques such as grid search or random search.
- Imbalanced data: Consider using techniques such as oversampling the minority class or undersampling the majority class to balance the dataset(SMOTE).
