# Collection_Of_R_Projects

# Rossaman Store Prediction
## Objectives
The target is to predict the Sales across the different stores. It is a regression task

## Data 
The data is from various Rossmann Pharmaceuticals stores collected over time. The goal is to build a model that can forecast Sales in the different stores. The model can be used for future prediction of sales and use for making business decisions.
Exploratory data analysis (EDA)
Exploratory data analysis is the lifeblood of every meaningful machine learning project. It helps us unravel the nature of the data and sometimes informs how we go about modeling. A careful exploration of the data encapsulates checking all available features, checking their interactions and correlation as well as their variability concerning the target.
The following results were obtained from EDA
•	It was noted that the data range for the Sales column is from 0 to 40,000, but there is barely any data after 20,000.
•	It was noted that the features Promo, Promo2, School Holiday, and Open are binary categorical features: Promo2 is well distributed between the two distinct values, whereas Promo has more records for ‘1’ and Open has most of the store records as ‘1’. The distribution between the values for ‘Open is good, as the stores will be open for most days except state holidays. Customer numbers range from 0 to 2,000 for most stores. A few stores have as many as 7000 daily customers, but these are outliers and we might need to fix them before modeling. The next set of numeric variables are Promo2SinceWeek and Promo2SinceYear; these show a relatively well-distributed feature
•	We can notice that the distribution of data points across different classes within a category is skewed. 
•	A simple check on StoreType and Assortment reveals that StoreType ‘b’ has a significantly lower number of stores or data points in the dataset. 
•	There was more sale when there was no holiday
•	There  was more sale when there during the promo period

## Machine Learning Prediction Model
GBM and Xgboost algorithms were used to model the data and MSE was used as a metric

## Results
The result of the analysis shows that Xgboost performed better in terms of MSE. The lowest MSE reported was 456.4174. It should also be noted that the most important feature in the datasets used by XGBOOST for evaluation was the ‘Customer feature’. Other important features can be seen in the chart provided in the appendix

