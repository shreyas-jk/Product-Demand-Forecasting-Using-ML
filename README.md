# Demand Forecasting using Machine Learning


Demand forecasting is the process of making estimations about future customer demand over a defined period, using historical data and other information. 

Usually organisations follow tranditional forecasting techniques/algorithms such as Auto Arima, Auto Arima, Sarima, Simple moving average and many more.

## Table of Contents

- [Goal](#goal)
- [Workflow](#workflow)
- [Required Packages](#require)


## Goal <a name = "goal"></a>

Due to the recent boost in AI world, companies have started researching the possibility of using machine learning in place of tranditional approach.

Tuning traditional algorithms takes a significant amount of effords and domain expertise as well. 

In this repo, we are trying to figure out a way of predict the same using machine learning algorithms. 


## Data <a name = "dataset"></a>

The dataset comprised of units sold on a daily basis along with details regarding the sales, eg. SKU(product id), Store, price etc.

*record_ID,	week,	store_id,	sku_id,	total_price,	base_price,	is_featured_sku,	is_display_sku,	units_sold*


## Workflow <a name = "workflow"></a>

- Handling missing values
- Feature selection based on my previous experience in Supply chain domain
- Converting dataset into time series format to apply supervised learning approach.
- Regression Modeling
  - Random Forest
  - XGBoost
  - SVM (future scope)
- Hyperparameter Tuning

## Result
![train](https://github.com/shreyas-jk/Demand-Forecasting-Using-ML/blob/main/final.png?raw=true)



## Required Packages <a name = "require"></a>

- numpy
- pandas
- sklearn
- easypreprocessing 
- seaborn 
- matplotlib
- xgboost

