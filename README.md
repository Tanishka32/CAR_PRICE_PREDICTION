# CAR_PRICE_PREDICTION

![Car](https://user-images.githubusercontent.com/118731707/226593398-b5d5465b-9a52-4e0a-a518-536bca3804ca.PNG)

Problem Statment

How do you evaluate the apt Price for a second hand car?

You look at the number of years, the type of fuel, how many KMS it has run etc.

In this case study, your task is to create a machine learning model which can predict the Price of a car based on its specs.

In below case study I will discuss the step by step approach to create a Machine Learning predictive model in such scenarios.

Flow of the case study is as below:

Reading the data in python

Defining the problem statement

Identifying the Target variable

Looking at the distribution of Target variable

Basic Data exploration

Rejecting useless columns

Visual Exploratory Data Analysis for data distribution (Histogram and Barcharts)

Feature Selection based on data distribution

Outlier treatment

Missing Values treatment

Visual correlation analysis

Statistical correlation analysis (Feature Selection)

Converting data to numeric for ML

Sampling and K-fold cross validation

Trying multiple Regression algorithms

Selecting the best Model

Reading the data into python

The data has one file "CarPricesData.csv". This file contains 1435 car prices data.

You can download the data required for this case study here

Data description

The business meaning of each column in the data is as below

Defining the problem statement:

Create a ML model which can predict the apt Price of a computer

Target Variable: Price
Predictors: Age, KM, FuelType, CC etc.

Price: The Price of the car in dollars

Age: The age of the car in months

KM: How many KMS did the car was used

FuelType: Petrol/Diesel/CNG car

HP: Horse power of the car

MetColor: Whether car has metallic color or not

Automatic: Whether car has automatic transmission or not

CC: The engine size of the car

Doors: The number of doors in the car

Weight: The weight of the car
