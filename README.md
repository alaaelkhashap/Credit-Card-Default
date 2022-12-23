# Credit-Card-Default

![image](https://user-images.githubusercontent.com/60587913/209307294-1b1cb031-4bc0-4db7-ba7f-d17487a2b7df.png)

## Main Topic
* Benefit of credit card 
* How credit card default happens
* Credit card default and time-consuming

## Abstract
Financial technology has mostly taken over our daily lives and simplified financial transactions and payments. Every day, a large number of people conduct transactions, but regrettably, some of them are unable to pay off their obligations. In order to lower the risk for the bank, we identify the clients in this paper who will go into default at an early stage and alert the bank about such clients.

## Introduction

Today, data has taken centre stage in banking, finance, and business. It kind of got hard to manage the data manually as the amount increased every second, so we turned to technology to automate activities and draw conclusions from the data for decision-making.
The worlds of money, stocks, credit, and investments are now a fast-paced and dynamic place for banking and finance. Many people use their credit cards to make regular purchases, and some of them are unaware that doing so will prevent them from making their monthly debt payments on schedule.

This might be problematic for both the client and the bank. It could cause a significant economic problem, similar to what occurred in the United States in 2008 when many people began to take out bank loans and then were unable to pay them back. This led to a period of economic contraction. As a result, the global economy was impacted by this crisis and lost more than $2 trillion.

Due to what we covered in the previous section and the significant risk that the banking and finance industries face, they have adopted cutting-edge technology, specifically the machine learning (ML) approach, to predict future decisions based on the client's historical data and determine whether or not a specific client can pay his or her debts. This will help to avoid a lot of issues in the future.


## Dataset 
Uisng https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset Dataset
* Dataset Information
    - This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.
    - Consists of 30000 instances, and 24 attributes with different data types (Numerical and Categorical)


## Covered Toics in methodology

* Data Preparation
  - Data Preparation
  - Data Cleaning
  - Further Analysis
  - Feature Engineering
  
* Training Data
    - Normal training set
    - Upsampled training set
    - Downsampled training set
    - SMOTE training set

* Models
  - Random Forest
  - Ada Boost
  - Gradient Boost
  - Light GBM Classifier
  - XGBClassifier
  - pycaret
  
 ## Conclusion
 •  Investigated the data and checked for data 
unbalancing.
• Visualizing the features and understanding the 
relationship between different features.
• Using different models from machine learning like 
“RF, DT, Ada boost, Gradient boost, LGBM,
Xgboost, and pycaret”.
• The best model is LDA using pycaret and the worst 
one is Ada Boost using a different sample of the 
training set.
• After implementing a different model, it may use in 
the bank to determine which client deserves to get 
the credit card.
• According to the accuracy:
The best model is the Ridge Classifier model = 
82.17%.
The worst model is the random forest model using
SMOTE training set = 69%.

 ## Future Work
  - Acquire customer data and more useful features.
  - Using deep learning, can be useful in complex data 
    and get more realistic results that can use in banks.
