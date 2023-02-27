# Credit-Risk Project

The goal of the project is to predict the risk of financial failure based on historical data. 

Banks and financial organizations use the historical data on customers' behaviour to predict the probability of future 
defaults of credit card borrowings. 

Banks can use credit risk prediction to decide whether to issue a credit card to the applicant.

## Data Sets
for this project, we have 2 different datasets:

* **Application Records**: all data related to the demographic information of applicants
* **Credit Records**: historical credit card status of each applicant

Applicant ID is a primary key to joining datasets.
![image](https://user-images.githubusercontent.com/53322705/221466018-94cdc7c3-2168-4f93-a4ec-d63e87d59dd9.png)

The dat set containes an imbalanced label:
## Project Phases
The project was led in 2 major phases:
* Exploratory Data Analytics: 1) Data Cleaning, 2) Feature engineering
* Predictive modeling

## Modeling
Developed 3 major predictive models:
* Random Forest
* XGBOOST
* CATBOOST

## Results	
The model metrics are saved in a table for a fast and clear comparison:

|NO|Model             | accuracy_score | precision_score | recall_score   | roc_auc_score| f1_score|
|- | -----------------| -------------- | --------------  | -------------- | -------------| --------|
|1 |randomforest_Final|   0.864091     |     0.888571    |   0.678404     |   0.817851   |0.769394 |
|2 |xgboost_model_fin |   0.781087     |     0.952576    |   0.363041     |   0.676985   |0.525722 |
|3 |ctboost_model_fin |   0.867162     |     0.921760    |   0.658228     |   0.815100   |0.768016 |

Catboost model has a better performance to predict high-risk applicants. Since we have an imbalanced data,
 the recall score can be an important metric for this project. Catboost has the highest precision and recall scores.
