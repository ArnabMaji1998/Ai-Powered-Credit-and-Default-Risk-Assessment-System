# Ai-Powered-Credit-and-Default-Risk-Assessment-System


## Introduction

Credit risk modeling is important for financial institutions. It represents the risk of borrower not being able to pay back the loan amount, credit card or other types of loans. In some cases, borrowers can pay only partial of the amount and the principal amount and interest amount are not paid. Both statistics and machine learning play an important role in handling big data and provide statistical modeling. 

## Project

This project is an AI-powered project to model the credit and default risk for loans. 

The goal is to build a credit risk model by using Loan Data to provide a scorecard for a daily use as well as a pipeline to calculate exposure loss.

Here is a step-by-step instruction as also in compliance with the Basel II requirements:

*  Preprocessing - Converting columns into dummy variables by fine and coarse classing
*  Calculate the PD model with logistic regression
*  Based on PD model, provide a practical scorecard in csv format
*  Construct LGD model with beta regression
*  Build EAD model with linear regression
*  Calculate the exposure loss after obtaining all models
*  Check the models if they are still doing good with the recent credit risk modeling.

Please note that this notebook includes my revisions/additions to the credit risk course on [365 Learning](https://365datascience.com/courses/credit-risk-modeling-in-python/).

## Key documents
	
Notebooks shown below:  
A preprocessing notebook and feature engineering  
A notebook on modelling probability of default (PD), delivering scorecard and calculating cutoff rate   
A notebook on modelling loss given default (LGD), exposure at default (EAD) and expected loss (EL)  
A notebook on checking population stability index  



## Deliverables

1. Scorecard, easy to interpret in comliance with the requirements    
2. Dataframe to test the impact of cut off rates on the number of accepted borrowers for credit
3. Models on loss given default (LGD), exposure at default (EAD) and expected loss (EL)  
4. Schema to check the population stability index with the recent data  

## Key documents
	
Notebooks  
1 - A preprocessing notebook  
2 - A notebook on selecting features for probability of default (PD) and modelling PD  
3 - A notebook on modelling loss given default (LGD), exposure at default (EAD) and Expected Loss (EL)  
4 - A notebook on checking population stability index  

## Technologies

Project is created with:
* Python 3.8
* Jupyter Notebook 6.4.12
* Python libraries (see /requirements.txt)
* VSCode 1.71.2
