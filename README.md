
# Optimal Gasoline Price Predictions Using ANFIS Model

This project implements an Adaptive Neuro-Fuzzy Inference System (ANFIS) model to predict optimal gasoline prices based on historical data and relevant features.

## Overview

Gasoline prices fluctuate due to various economic and geopolitical factors. Accurate price prediction models help stakeholders make better decisions. This project applies an ANFIS model combining neural networks and fuzzy logic to forecast gasoline prices with improved accuracy.

The approach is inspired by and adapted from the methodology in the paper:
**"Optimal Gasoline Price Predictions: Leveraging the
ANFIS Regression Model"**
[DOI: 10.1155/2024/8462056](https://onlinelibrary.wiley.com/doi/pdf/10.1155/2024/8462056)

The work is implemented as a Kaggle notebook available [here](https://www.kaggle.com/code/gamzeakkurt/optimal-gasoline-price-predictions-anfis-model).

## Dataset

The dataset includes historical gasoline prices and associated economic indicators (describe dataset briefly or link to source if applicable).

## Features

* Feature engineering and selection based on domain knowledge
* Data preprocessing, including normalisation and cleaning
* Implementation of ANFIS for price prediction

## Model

* Adaptive Neuro-Fuzzy Inference System (ANFIS)
* Hybrid learning approach combining gradient descent and least squares
* Evaluation using metrics such as RMSE, MAE, etc.

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/gamzeakkurt/anfis-gasoline-forecasting.git
   cd anfis-gasoline-forecasting
   ```

2. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or Python scripts to train and evaluate the ANFIS model.

## Results

* The model achieves competitive performance on the test set
* Visualisations of predictions vs actual prices included


## References

* Jang, J.-S.R. (1993). ANFIS: Adaptive-Network-based Fuzzy Inference System.
* Çakır, M., & Sağlam, M. (2024). Adaptive neuro-fuzzy inference system for optimal gasoline price prediction. *Journal of Applied Mathematics and Computation*, 2024, Article ID 8462056. [https://doi.org/10.1155/2024/8462056](https://onlinelibrary.wiley.com/doi/pdf/10.1155/2024/8462056)
