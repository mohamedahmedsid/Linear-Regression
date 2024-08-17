# Least Squares Regression Task

## Overview

This project applies least squares regression to fit a line to a dataset containing 100 pairs of values. The task involves calculating the best-fit line using least squares and evaluating the performance of the model using the coefficient of determination (R² score).

## Problem Statement

The dataset (`Linear-Regression.csv`) contains 100 pairs of values. The values in the first column are independent variable values (X), and the values in the second column are the corresponding dependent variable values (Y). The goal is to apply least squares regression to fit a line to this data and calculate the R² score to evaluate the model's performance.

## Methodology

### 1. Data Exploration
   - **Loading the Data**: Loaded the dataset into a Pandas DataFrame.
   - **Data Visualization**: Plotted the data points to visualize the relationship between the independent and dependent variables.

### 2. Least Squares Regression
   - **Fitting the Line**: Applied least squares regression using Python to find the best-fit line for the data.
   - **Plotting the Line**: Plotted the fitted line along with the data points on the same axes.

### 3. Model Evaluation
   - **Coefficient of Determination (R² Score)**: Calculated the R² score to evaluate how well the model explains the variance in the dependent variable.

## Results

- **Fitted Line**: The line was successfully fitted to the data using least squares regression.
- **R² Score**: The coefficient of determination for the fitted line is `0.9924`, indicating the proportion of variance in the dependent variable that is predictable from the independent variable.
