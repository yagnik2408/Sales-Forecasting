# Sales-Forecasting
This project provides an end-to-end solution for forecasting the demand for various items across multiple restaurants. By analyzing historical sales data, this project aims to build a predictive model that can help in making informed business decisions regarding inventory, staffing, and marketing strategies.
🎯 Project Overview
In a competitive market, accurate demand forecasting is crucial for business success. This project, developed for a data analytics company named Fresh Analytics, focuses on predicting the sales of restaurant items to enable better planning and decision-making.

The primary objectives were to:

Analyze historical sales data to understand patterns and trends.

Perform exploratory data analysis (EDA) to identify key drivers of sales, such as weekday, monthly, and quarterly fluctuations.

Compare the performance of different restaurants and identify popular items.

Build and evaluate several machine learning models to forecast future sales.

Provide a one-year sales forecast based on the best-performing model.

The entire process, from data preprocessing to model building and visualization, is documented in the Sales_Forecasting.ipynb notebook.

🛠️ Tech Stack
Language: Python

Core Libraries:

Data Manipulation & Analysis: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn (LinearRegression, RandomForestRegressor), XGBoost

Environment: Jupyter Notebook

📂 Datasets
The analysis is based on three separate CSV files:

sales.csv: Contains transactional data, including date, item ID, price, and item count.

items.csv: Provides details about each item, such as name, cost, and calorie count.

resturants.csv: Includes information about the different restaurant locations.

These datasets were merged to create a comprehensive dataset for analysis and modeling.

🚀 Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
Ensure you have Python 3.x installed on your system.

Installation
Clone the repository:

git clone https://github.com/your_username/sales-forecasting.git

Navigate to the project directory:

cd sales-forecasting

Install the required packages:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost

Launch Jupyter Notebook or JupyterLab to view the notebook:

jupyter notebook Sales_Forecasting.ipynb

📊 Analysis & Modeling
The Jupyter Notebook provides a detailed walkthrough of the project, including:

Preliminary Analysis & EDA:

Merging the datasets and handling missing values.

Visualizing daily, weekly, and monthly sales trends to identify seasonality.

Analyzing sales performance by restaurant and identifying top-selling items.

Feature Engineering:

Extracting time-based features from the date column, such as year, month, day, weekday, and quarter, to be used in the predictive models.

Model Building & Evaluation:

Three different regression models were built and compared:

Linear Regression

Random Forest Regressor

XGBoost Regressor

The models were trained on historical data, with the last six months reserved for testing.

Root Mean Square Error (RMSE) was used as the evaluation metric. The XGBoost model was found to be the best-performing model with the lowest RMSE.

Example Visualization
(Note: You would replace this with a screenshot of your actual forecast chart from the notebook)

💡 Conclusion & Forecast
The analysis revealed significant temporal patterns in sales, with clear weekly and seasonal trends. Based on the model comparison, the XGBoost Regressor was selected as the best model for forecasting.

The project culminates in a one-year sales forecast, providing valuable insights for future business planning and strategy.
