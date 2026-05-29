# Predicting House Prices

A machine learning project comparing the performance of Random Forest and Gradient Boosting Machine (GBM) models in predicting residential house prices using the Ames Housing dataset.

## Overview

This project investigates how two ensemble learning techniques—Random Forest and Gradient Boosting Machines—compare in terms of predictive accuracy for housing price prediction. The workflow includes data exploration, preprocessing, hyperparameter tuning, model training, cross-validation, and performance evaluation.

## Dataset

This project uses the Ames Housing dataset from Kaggle's *House Prices: Advanced Regression Techniques* competition.

The dataset contains 79 explanatory variables describing residential homes in Ames, Iowa, including property characteristics, location information, quality metrics, and structural features.

## Methodology

The machine learning pipeline includes:

* Data cleaning and preprocessing
* Missing value handling
* Log transformation of the target variable
* Exploratory data analysis (EDA)
* Hyperparameter tuning
* Random Forest regression
* Gradient Boosting Machine regression
* 5-fold cross-validation
* Feature importance analysis
* Model evaluation using MSE and R²

## Results

The Gradient Boosting Machine model achieved stronger predictive performance than the Random Forest model, demonstrating:

* Lower Mean Squared Error (MSE)
* Higher R² score
* Better generalization during cross-validation
* More consistent performance across validation folds

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Repository Contents

* `prediction-pipeline.ipynb` — Complete machine learning workflow, analysis, and model evaluation.

## Research Paper

A detailed research paper accompanying this project is available on ResearchGate.

**DOI:** 10.13140/RG.2.2.23088.11526
