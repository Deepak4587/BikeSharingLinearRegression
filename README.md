# Bike Sharing
> This project is to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Data Preparation](#data-preparation)
* [Model Building](#model-building)
* [Model Evaluation](#model-evaluation)
* [Conclusions](#conclusions)


## Problem Statement
- BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.
- They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- They now want to understand the factors affecting the demand for these shared bikes in the American market.
- They mainly want to know: which variables are significant in predicting the demand for shared bikes, and how well those variables describe the bike demands


## Data Preparation
- Dummy values were added in place of variables that are categorical in nature.
- The unnecessary columns were removed from the dataset.
- A taining set and test set were created, after scaling the data.


## Model Building
- The variable with the highest correlation was selected and the model was trained using that. The R2 value was found.
- Another set of variables were added on by one based on the correlation values and the model was trained.
- VIF and p-values were used to find the variables that need to be removed from the dataset.


## Model Evaluation
- Residual analysis was done on the training set.
- Predictions were made using the final model.
- The R2 score was found and compared with that of the train data.
- The coefficients with most impact were found.


## Conclusions
- There are factors that have both positive and negative impact on the target variable.
- The categorical variables do have a good impact on the target variable.
- All the factors that were analysed and had an impact are found and documented.


## Contact
Created by [@Deepak4587] - feel free to contact me!
