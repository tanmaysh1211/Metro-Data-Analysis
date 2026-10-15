# Delhi Metro Smart Card Analytics Platform

This is a comprehensive PySpark-based big data analytics system designed to analyze Delhi Metro smart card transaction data. It leverages the Hadoop ecosystem and advanced machine learning techniques to generate actionable insights for urban transportation optimization, passenger behavior prediction, and fraud detection.

## Features

- **Data Cleaning & Entity Resolution:** Normalizes and cleans transaction data, including station name standardization.
- **Recommendation System:** Implements ALS collaborative filtering to recommend optimal metro stations/routes to passengers.
- **Peak Hour Prediction:** Uses Decision Tree classification to forecast peak hour travel with over 85% accuracy.
- **Anomaly Detection:** Applies K-Means clustering to identify anomalous travel patterns and potential fraud.
- **Monte Carlo Simulation:** Simulates fare variations to assess financial risk and revenue forecasting.
- **Extended Data Analysis:** In-depth descriptive statistics and insights such as peak vs off-peak travel times, fare distributions, passenger loyalty, station pairs, and correlation of travel metrics.
- **Output:** Saves processed datasets in Parquet format for efficient querying and Hadoop integration.

## Tech Stack

- PySpark and MLlib for data processing and machine learning
- Hadoop HDFS for scalable data storage and Parquet format for optimized datasets
- Python 3.x for scripting and orchestration

## Project Benefits

- Enables transit authorities like MoRTH to optimize scheduling and reduce congestion
- Provides fare fraud detection capabilities potentially saving millions INR
- Supports infrastructure and policy planning with robust data-driven insights
- Scales to handle millions of daily transactions in smart city environments

## Usage

1. Ensure the dataset (`metro.csv`) is available in the `csv/` directory.
2. Run the PySpark script to perform data processing, training, and analytics.
3. Access output Parquet files for further analysis or visualization.




