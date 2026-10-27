# Retail Sales Analysis and Forecasting

## Overview
This project analyses an online retail transaction dataset to identify sales trends, top revenue-generating items, and the potential of machine learning for monthly revenue forecasting.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Key Tasks
- Cleaned transaction data and calculated revenue.
- Analysed monthly revenue trends.
- Identified the top 10 items by revenue.
- Trained a Linear Regression model.
- Compared its predictions with a naïve forecasting baseline using Mean Absolute Error (MAE).

## Key Findings
- November 2011 recorded the highest full-month revenue in the analysed period.
- Linear Regression achieved an MAE of £377,352.41, compared with £437,836.01 for the naïve baseline.
- The model performed better than the baseline on the three test months, but its reliability remains uncertain because of the limited data.

## Limitations
The dataset contains only 13 monthly observations, and December 2011 is incomplete. The forecasting results should therefore be treated as an initial demonstration rather than a reliable business forecasting system.

## Dataset
UCI Machine Learning Repository: [Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)

## Author
Manzuma Halimat Jumai