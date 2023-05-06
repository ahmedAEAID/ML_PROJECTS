# BOSTON HOUSE PRICE PRDICTIONS
## project description:
- This project predicts home prices in Boston using machine learning. To accomplish this task, the project used six different methods to remove outliers: z-score, interquartile range (iQR), Isolation Forest, Local Outlier Factor, One-class SVM, and DBSCAN. After comparing the performance of these methods, the project decided to use Isolation Forest to remove outliers.

- The project then used two methods, Chi2 and Treed models, to determine feature importance. After identifying the important features, the project trained several machine learning models on the preprocessed data, including SVR, linear regression, decision tree, random forest, and XGBoost. The project then performed hyperparameter tuning on XGBoost and random forest models to find the best performing model. Finally, the project selected XGBoost as the best model for predicting house prices in Boston.

- The project achieved a high accuracy score of 0.92 on the test set using the tuned XGBoost model. 
### Compare Models
![compare models](https://github.com/ahmedAEAID/ML_PROJECTS/blob/main/Boston%20house%20price%20Predictions/Images/output.png)
### Models Scores
![Models Scores](https://github.com/ahmedAEAID/ML_PROJECTS/blob/main/Boston%20house%20price%20Predictions/Images/Models%20Scores.png)
### Residual XGBoost
![Residual XGBoost](https://github.com/ahmedAEAID/ML_PROJECTS/blob/main/Boston%20house%20price%20Predictions/Images/Residual%20Xgb.png)
### Predictions vs Actua
![Predictions vs Actua](https://github.com/ahmedAEAID/ML_PROJECTS/blob/main/Boston%20house%20price%20Predictions/Images/Predictions%20vs%20Actual.png)
