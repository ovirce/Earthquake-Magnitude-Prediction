# Earthquake-Magnitude-Prediction
# A Comparative Study of Random Forest and Deep Neural Network Models for Earthquake Prediction

## 🏆 Dissertation Achievement

**94/100 — First-Class Honours**

This dissertation was awarded the **Outstanding Dissertation Award** at the University of Hull and achieved the **highest mark in my cohort**.

The project investigates and compares the performance of **Random Forest** and **Deep Neural Network** models for earthquake prediction using historical earthquake data from the United States Geological Survey (USGS).

---

## Overview

Earthquake prediction is a challenging machine learning problem due to the complex and unpredictable nature of seismic activity.

This project investigates whether machine learning techniques can be used to identify patterns in historical earthquake data and predict earthquake-related outcomes.

Two different approaches were developed and evaluated:

- **Random Forest**
- **Deep Neural Network**

The models were trained using historical earthquake data from **2000–2015** and evaluated on unseen data from **2016–2024**.

---

## Objectives

The main objectives of the project were to:

- Investigate the suitability of machine learning for earthquake prediction
- Prepare and analyse historical earthquake data
- Develop a Random Forest model
- Develop a Deep Neural Network model
- Compare the performance of the two approaches
- Evaluate model performance using appropriate metrics
- Investigate whether either approach provided meaningful predictive performance

---

## Technologies & Tools

### Programming
- Python

### Machine Learning
- Scikit-learn
- TensorFlow / Keras

### Data Analysis
- NumPy
- Pandas

### Visualisation
- Matplotlib

### Data Source
- USGS Earthquake Catalog

---

## Machine Learning Models

### Random Forest

The Random Forest model was developed using Scikit-learn.

Key parameters included:

- `n_estimators = 300`
- `max_depth = 8`
- `min_samples_leaf = 4`

### Deep Neural Network

A feed-forward neural network was developed using Keras/TensorFlow.

The network was trained using the prepared earthquake dataset and evaluated against unseen test data.

---

## Dataset

The project uses earthquake data obtained from the **United States Geological Survey (USGS)**.

The dataset covers earthquakes occurring in California between:

**2000 – 2024**

The data was divided chronologically:

| Dataset | Period |
|---|---|
| Training | 2000–2015 |
| Testing | 2016–2024 |

Using a chronological split helped ensure that the models were evaluated on future earthquake data rather than randomly selected observations.

---

## Evaluation

The models were evaluated using regression performance metrics including:

- Root Mean Squared Error (RMSE)
- R²
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

The results demonstrated the challenges associated with predicting earthquake behaviour using historical data alone and provided insight into the strengths and limitations of the approaches investigated.
