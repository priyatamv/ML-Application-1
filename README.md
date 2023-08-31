# What drives the price of a car

This data study examines a vehicle dataset and derives the features that influence the price of a car

## Description

The objective of the dataset is to comprehend the variables that impact the pricing of a car and to construct recommendation models.

## Scope

Analyze various features within the car dataset that influence the price of the car.

## Getting Started

### Dependencies

* Juypyter note book.

### Analysis

#### Data Exploration

Part of data exploration the following activities has been done.
* Checking for missing Values
* Checking Zero values
* Checking Unique Values
* Check Unique Identifiers
* Check for Duplicate Records
* Check for outliers
#### Data visualziation
* Explored data visually for various features using histograms
   ![image info](images/histogram.png)
* Plot outliers
#### Data Preparation
  ##### Data Cleaning
      * Drop Missing Year and Odometer values
      * Remove Duplicate Values
      * Remove outliers
      * Flag Outliers Based on Thresholds
      * Remove outliers based on IQR
      * Remove outliers based on thresholds
      * Fill Categorical Missing Values
 ##### Data Encoding           
      * Ordinal Encoding
      * One-Hot Encoding
##### Data Correlation          
    * Finding correlation of features
    * Visualize Correlation matrix
    * Top 20 positive and negative correlation features
##### Feature Selection]
    * RandomForestRegressor
    * RFE
##### PCA           
    * PCA analysis on the features what were found by RFE
    * RFE
##### Modeling
	* Creating datasets for modeling
	* Model-Iteration 1:Dataset no outliers and cleaned data
        * LinearRegression
        * LinearRegression With PolynomialFeatures
        * LinearRegression With PolynomialFeatures and Ridge
	* Model-Iteration 2: Encoded data with top co-related features
        * LinearRegression
  * Model-Iteration 3: Encoded-data-with-top-co-related-feature-with-PCA
        * LinearRegression
##### Evaluation
    * Using hyperparameters to the models
    * Cross validation on the Linear models
#### Summary of Regression Model Evaluations


#### Next Steps and Recommendations
## Link to notebook

https://github.com/priyatamv/ML-Application-1/blob/main/prompt_II.ipynb

## Authors

Priyatam Veyyakula

## Version History

* 0.1
    * Initial Release

