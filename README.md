# Bayesian Missing Data - Multiple Imputation Methods

## Overview
This project, presented at California State University Fullerton for Math 538 Fall 2023, explores the application of Bayesian methods in handling missing data through multiple imputation techniques. Authored by Paul Lopez and Emilio Vasquez, this work addresses a common dilemma in data science: managing missing data in datasets.

## Purpose
The primary goal of this project is to demonstrate a principled approach to handling missing data using Bayesian multiple imputation methods. It specifically targets scenarios common in finance, healthcare, and social sciences, where ignoring or eliminating missing values can lead to skewed results and invalid statistical inferences.

## Methodology
The approach taken involves the creation of multiple complete datasets from incomplete ones, where missing values are imputed using simulated draws from an appropriate model. The project encompasses:

- An exploration of missing data types (MCAR, MAR, MNAR) and their implications.
- The construction of a Bayesian regression model, including the setting of priors and fitting the model using Markov chain Monte Carlo (MCMC) methods.
- The practical application of the model to a time-series dataset of AAPL stock prices, including data acquisition, exploratory data analysis, data amputation, and imputation.

## Key Features
- **Bayesian Framework:** Utilizes a Bayesian approach for multiple imputation, offering flexibility in handling missing data and representing imputation uncertainty.
- **Comprehensive Analysis:** Includes exploratory data analysis, Bayesian regression modeling, and the combination of model results to address missing data in a financial dataset.
- **Real-world Application:** Demonstrates the methodology using AAPL stock price data, providing a relevant and practical example of the model's application in a real-world context.

## Results
The project successfully applies Bayesian regression models to impute missing data in a financial time-series dataset. The findings underscore the effectiveness of Bayesian multiple imputation in dealing with missing data, while accounting for uncertainty and leveraging flexible modeling techniques.

## Conclusion
The study concludes that Bayesian multiple imputation is a robust method for handling missing data in diverse fields, particularly where the accuracy and reliability of statistical inferences are critical.

## References
A comprehensive list of references is provided in the project document, supporting the methodology and conclusions drawn.
