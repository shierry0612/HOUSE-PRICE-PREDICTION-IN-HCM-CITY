# HOUSE-PRICE-PREDICTION-IN-HCM-CITY
This project focuses on predicting house prices in Ho Chi Minh City using machine learning techniques. It includes web scraping, data preprocessing, feature engineering, model training, evaluation, and visualization.

## Objective
This project demonstrates an end-to-end data science workflow including:
- Data scraping from a real estate website
- Data preprocessing and feature engineering
- Machine learning modeling and evaluation
- Data visualization using geospatial techniques
The ultimate goal is to build a model that can accurately predict house prices based on relevant features.

## Data Collection and Cleaning:
Data source:
- The dataset was collected from real estate listings on the website batdongsan.vn.
- The data includes house prices, area, location, and other attributes such as legal documents and interior conditions.
- The data was collected from various districts of Ho Chi Minh City during the year 2023.

Handling noisy data:
- Erroneous values were adjusted, and irrelevant or corrupted data entries were removed.

## Data Analysis:
- Descriptive analysis: Descriptive statistics were used to gain insights into the distribution and relationships between variables in the dataset.
- Correlation analysis: Correlation analysis was conducted to examine the relationships between house prices and factors such as location, area, number of rooms, etc.

## Data Preprocessing:
- Handling missing values: Removed or imputed missing data
- Outlier processing
- Normalization and encoding
- Data type conversion for compatibility

## Predictive Modeling:
- Machine learning models: Applied basic models (Linear Regression) along with advanced models such as Random Forest and Support Vector Machines to predict house prices.
- Hyperparameter tuning: Performed hyperparameter optimization to improve model performance.

## Model Evaluation:
- Baseline model: Used as a reference point to compare with advanced models.
- Cross-validation: Employed to enhance objectivity and minimize bias by avoiding overfitting and ensuring coverage of potential patterns in the data.
- Performance evaluation: Used MAE, MSE, and RMSE to evaluate each model's performance.
- Model benchmarking:
- Compared all model metrics to identify the optimal one.

## Tools Used:
- Web scraping: Beautiful Soup, Regex
- Data processing: Pandas, NumPy
- Data visualization: Matplotlib, Seaborn
- Machine learning: Scikit-learn

