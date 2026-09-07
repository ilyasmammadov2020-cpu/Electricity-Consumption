
## Daily Electricity Consumption Prediction

This project analyzes **daily electricity consumption in Turkey** using several statistical and machine-learning methods. All computations are performed in Python.

## Objective

The main objective is to develop and compare different models for predicting daily electricity consumption and evaluate their performance on unseen test data.

## Dataset

The project uses the **daily electricity consumption in Turkey** dataset provided as:

```text
Electricity-Consumption.csv
```

The data is divided into:

* **Training set:** First 10 months
* **Test set:** Last 2 months

## Methods

### 1. Regression

* Full least-squares regression using all potential predictors
* Analysis of predictor significance and R²
* Training and test performance using:

  * MSE
  * RMSE
  * MAPE
* Lasso regression with 5-fold cross-validation
* Model selection using exactly 5 predictors

### 2. Trees and Random Forests

* Regression tree
* Visualization of the first three tree levels
* Predictor importance analysis
* Random forest
* 5-fold cross-validation to determine:

  * Optimal tree depth
  * Number of predictors
* Training and test performance evaluation

### 3. Neural Networks

Two neural-network models are developed:

* Single-hidden-layer neural network
* Two-hidden-layer neural network

Different activation functions and optimization parameters are tested, including:

* Sigmoid
* ReLU
* Mini-batch size
* Number of epochs

## Evaluation

Models are evaluated primarily using:

* **MSE (Mean Squared Error)**
* **RMSE (Root Mean Squared Error)**
* **MAPE (Mean Absolute Percentage Error)**

The final comparison considers both training and test performance to assess model accuracy and possible overfitting.

## Project Structure

```text
.
├── Electricity-Consumption.csv
├── Electricity_consumption.ipynb
├── electricity consumption.docx
└── README.md
```

## Requirements

The project is implemented in Python using standard libraries, including:

```text
numpy
pandas
scikit-learn
statsmodels
matplotlib
```


## Results

The final report summarizes:

* Model specifications
* Hyperparameters
* Training errors
* Test errors
* Model comparisons
* Overfitting assessment
* Overall recommendation of the best and least suitable methods


