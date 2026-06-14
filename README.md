# ADS503-FINAL-PROJECT
Predictive modeling project using CDC diabetes health indicator data to analyze, classify, and evaluate diabetes risk factors in R.


# Dataset source and description
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

The CDC Diabetes Health Indicators dataset consists of 253,680 records describing behavioral, clinical, and demographic characteristics, and is from the 2014 Behavioral Risk Factor Surveillance System (BRFSS) survey, available on UC Irvine’s Machine Learning Repository. There are a total of 22 variables, including a unique identifier `ID` and the binary target variable `Diabetes_binary` which indicates whether an individual has been diagnosed with diabetes/pre-diabetes or does not have either condition.



# Project Description
This project employs predictive modelling techniques to examine the relationship between lifestyle and health factors and diabetes diagnosis in the U.S. Using R and the CDC’s Diabetes Health Indicators dataset, the team will perform exploratory data analysis, pre-process the data, and develop, evaluate, and compare both linear and nonlinear binary classification models. Each model will be validated and tuned to improve predictive performance, with the objective of determining the optimal model and the features that contribute most to diabetes status


# Problem Statement





# Project overview and R library 
 
	1. Repository clonable if access given

	https://github.com/tkbarb10/ADS_505_Project.git
	cd ADS503-FINAL-PROJECT

	2. Library Needed 
		library(tidyverse)
		library(caret)
		library(corrplot)
		library(kernlab)
		library(pROC)
		library(earth)
		library(dplyr)
		library(gt)

	3. Process invloved

		i. EDA ( Data import, clean , validate , null value check, outlier check)
		ii. Train, Test and Validate split
		iii. Model build and ran on Trainging Dataset
		    - Logistic Regression
		    - Partial Least Squares (PLS)
		    _ Multivariate Adaptive Regression Splines (MARS)
		    _ Lnear Discriminant Analysis (LDA)
		    _ Random Forest
		    _ XGBoost
		iv. Best model selected with higher ROC and Accuracy (XGBoost)
		v. Ran XGBoost model against Test data 
