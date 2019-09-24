# Customer Behaivor Prediction (2) - Monthly Spending

## Overview
In 1998, the Adventure Works Cycles company collected a large volume of data about their existing customers, including demographic features and information about purchases they have made. The company is particularly interested in analyzing customer data to determine any apparent relationships between demographic features known about the customers and the likelihood of a customer purchasing a bike. Additionally, the analysis should endeavor to determine whether a customer's average monthly spend with the company can be predicted from known customer characteristics.

## Goal
The goal is to build a regression model to predict customers' monthly spending.

## Data
The training and test datasets are retrieved from [Microsoft Learning](https://github.com/MicrosoftLearning).

## Model
We are adopting a simple linear regression model to predict customers' monthly spending. Evaluated with cross-validation on the training data, the simple model gives an R^2 of **0.9464**.
