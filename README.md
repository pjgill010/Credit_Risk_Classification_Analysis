# Credit_Risk_Classification_Analysis

## Summary:

- This project uses various techniques to train and evaluate a model based on loan risk. A dataset of historical lending activity from a peer-to-peer lending services company was used to build a model that can identify the creditworthiness of borrowers.

#### Steps:
- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Predict a Logistic Regression Model with Resampled Training Data
- Write a Credit Risk Analysis Report

#### First Model:

<img width="485" alt="Model 1" src="https://github.com/pjgill010/Credit_Risk_Classification_Analysis/assets/118948437/acef8fa9-6fc9-4fa2-8d16-f2f11daa1fda">

#### Second Model:

<img width="463" alt="Model 2" src="https://github.com/pjgill010/Credit_Risk_Classification_Analysis/assets/118948437/482d8fd6-fe85-4bd0-9049-c22c6772b5ab">

## Questions:

- Question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
- Answer: 94% accurate. High risk loans - recall is 89%. Should be higher.

- Question: How well does the logistic regression model, fit with oversampled data, predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
- Answer: Accuracy has gone up. 94% up to 99%. Recall for high risk 89% up to 100%
