# Diabetes Prediction using PySpark

![Diabetes Image](assets/img/project/diabetes_pred.jpg)

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Key Features](#key-features)
- [Results and Stats](#results-and-stats)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## Project Overview

This project aims to predict diabetes occurrence using the Pima Indians Diabetes dataset. Through advanced Exploratory Data Analysis (EDA) and feature engineering, the model was enhanced to provide accurate results.

## Technologies Used

- **PySpark:** Used for data processing and ML modeling.
- **Optuna:** Applied for hyperparameter tuning and optimization.
- **Seaborn & Matplotlib:** For visualization and EDA.

## Key Features

- **Advanced EDA:** Conducted a deep dive into the dataset, visualizing correlations and feature distributions.
- **Feature Engineering:** Introduced interaction terms to boost model performance.
- **Model Building:** Utilized Logistic Regression and Gradient Boosted Trees from PySpark's MLlib.
- **Optimization:** Applied Optuna for hyperparameter tuning, achieving better model results.

## Results and Stats

- Conducted **10** optimization trials with Optuna.
- Best trial achieved an accuracy of **95.88%** with parameters:
  - maxDepth: 6
  - maxBins: 21
  - maxIter: 13
- Gradient-Boosted Trees Classifier (with Cross Validation) achieved an accuracy of **96.03%**.

## Usage

1. Clone the repository to your local machine.
2. Ensure you have all the necessary libraries and dependencies installed.
3. Run the PySpark notebook.
4. For visualization, ensure Matplotlib and Seaborn are installed.

## Acknowledgements

- Dataset sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php).
- Special thanks to OpenAI and the community for guidance and support.
