# MSDS431Week4
# Linear Regression Comparison: Go, Python, and R

## Overview

This repository contains implementations of linear regression using three programming languages: Go, Python, and R. The goal is to demonstrate how to perform linear regression in each language and compare the results, including execution times. The datasets used are derived from the famous Anscombe's Quartet, which highlights the importance of data visualization and analysis.

## Contents

- **week4main.go**: Implementation of linear regression using the montannaflynn/stats library.
- **week4main_test.go**: Test file for week4main.go that calculations execution time for the linear regressions
- **pythonWeek4.py**: Implementation using the `statsmodels` library.
- **Rweek4.R**: Implementation using base R functions.
- **Datasets**: Data from Anscombe's Quartet.

## Datasets

The repository uses the four datasets from Anscombe's Quartet:

- Dataset I
- Dataset II
- Dataset III
- Dataset IV

## Execution from a bash terminal
- **Go**: go run week4maing.go
- **Python**: python pythonWeek4.py
- **R**: Rscript Rweek4.R

## Results
- I would not recommend using the montanaflynn/stats package in Go because it does not return the slope and y intercept like the python and R models. And these are the coefficients of interest when performing linear regression. Instad, the montanaflynn/stats LinearRegression function returns a series with the x coordinates and the y coordinates of the regression model. In terms of execution time, Python was the fastest. Due to its faster speed and model outputs, I would recomend the company use python.




