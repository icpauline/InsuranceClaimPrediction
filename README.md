# Insurance Claim Prediction
## Introduction
CarIns is a startup that provides insurance for cars. It is one of the best car insurance brands known for the highest claim settlement ratio. It was launched back in Oct 2020 and acquired its initial policyholders by providing a hassle-free claim process, instant policy issuance, and claim settlements at minimum coverages.

As it's a fast growing startup, the company would like to optimize the cost of the insurance by identifying the policyholders who are more likely to claim in the next 6 months. 
## Task
Now the company would like to use Data Science to identify the policyholders whose chances of filing a claim are high in the next 6 months. The company challenges the Data Science community to build a high-performance algorithm to predict if the policyholder will file a claim in the next 6 months or not based on the set of car and policy features.
## Dataset:
We are provided with information on policyholders containing the attributes like policy tenure, age of the car, age of the car owner, population density of the city, make and model of the car, power, engine type, etc and the target variable indicating whether the policyholder files a claim in the next 6 months or not.
The given dataset consists of 97655 rows and 43 columns
## Approach
1.	Imported the dataset.
2.	Checked for null values and duplicates
3.	Checked for unique values in the columns
4.	Featuring Engineering is done by combining some features
5.	Feature elimination is performed with the help of correlation
6.	Performed one hot encoding on categorical variables
7.	upsampled the highly imbalanced dataset using SMOTE
8.	Used XGBoost classifier to obtain the best f1 score.
