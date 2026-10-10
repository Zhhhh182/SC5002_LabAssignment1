# SC5002 Lab Assignment 1 Machine Learning Experiments

## Project Overview

This assignment explores regression models for predicting median house values using the California housing dataset.

## Machine Learning with Regression Models

* Dataset: California housing dataset.
* Continuous Target variable: `MedHouseVal`.
* Input features: `MedInc`, `HouseAge`, `AveRooms`, `AveBedrms`, `Population`, `AveOccup`, `Latitude`, and `Longitude`.
* Models: Linear Regression and Ridge Regression (with different regularization penalties).
* Evaluation: Five-fold cross-validation using the R² score.

## Results

| Model             | Mean 5-Fold R² |
| ----------------- | -------------: |
| Linear Regression |         0.6457 |
| Ridge (α = 0.1)   |         0.6457 |
| Ridge (α = 10)    |         0.6443 |
| Ridge (α = 1000)  |         0.3574 |

## Key Findings

Excessive Ridge regularisation can cause underfitting and reduce predictive performance. Cross-validation provides a more robust assessment than a single train/test split.

## How to Run

1. Open the notebook in Google Colab.
2. Install any required libraries and load the dataset as instructed in the notebook.
3. Click Run All.

## Use of Generative AI

Generative AI was used to clarify concepts, review calculations, and interpret model evaluation results. Its suggestions were checked against the group's calculations and experimental outputs.
