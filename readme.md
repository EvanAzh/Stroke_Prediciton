## README

<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="https://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""></a></p>

Healthcare Stroke Prediction Analysis

Overview
This project analyzes healthcare data to predict stroke occurrences using logistic regression and Generalized Additive Models (GAMs). The analysis includes data cleaning, exploratory data analysis (EDA), and model development.

Team Members
Patricia Fonseca Gomes
Ngoc Uyen Phung
Renzo Rauschenberg
Evan Brahma Hughie Azhabur

Project Structure

1. Loading Packages and Data
Libraries: ISLR2, dplyr, ggplot2, splines, gam, PRROC
Data: healthcare-dataset-stroke-data.csv

2. Data Structure and Cleaning
Inspect data dimensions and structure
Convert columns to factors and handle missing values in bmi
Remove irrelevant columns and filter out non-binary gender data

3. Exploratory Data Analysis (EDA)
Provide descriptive statistics and visualizations
Plot distributions and relationships for variables like BMI, glucose level, age, and stroke status

4. Model Preparation
Split data into training (80%) and test (20%) sets

5. Classical Logistic Regression
Develop logistic regression models
Evaluate models using AIC, accuracy, sensitivity, specificity, precision, and recall
Use ROC curve analysis to determine optimal thresholds

6. Generalized Additive Models (GAM)
Build a GAM for stroke prediction
Compare performance with logistic regression using AIC
Visualize smooth terms for continuous predictors
Evaluate predictive power using precision-recall curves

Key Findings
Significant predictors for stroke: age, hypertension, and average glucose level
Preferred logistic regression model based on AIC values
Various thresholds tested to balance sensitivity and specificity, aiming for high recall 

Usage
Ensure the necessary packages are installed in R.
Run the script from start to end for data loading, cleaning, EDA, and model evaluation.

Future Work
Further tuning and validation using cross-validation
Exploration of additional predictive modeling techniques

Contact
For questions or contributions, contact the project members or open an issue on this repository.
email me: evanbrahmabrahma@gmail.com