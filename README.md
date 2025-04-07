# Prediction-High-Traffic-Recipes-For-Tasty-Bytes
## Overview

Tasty Bytes, a recipe and meal planning service, aims to increase website traffic and subscriptions by featuring popular recipes on its homepage. The product manager has requested a data science solution to predict which recipes will lead to high traffic, with a goal of correctly predicting high traffic recipes 80% of the time while minimizing the display of unpopular recipes. This report outlines the data validation, exploratory analysis, model development, evaluation, and recommendations based on the provided dataset of 947 recipes.

## Key Exploratory Insights
- High traffic recipes are reasonably common (60%), providing a good basis for prediction.
- Categories like Potato and Vegetable are more likely to drive traffic, possibly due to broad appeal or dietary trends.

## Model Development
This is a binary classification problem, predicting whether a recipe leads to high traffic (1) or not (0). Two models were developed:
- Baseline Model: Logistic Regression
- Comparison Model: Random Forest
