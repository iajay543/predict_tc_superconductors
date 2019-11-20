# predict_tc_superconductors
Predicting the critical temperature of superconductors


This project covers exploratory data analysis and prediction of critical temperature (Tc) of superconductors. The project specifications is described in 
'FIT5149_ass1_description.pdf' file which is uploaded in this repository. 

The workflow is as follows:
1. Exploratory Data Analysis (Data Auditing, Feature Scaling using Min-Max Normalization, 
Feature Selection using Filter Based Methods such as Variance Threshold and Correlation).
2. Model Building using Multiple Linear Regression, Model Updation, Model Comparison and Diagnosis.
3. Model Building using Wrapper Methods such as Stepwise Forward Regression, Stepwise Backward Regression, Stepwise Combined Regression and selecting the best one amongst the three on the basis of Mean Squared Error (MSE).
4. Model Building using Embedded Methods such as Ridge Regression, Lasso Regression and Elastic Net and selecting the best one amongst the three on the basis of Mean Squared Error (MSE).
5. Model Building using XGBoost.
6. Selecting the final best one amongst all (Initial Model from Filter method, Best Model from Wrapper method, Best Model from Embedded Method and XGBoost Model) on the basis of MSE.
