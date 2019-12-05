# Santander Kaggle Competition to Predict Customer Satisfaction

### Note: My roc_auc_score on the holdout test set was .83605 which would have won the competition however of course there is the caveat that this competition is 4 years old (2015). My solution just uses a baseline XGBoost model with feature selection done using xgboost feature importances; and XGBoost had an initial release in March of 2014, so XGBoost was available then although I am not sure what percentage of people were using it back then. I tried a ADASYN resampling technique however this produced worse performance. 

![Screenshot of winning results](https://github.com/sethweiland/santander_kaggle_satisfaction_competition/blob/master/Screen%20Shot%202019-12-05%20at%2012.39.37%20PM.png)
