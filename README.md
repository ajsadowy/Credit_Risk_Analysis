# Credit_Risk_Analysis   
## Overview of Analysis   
This project's purpose was to build and review several maching learning models to help predict credit risk.   
   
The algorthms that were utilized were RandomOverSampler, SMOTE, ClusterCentroids, and SMOTEENN. The models we utilized to reduce bias were BalancedRandomForestClassifier and EasyEnsembleClassifier.   

## Results   
### RandomOverSampler Model   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/1a.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/1b.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/1c.png)   
   
 * Accuracy score is 64.7%   
 * Precision for high risk is 1% and a sensativity of 62%   
 * Precision for low risk is 99% and a sensativity of 67%   
   
### SMOTE Model
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/2a.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/2b.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/2c.png)   

 * Accuracy score is 62.5%   
 * Precision for high risk is 1% and a sensativity of 62%   
 * Precision for low risk is 99% and a sensativity of 63%   
   
### ClusterCentroids Model   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/3a.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/3b.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/3c.png)   
   
 * Accuracy score is 51.0%   
 * Precision for high risk is 1% and a sensativity of 59%   
 * Precision for low risk is 99% and a sensativity of 44%   
   
### SMOTEENN Model   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/4a.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/4b.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/4c.png)   
   
 * Accuracy score is 64.1%   
 * Precision for high risk is 1% and a sensativity of 70%   
 * Precision for low risk is 100% and a sensativity of 58%   
   
### BalancedRandomForestClassifier Model   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/5a.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/5b.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/5c.png)   
   
 * Accuracy score is 78.8%   
 * Precision for high risk is 3% and a sensativity of 70%   
 * Precision for low risk is 100% and a sensativity of 87%   
   
### EasyEnsembleClassifier Model   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/6a.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/6b.png)   
![pic](https://github.com/ajsadowy/Credit_Risk_Analysis/blob/main/IMAGES/6c.png)   
   
 * Accuracy score is 93.1%   
 * Precision for high risk is 9% and a sensativity of 92%   
 * Precision for low risk is 100% and a sensativity of 94%   

## Conclusion   
For every model used showed a poor precisions rate for determining high risk. Even with the EasyEnsembleClassifier model being the best model showed a precision of 9% for high risk.    
   
Now while the bank may be skeptical when using these models to determine credit eligibility for these high risk candidates, these datasets would support offering credit with higher interest rates and application fees to increase yields to offset the risk cost.
