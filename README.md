# House-Price-Prediction
Predicting Price of house by considering ,house age, Distance from public transport, No of convenient stores around house etc.. 
Applied multiple machine learning linear models like simple linear regression, Desicion tree regressor, Random Forest Regressor.

# Data Source
Kaggle

# Data shape
(414,7)

# Data columns
1) Purchase year
2) House age
3) Distance to the nearest MRT station
4) Number of convenience stores
5) Latitude
6) Longitude
7) House price of unit area
 
# Steps Followed
1) Data Import
2) Column Renaming
3) Data cleaning or null value imputation
4) Creating Visualization
5) Train Test spilt
6) Apply feature selection
   SelectKBest with mutual info regressor
7) Model building
   1) Simple linear regression
   2) Decision Tree Regressor
   3) Random Forest Regressor
# Results or Accuracy
1) Simple linear regression 
     1) r2 score                                  0.561
     2) Mean absolute error                       6.86
     3) Mean absolute percentage error            0.0.19437 
  
2) Decision Tree Regressor 
     1) r2 score                                  0.673
     2) Mean absolute error                       5.80
     3) Mean absolute percentage error            0.1556  
     
3) Random Forest Regressor 
     1) r2 score                                  0.766
     2) Mean absolute error                       4.54
     3) Mean absolute percentage error            0.1227
       
# Model Selection on basis of r2score, MAE and MAPE
   Random Forest Regressor(RF) becoz, it has high r2score and lower MAE and MAPE amoungs all the three models. 
