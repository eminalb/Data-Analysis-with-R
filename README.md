# Hitters Salary Analysis - README

## Overview
This project analyzes the relationship between baseball player statistics and their salaries using the **Hitters dataset**, which contains information on Major League Baseball players from the 1986 and 1987 seasons. The analysis focuses on predicting salary levels (**Low, Medium, High**) based on performance metrics, career statistics, and other relevant variables.

## Key Features
- **Data Preprocessing**: Handles missing values, detects outliers, and standardizes numeric predictors.
- **Exploratory Data Analysis**: Includes visualizations of distributions, correlations, and relationships between variables.
- **Multinomial Logistic Regression**: Predicts salary levels using performance metrics as predictors.
- **Model Evaluation**: Uses cross-validation and performance metrics (accuracy, precision, recall, F1-score) to assess model quality.
- **Multicollinearity Handling**: Addresses correlated predictors using Principal Component Analysis (PCA) and stepwise selection.
- **Comprehensive Reporting**: Detailed R Markdown document with visualizations, interpretations, and conclusions.

## Files
- `ProjectWork_GroupE.Rmd`: R Markdown file containing the full analysis, including code, visualizations, and explanations.
- `ProjectWork_GroupE.html`: HTML output of the R Markdown report.
- `ProjectWork_GroupE.pdf`: PDF version of the HTML report.
- `Hitters.csv`: Dataset used for the analysis.

## How to Use
1. Ensure you have **R** and **RStudio** installed.
2. Install the required R packages listed in the setup chunk of the R Markdown file.
3. Place `Hitters.csv` in your working directory.
4. Open `ProjectWork_GroupE.Rmd` in RStudio and **knit** the document to generate the HTML report.

## Dependencies
R packages:
- `dplyr`
- `ggplot2`
- `kableExtra`
- `corrplot`
- `reshape2`
- `psych`
- `DT`
- `gridExtra`
- `nnet`
- `caret`
- `car`
- `MASS`
- `tidyverse`

## Authors
- **Ege John Isik** (302991)  
- **Muhammet Emin Albayram** (303991)

