Machine Learning (ML) considered as a subset of Artificial Intelligence (AI) is the scientific study of algorithms and statistical models that computer systems use to effectively perform a specific task without using explicit instructions, relying on 
patterns and inference instead. PyCaret's Regression Module is a supervised machine learning module that is used for estimating the relationships between a dependent variable (Target) and one or more independent variables (Features). On this project the typical workflow of PyCaret’s Regression module steps 
Setup ➡️      Compare Models ➡️ Analyze Model➡️ Prediction        ➡️ Save Model
Were followed to experiment and come up with the best regression model that predicts the alcohol on the Red Wine Quality Data Set, available on the UCI machine learning repository (https://archive.ics.uci.edu/ml/datasets/wine+quality). After several experiments including testing the models with an unseen data, top three models based on R2, Cat Boost Regressor (CBR), Light Gradient Boosting Machine (LGBM) and Extreme Gradient Boosting (EGB) with R2 of 0.7818, 0.7527 and 0.7448 respectively were selected as winning models. Further more for best performance results the top three models were tested as blended and stacked. The final stacked model has come with the best performance metrics of R2= 0.7824. MAE = 0.3286, MSE = 0.2379, RMSE = 0.4860, RMSLE= 0.0414, and MAPE=0.0312. At last, this model was finalized and saved as the winning model. This work demonstrates how experimenting with different preprocessing options and observing their impact on model performance, leads to creating best model for the problem in hand. 

Github link:
https://github.com/Solomon-Million/ML_REGRESSION_MODELING

Video link:
https://www.loom.com/share/9c7ffa053c3b49a1bc6189a0ab0b500f?sid=5829e122-3e6f-4e9e-9fa3-a720c80861d1
