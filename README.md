# YES Bank Stock Price Prediction Using Machine Learning

## Project Overview

This project focuses on building a machine learning model to predict YES Bank stock closing prices using historical stock market data. The project analyzes previous stock price patterns, identifies important relationships between market variables, and applies regression algorithms to forecast stock prices.

The complete workflow includes data exploration, visualization, preprocessing, machine learning model implementation, performance evaluation, and hyperparameter tuning to improve prediction results.

## Project Type

EDA + Regression

## Objective

The major objectives of this project are:

- Study historical YES Bank stock price data.
- Perform Exploratory Data Analysis to understand market trends.
- Build regression models for predicting stock closing prices.
- Compare different machine learning algorithms.
- Optimize model parameters to improve prediction performance.

## Dataset

**Dataset Name:** data_YesBank_StockPrices.csv

The dataset contains historical stock market records of YES Bank with details related to price movements and trading activity.

The available features are:

- Date
- Open
- High
- Low
- Close
- Volume

The **Close** price is selected as the target variable for prediction.

## Variables Description

| Variable | Description |
|----------|-------------|
| Date | Represents the date of the stock record and helps analyze price variations and trends over different time periods. |
| Open | Indicates the opening price of YES Bank stock at the start of the trading session. |
| High | Represents the maximum price achieved by the stock during the trading period. |
| Low | Represents the minimum price reached by the stock during the trading period. |
| Close | Represents the final traded price of YES Bank stock and is the target variable predicted by the models. |
| Volume | Represents the number of shares traded and provides information about market activity. |

## Exploratory Data Analysis

EDA was performed to gain insights into the dataset and understand stock price behavior.

The analysis includes:

- Examining dataset structure and summary statistics.
- Checking missing values and data quality.
- Visualizing historical stock price movements.
- Studying feature relationships.
- Performing correlation analysis.
- Identifying trends and patterns in stock prices.

## Data Preprocessing

The following preprocessing techniques were applied:

- Imported and inspected the dataset.
- Checked for missing or inconsistent values.
- Converted date information into useful features.
- Selected appropriate input variables.
- Prepared data for machine learning algorithms.
- Split the dataset into training and testing sets.

## Machine Learning Models Implemented

### Random Forest Regressor

Random Forest Regressor is an ensemble-based algorithm that combines multiple decision trees to improve prediction accuracy. It is capable of learning complex patterns from historical stock data and reducing overfitting.

### XGBoost Regressor

XGBoost Regressor is a powerful boosting algorithm that improves model performance by sequentially reducing prediction errors. It is effective for handling structured datasets with complex relationships.

### Support Vector Regression (SVR)

Support Vector Regression is used to predict continuous values by finding patterns between input features and output variables. It performs well in capturing non-linear relationships using kernel functions.

## Model Evaluation Metrics

The performance of the regression models is measured using:

**Mean Absolute Error (MAE)**

Measures the average absolute difference between actual and predicted stock prices. Lower MAE values indicate better prediction accuracy.

**Mean Squared Error (MSE)**

Measures the average squared difference between actual and predicted values and gives more importance to larger prediction errors.

**Root Mean Squared Error (RMSE)**

Represents the prediction error in the same scale as the stock price, making it easier to understand.

**R² Score**

Indicates how effectively the model explains variations in YES Bank stock prices. Higher R² values represent better model performance.

## Hyperparameter Optimization

Hyperparameter tuning was performed to improve model efficiency and prediction accuracy.

The optimization methods used are:

**GridSearchCV**

GridSearchCV searches through predefined parameter combinations and selects the best parameters based on cross-validation results.

**RandomizedSearchCV**

RandomizedSearchCV performs random sampling of parameter combinations to find optimized parameters with reduced computational cost.

The tuning process helped enhance model performance by selecting suitable parameter values and reducing prediction errors.

## Results

The developed machine learning models successfully predicted YES Bank stock closing prices using historical market data.

The optimized models achieved:

- Improved prediction performance.
- Lower error values.
- Better R² score.
- Improved understanding of stock price patterns.

The final model can be used as a supporting system for financial analysis and market trend evaluation.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Project Structure

YES-Bank-Stock-Price-Prediction/

├── README.md

├── Sample_EDA_Submission_Template.ipynb

├── Sample_ML_Submission_Template.ipynb

├── data_YesBank_StockPrices.csv

└── requirements.txt

## How to Run the Project

1. Open the notebooks using Google Colab.

2. Upload the dataset:

data_YesBank_StockPrices.csv

3. Install the required dependencies:

pip install -r requirements.txt

4. Execute all notebook cells sequentially.

The notebooks perform:

- Data loading.
- Exploratory Data Analysis.
- Data preprocessing.
- Data visualization.
- Model training.
- Model evaluation.
- Hyperparameter tuning.
- Stock price prediction.

## Requirements

The required Python packages are available in the requirements.txt file.

## Author

**Kanagasundari B**

## Conclusion

This project demonstrates the application of machine learning regression techniques for YES Bank stock price prediction. By combining data analysis, preprocessing, regression algorithms, evaluation metrics, and optimization methods, the project provides an approach for analyzing historical stock data and generating predictive insights.

The model can assist in understanding stock trends and supporting financial analysis. Since stock prices are affected by multiple economic and market factors, the predictions should be used as an analytical aid rather than a guaranteed indication of future prices.
