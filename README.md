# Predictive Analytics for Work Orders

## Overview

This project focuses on developing a predictive analytics model to forecast work order volumes, assess risk levels, and categorize durations for facilities. The goal is to provide actionable insights that can help optimize resource allocation and manage operational risks more effectively.

## Key Components

1. **Data Preparation**:
   - **Data Loading and Cleaning**: Import and preprocess data from various sources, including CSV and Parquet files.
   - **Feature Engineering**: Generate new features from existing data, such as date-related features and work order metrics.

2. **Model Building**:
   - **Prediction Models**: Train and evaluate models to predict work order volumes using historical data. The models include regression and classification algorithms.
   - **Risk Assessment**: Evaluate risk levels associated with work orders, including location and escort risks.

3. **Prediction and Deployment**:
   - **Work Order Volume Forecasting**: Use trained models to predict future work order volumes and assess various risk factors.
   - **Visualization**: Create visualizations to represent the predicted work order volumes and risk assessments over time.

4. **Evaluation and Optimization**:
   - **Model Evaluation**: Assess the performance of different models and select the best-performing one based on accuracy and other metrics.
   - **Hyperparameter Tuning**: Optimize model parameters to improve performance.

## Files Included

- **`Deployment.ipynb`**: Contains the code for making predictions and visualizing the results based on the trained models.
- **`split_risks_duration.ipynb`**: Includes data preparation, feature engineering, and model training for predicting work order volumes and categorizing risks.

## How to Use

1. **Set Up Environment**: Ensure you have the required Python libraries installed (e.g., pandas, matplotlib, seaborn, scikit-learn, xgboost).
2. **Load Data**: Place your data files in the project directory.
3. **Run Notebooks**: Execute the Jupyter notebooks in the order provided to perform data processing, model training, and predictions.

## Results

The project produces forecasts for work order volumes and provides risk assessments, which are visualized through various plots and a PowerBI dashboard. This information helps in understanding future workload and managing risks effectively.
