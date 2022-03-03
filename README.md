Team: Barbara/Mirjam

# Customer_Segmentation
Multi-class Classification Model to predict the label of new customers

Context:
An automobile company has plans to enter new markets with their existing products. After intensive market research, they’ve deduced that the behavior of new market is similar to their existing market.
In the existing market they classified customers into 4 segments. They plan to use the same strategy on new markets and have identified 2627 new potential customers.

Data Description:
Multi-class classification supervised ML model
Data is divided in train set (11 columns/ 8068 rows) and test set (10 columns/ 2627 rows)
Target variable: Segmentation-Column
Description of the problem: new customers are not yet labeled
Objective: create a prediction model that can assign the new customers to one of the existing segmentation (A,B,C,D) with high accuracy


Project Plan

Wed 2.Mar

1. EDA 
explore train set: column/features
checking for imbalance of target column
visualization of the data for understanding it better)

2. Data Cleaning
removing duplicates
dropping unnecessary columns: ID
dealing with missing values
numerical: Work_Experience: 829/around 10% (How to deal with the nan values here?), Family_Size: 335
categorical: Graduated: 78(Replacing with mode - Yes), Profession: 124 (Replacing with mode - Artist, Var_1: 76 (Replacing with mode - Cat_6), Ever_Married: 140 (Replacing with mode - Yes)

Thu 3. Mar

Still to do
removing duplicates
dropping unnecessary columns: ID
saving the cleaned version to a csv

3. Modelling
Split Train Data into Train and Validation Data with Predictors/Independent & Target/Dependent (Segmentation)
Encoding categorical variables - nominal or ordinal?
Pipeline 
Iteration: Choosing the best model with the highest accuracy and create the segmentation for the new customers
Feature Engineering (Feature Importance/ Feature Selection)
Fri 4. Mar
4. Evaluation
Cross Validation
GreadSearch
Tuning
