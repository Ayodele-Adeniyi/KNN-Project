# Predicting Internet Addiction in Children: A Comparative Analysis of Predictive Models

## Overview

This project explores predictive models for estimating scores on the Parent-Child Internet Addiction Test (PCIAT) based on features such as Sleep Disturbance Score, Internet Usage, Age, and Sex. It compares the effectiveness of **Linear Regression** and **k-Nearest Neighbors (KNN)** models to determine the best approach for predicting PCIAT scores.

## Dataset

-   **Source:** [Kaggle - Child Mind Institute: Problematic Internet Use](https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use/data)
-   **Features Used:**
    -   Age (years)
    -   Sex (Male/Female)
    -   Sleep Disturbance Score
    -   Internet Usage (hours/day)
    -   PCIAT Score (Target Variable)
-   **Data Preprocessing:**
    -   Handling missing values
    -   Feature selection and transformation

## Methodology

1.  **Exploratory Data Analysis (EDA)**
    -   Visualizing data distributions and correlations
    -   Checking for missing values and outliers
2.  **Model Selection & Implementation**
    -   **Linear Regression:** Assesses linear relationships and statistical significance of predictors.
    -   **k-Nearest Neighbors (KNN):** Predicts PCIAT scores based on the similarity of neighboring data points.
3.  **Model Evaluation**
    -   **Root Mean Squared Error (RMSE)** used as the primary performance metric.
    -   **10-Fold Cross Validation** to assess model generalization.

## Results

| Model                      | RMSE      |
|----------------------------|-----------|
| Linear Regression          | 16.3336   |
| k-Nearest Neighbors (K=51) | `16.5731` |

-   The model with the lower RMSE is recommended for PCIAT score prediction.
-   Linear Regression provides better interpretability, while KNN offers flexibility.
