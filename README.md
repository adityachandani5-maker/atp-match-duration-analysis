# ATP Match Duration and Ace Performance Analysis

This project analyzes 2024 ATP tennis match data to study match duration and winner ace performance using statistical learning methods in R.

## Overview

The project focuses on two main questions:

1. Can ATP match duration be predicted using player, match, and tournament variables?
2. Can winner ace performance be classified as high or low based on player and match characteristics?

The analysis uses regression and classification techniques to explore patterns in professional tennis match data and compare model performance.

## Methods Used

### Regression

- Multiple Linear Regression
- Backward stepwise selection
- K-Nearest Neighbors Regression
- Training and test error comparison

### Classification

- Logistic Regression
- Quadratic Discriminant Analysis
- 10-fold cross-validation
- Confusion matrix and accuracy comparison

## Tools Used

- R
- R Markdown
- tidyverse
- ggplot2
- caret
- FNN
- MASS
- knitr

## Dataset

The dataset comes from Jeff Sackmann's Tennis ATP match results database and uses 2024 ATP match data.

Dataset source:  
https://github.com/JeffSackmann/tennis_atp

## Key Results

- Multiple Linear Regression explained approximately 31% of the variation in match duration.
- KNN regression performed best around K = 16.
- Multiple Linear Regression had slightly better test error than KNN and was more interpretable.
- Logistic Regression and QDA achieved similar cross-validation accuracy, around 71–73%.
- Winner height, surface, match duration, and first-serve points won were important predictors of ace performance.

## Files

- `ATP-Match-Duration.Rmd`: Full R Markdown analysis
- `ATP-Match-Duration.pdf`: Final knitted report

## Author

Aditya Chandani  
Mathematics and Data Science  
Franklin & Marshall College
