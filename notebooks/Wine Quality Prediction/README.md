# Collection_Of_R_Projects

## Melanoma EDA
The task involves the exploratiry data analysis on the melanoma dataset.
The data consists of measurements made on patients with
malignant melanoma. Each patient had their tumour removed by surgery at the Depart-
ment of Plastic Surgery, University Hospital of Odense, Denmark during the period 1962
to 1977. The surgery consisted of complete removal of the tumour together with about
2.5cm of the surrounding skin. Among the measurements taken were the thickness of the
tumour and whether it was ulcerated or not. These are thought to be important prog-
nostic variables in that patients with a thick and/or ulcerated tumour have an increased
chance of death from melanoma.

# Census-Income EDA and Prediction Task

## Introduction
Columns included in the dataset:
* Age : continuous.
* Workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
* fnlwgt: continuous.
* Education : Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th,                           10th, Doctorate, 5th-6th.
* Education Number : continuous.
* Martial Status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
* Occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-               clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
* Relationship : Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
* Race : White, Asian-Pac-Islander, Amer-Indian-Eskimo,Black, other.
* Sex: Female, Male.
* Capital Gain : Continuous.
* Capital Loss : Continuous.
* Hours per week : Working hours per week(continuous)
* Native Country : United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South,                    China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-                    Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-                        Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.


## Content
1. Get Data
2. Data Cleaning
3. Missing values
4. Building model
5. Classification Models
   * Logistic Regression
   * SVM (Support Vector Machine)

# Problem Statement
Predicting the class of people based on their income of different countries.


# Wine Quality Prediction
## Data Set Selection

This datasets is related to red variants of the Portuguese "Vinho Verde" wine.  Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).  

The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality

**Content of the dataset**

Input variables (based on physicochemical tests):  
1 - fixed acidity  
2 - volatile acidity  
3 - citric acid  
4 - residual sugar  
5 - chlorides  
6 - free sulfur dioxide  
7 - total sulfur dioxide  
8 - density  
9 - pH  
10 - sulphates  
11 - alcohol  
Output variable (based on sensory data):  
12 - quality (score between 0 and 10)  

A new quality target will be genrated from the quality feature


Cortez, P., Cerdeira, A., Almeida, F., Matos, T., Reis, J., 2009. Modeling wine preferences by data mining from physicochemical properties. Decision Support Systems, 47, 547-553.