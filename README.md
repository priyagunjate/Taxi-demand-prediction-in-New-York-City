# Taxi-demand-prediction-in-New-York-City


Objectives:

Task 1: Incorporate Fourier features as features into Regression models and measure MAPE. 

Task 2: Perform hyper-parameter tuning for Regression models.

2a. Linear Regression: Grid Search 

2b. Random Forest: Random Search

2c. Xgboost: Random Search 


Task 3: Explore more time-series features using Google search/Quora/Stackoverflow to reduce the MAPE <12%



Procedure for accomplished above objectives is as :

Task 1:

As the datsets is in time series ,convert into frequecy domain to get frequecy and amplitude
values using fourier transform.And these Frequecy and amplitude of region_cum feature can be
used as features.These features are important becuase of repeating structure of datasets.
  
    1.Find the frequecy according to maximum amplitude
    
    2.sort the frequecy to get important frequecy and corresponding amplitude.This is our
      new feature.
    
    3.Concatenate newfeature with datasets .(this datsets is used for training and testing
      the model to get Train MAPE & Test MAPE)
Task2:

Perform hyper-parameter tuning for Regression models.

  2a. Linear Regression: Grid Search
  
  2b. Random Forest: Random Search
  
  2c. Xgboost: Random Search
  
Task 3:
  Use time series feature in task1
  
  Split the Train & test dataset into 75-25%
  
  Use cluster size=30
  
  here, I used LSTM model and MAPE <12% (It is new model )




Refrence applied ai

