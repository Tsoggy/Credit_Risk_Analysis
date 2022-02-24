# Credit Risk Analysis

## Purpose
In this analysis, we used the credit card credit dataset from Lending Club to create models that evaluates applications for low or high risk. Each application has many variables, including but not limited to: loan amount, interest rate, annual income, home ownership, etc..

### Models used for analysis
The following six machine learning models are used to check for accuracy in determining risk:
  
  1. Random Oversampling
  2. SMOTE
  3. Random Undersampling
  4. SMOTEENN
  5. Balanced Random Forest Classifying
  6. Easy Ensemble Classifying

### Initial Counts of Minority/Majority Classes in the Dataset
When we split the data into low risk and high risk, the count of each in the dataset is as follows (where 0 is high-risk and 1 is low-risk):
![HighvLow](Resources/HighvLow.png)

0.5% of the dataset is classified as high-risk, which is a very small subset of the dataset. When we separate our data into training and testing groups, our training group has the following count:
![HighvLowTraining](Resources/HighvLowTraining.png)

## Accuracy Scores of Each Model
#### Random Oversampling
Random oversampling duplicates the records of the minority class (data that is identified as high-risk) to match the size of the majority class. Using random oversampling produces the following measurements:
