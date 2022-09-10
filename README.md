
The **objective** of this project is to create an accurate as possible machine learning classification model for determining whether or not a baseball team is going to win a game as local.

![alt text](data:image/jpeg;base64,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)

## Overview
### - Exploratory Data Analysis of housing data (Insights):

- Missing values handling
- All numerical variables
- Distribution of numerical variables
- Categorical variables
- Cardinatily of categorical variables
- Outliers
- Relationships between dependent and independent features


### - Feature engineering framework:

- Splitting data into train and test set with stratified sampling tecnique to preserve distributions found in the housing data
- Creation of an advanced custom transformation pipeline with helpfull tools such as: median imputer, log normalization, custom column modifiers, rare category handler, NaN dropper, categoric variable encoder and variables scaler. (to clean and transform in a fast way future raw sets)

*Note: I could have used ScikitLearn tools such as imputer or Ordinal Encoder, however to add more value to the project and have more control I defined my own cleaning functions*

### - Feature selection framework:

-Use filter algorithms simple methods such as Chi square and Correlation matrix methods to have an initial visualization.

- Different regression embeded methods will be used to determine feature importance and select the best features to feed our models:
- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- XgBoost Regression
- Permutation Regression

*I propose 2 ways of selecting best features, one is simply selecting the top occurrences total sum of the counts, the second one is selecting the the features that appeared as a top in at least 2 different models*

### - Model selection, training and tunning:
Diferent algorithms to find the one with the best metrics and results for this problem

Models proposed:
- Linear Regressor
- Decision Tree Regressor
- Random Forest Regressor
- Support vector machine regressor
- KG-Boost Regressor
- K-n Neighbor regressor
- Lasso Regressor

### - Results summary

A regressor tool for estimating housing sale price was developed from scrath with excelent results, reaching a 88% accuracy in test set. All steps and assumptions were important to reach this result

