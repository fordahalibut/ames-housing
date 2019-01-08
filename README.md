# Project 2 - Ames Housing Data and Kaggle Challenge

## Problem statement

Using the Ames Housing dataset, can we build a regression model that is predictive of home value?

## Executive Summary

Key Findings:
- Many features had a correlation on sale price, even after Lasso regularization.
- Intuition only gets us so far with this data set - many strong correlations come from surprising features.

After performing exploratory data analysis and munging, we obtained a set of features that appear to have strong predictive capability for our target variable. Using scaling and regularization, we controlled for colinearity. By using a hold out set and cross validation, we controlled for overfitting on our training data, and ultimately achieved an $R^2$ score of `0.93`.


## Contents

- [1. Importing and Examining Data](#1.-Importing-and-Examining-Data)
- [2. Examining our target variable](#2.-Examining-our-target-variable)
- [3. Handling Outliers](#3.-Handling-Outliers)
- [4. Cleaning missing data](#4.-Cleaning-missing-data)
- [5. Data transformations](#5.-Data-transformations)
- [6. Exploratory Data Analysis](#6.-Exploratory-Data-Analysis)
- [7. Creating Dummy Variables](#7.-Creating-Dummy-Variables)
- [8. Building X and y, transforming and scaling features](#8.-Building-X-and-y,-transforming-and-scaling-features)
- [9. Constructing and scoring the model](#9.-Constructing-and-scoring-the-model)
- [10. Conclusion](#10.-Conclusion)

## Data Dictionary
- [Ames Housing Dataset](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)

## Conclusion

After performing exploratory data analysis and munging, we obtained a set of features that appear to have strong predictive capability for our target variable. Using scaling and regularization, we controlled for colinearity. By using a hold out set and cross validation, we controlled for overfitting on our training data, and ultimately achieved an $R^2$ score of `0.93`.