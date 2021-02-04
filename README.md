# Computer vision - Glasses or no glasses

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

The purpose of this project is to create a `Machine Learning model` which will be able to `predict` dthe average price of the spanish railway ticket.

It would be applied different `regression` modeld and their performance are going to be compared by `R square score` on the `test sample` and `training sample`

## Technical details about the project:

 :round_pushpin: **Programming language:** `Python`

 :round_pushpin: **Library:** `scikit-learn`

 :round_pushpin: **Applied algorithm:** `Decision tree`, `Bagging`, `Boosting`, `Random forest` and `Xgboost`
 
## Data sources: 

- Kggle: https://www.kaggle.com/thegurusteam/spanish-high-speed-rail-system-ticket-pricing

## Some figures:

- Map with the railway city connections:

![alt text](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Before_modeling/Figures/Screenshot%202021-01-25%20at%2012.57.09.png)

- Cross validation, boosting model:

![alt text](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Modeling/Boosting/Figures/cv_boosting.png)

- Actuals vs predicted, boosting model:

![alt text](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Modeling/Boosting/Figures/cv_pred_err_boost.png)

## Results:

- Application of fine tuning (after the green line):

![alt text](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Results/table_results.png)

## Conclusion:

As per the above `results table`, it seems the `Boosting model is the best one`, it has the `greatest R square score on the test sample`, equal to `87.73`

However, taking into consideration the `R square score on the training sample`, the `Xgboosting model seems to have the greatest score`. This result is according to the conclussion made before, which suggests that in `this model there is overfitting problem`, or at leats, this model overfitted the data more than other models

## Links to notebooks:

## [:white_check_mark: Data cleaning](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Before_modeling/1.Data_cleaning.ipynb)
## [:white_check_mark: Data exploration](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Before_modeling/2.Data_exploration.ipynb)
## [:white_check_mark: Data transformation](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Before_modeling/3.Data_transformation.ipynb)

## [:white_check_mark: Decision trees](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Modeling/Dec_tree/Dec_trees.ipynb)
## [:white_check_mark: Bagging](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Modeling/Bagging/Bagging.ipynb)
## [:white_check_mark: Boosting](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Modeling/Boosting/Boosting.ipynb)
## [:white_check_mark: Random forest](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Modeling/Ran_forest/Ran_forest.ipynb)
## [:white_check_mark: Xgboost](https://github.com/lajobu/Renfe_pred_avg_price/blob/master/Modeling/Xgbost/xgboost.ipynb)
