# Exploratory Data Analysis and Linear Regression on Body Performance Data (Bio-Statistics)

## Introduction
This project involves the analysis of a dataset containing information about body performance metrics of individuals. The dataset includes various physical attributes like age, gender, height, weight, body fat percentage, blood pressure, grip strength, and performance in physical tests such as sit-ups and broad jump. The goal of this project is to perform exploratory data analysis (EDA) to gain insights into the data and build linear regression models to predict physical performance based on selected attributes.

## Dataset
The dataset used in this project is named 'bodyPerformance.csv.' It consists of the following columns:

age: Age of the individual.
gender: Gender of the individual (M for male, F for female).
height_cm: Height in centimeters.
weight_kg: Weight in kilograms.
body fat_%: Percentage of body fat.
diastolic: Diastolic blood pressure.
systolic: Systolic blood pressure.
gripForce: Grip strength in newtons.
sit and bend forward_cm: Measurement of the ability to sit and bend forward in centimeters.
sit-ups counts: Number of sit-ups performed.
broad jump_cm: Distance of broad jump in centimeters.
class: A categorical variable indicating different classes.

## Project Tasks

1. Data Loading and Exploration
Load the dataset into a Pandas DataFrame.
Examine the structure of the dataset using .info() and .describe().
Identify the data types of each column.
Check for missing values and handle them if necessary.

3. Summary Statistics and Data Distributions
Calculate summary statistics such as mean, median, mode, variance, standard deviation, skewness for selected numeric columns like 'body fat_%,' 'height_cm,' and 'weight_kg.'
Visualize the data distributions using histograms, density plots, and box plots.
Explore relationships between variables, especially between physical attributes and performance metrics.

4. Linear Regression Modeling
3.1 Predicting 'sit-ups counts'
Prepare the data by selecting relevant features (independent variables) and the target variable ('sit-ups counts').
Split the dataset into training and testing sets.
Build a linear regression model to predict 'sit-ups counts' based on attributes like height, weight, and body fat percentage.
Evaluate the model's performance using metrics like R-squared, F-statistic, and p-values.
Visualize the regression results using scatter plots.
3.2 Predicting 'broad jump_cm'
Repeat the same steps as in 3.1 but this time predict 'broad jump_cm' based on selected attributes.
Assess the performance of the second linear regression model.

5. Data Visualization
Create meaningful visualizations to illustrate relationships between variables, for example, pair plots with regression lines, box plots, and density plots.
Explore how gender and class affect body performance metrics.

6. Conclusion and Insights
Summarize the key findings and insights from the EDA and regression analysis.
Discuss the practical implications of the results and how they can be used to better understand body performance metrics.
