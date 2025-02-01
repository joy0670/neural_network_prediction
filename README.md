# Prediction of Conversion Within 7 Days with a Neural Network

## Project Overview
This project applies **machine learning** to predict whether a user will **convert (make a purchase)** within **7 days** based on behavioral data. The model is trained using a **neural network** and leverages data processing, feature engineering, and deep learning techniques to optimize predictions.

## Dataset & Features
The dataset, extracted from **Google BigQuery**, includes:
- **User interactions** (event timestamps, event names)
- **E-commerce details** (total items purchased, revenue, transaction ID)
- **Device information** (device category, platform)
- **Feature engineering** was performed to create **derived variables** that enhance predictive power.

## Modeling Approach
- **Data Cleaning & Feature Engineering**: Extract meaningful features from raw data.
- **Neural Network Model**: Implemented using **TensorFlow/Keras**.
- **Training & Evaluation**: Data split into **training and validation sets** to assess model performance.
- **Performance Metrics**: Evaluated using accuracy, precision-recall, and AUC-ROC scores.

## Results & Insights
- The model successfully identifies high-potential conversion users.
- Feature importance analysis reveals that **purchase behavior and event sequences** are strong predictors.
- Future improvements can include **hyperparameter tuning, alternative architectures, and additional behavioral features.**

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/conversion-prediction.git
   cd conversion-prediction
