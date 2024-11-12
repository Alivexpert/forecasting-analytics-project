# forecasting-analytics-project
Automated forecasting and data integration using Databricks and Power BI

# Project Overview
This project aims to develop an automated forecasting solution that uses Databricks for data processing and Power BI for visualization. The goal is to produce accurate forecasts of business metrics and make real-time data accessible through interactive dashboards.

# Table of Contents
* Project Overview
* Features
* Installation
* Usage
* Project Structure
* Results
* Future Improvement
* License

 # Features
 * Automated ETL process using Databricks, handling large datasets from multiple sources.
 * Forecasting model to predict key metrics such as revenue growth and expenses.
 * Power BI dashboards for real-time data analysis and visualization.
 * Data validation and transformation pipelines for reliable forecasting.

# Installation
Prereq
* Python 3.8 or Latest
* Databrick Account : For Model Traning and Data processing
* Create New DSN using ODBC data sources for data visualization
* Use any Visualization tool Create Interactive DBs

# Installation Steps 
git clone https://github.com/Alivexpert/forecasting-analytics-project.git
cd forecasting-analytics-project
# python packages
pip install -r requirements.txt

## Usage
# Data Prep Session 
* Use Databricks to extract data from multiple sources, clean, and normalize it.
* Load the prepared data into a SQL table named ForecastingData. (you can give the names of our chocices)
# Model Training
* Employ Python and PySpark to preprocess features and train a forecasting model.
* Use the VectorAssembler in PySpark to create feature vectors based on columns such as Actual Revenue, Actual Expenses, Profit Margin, and Growth Rate.( Insights on Different approaches are higly welcomed )
# Automation
* Set up a job in Databricks to automate the ETL, model training, and data updates in a table called UpdatedForecastingData.
* Configure the Databricks Job to run periodically, automatically refreshing the data and forecasts.
# Visualization 
* Connect Power BI using ODBC data sources
* Create Dashboard based on Business requirement as well as look for new metrics.
