# Phishing

## Objective: Identify Phishing Websites 

### Brief description of data: 
30 categorical features, one target variable with 2 categories.

### Libraries used:
pandas, numpy, matplotlib, seaborn, scikit-learn

### Approach

1. Overview of Data
2. Check for missing values
3. Check distribution of target variable
4. Apply classification models using all variables and select the model with the best score
5. Hyperparameter optimization of best model
6. Plot important features

Result: Random Forest Model gave the best accuracy, f1 - score and cross validation score. No features were omitted as reduction in number of features resulted in lower scores.

        Accuracy: 97%
        
        Cross Validation Score: 98%
        
        F1 Score: 97% for class 0 and 96% for class 1
