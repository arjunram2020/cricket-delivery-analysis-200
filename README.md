# cricket-delivery-analysis-200
This repository analyzes a dataset of 200+ cricket deliveries from bowlers to predict ball speed and identify key influencing features. Below are the steps through which I performed the analysis:
  Removed outlier points using matplotlib and Seaborn
  Performed null analysis and preprocessing of data
  Implemented many regression models including Ridge, Lasso, XGBRegressor, CatBoostRegressor, RandomForestRegressor, etc.
  Used training split (80% train and 20% test). Also used GridSearchCV implemented through SkLearn which is a cross-validation method to be used towards testing data (20% of training)
  Calculate RMSE and R^2 values (The best functioning model turned out to be XGBoost) 
  Calculated coefficients of each weight through pandas,  contributor (weight) turned out to be Arm Speed
  Calculated Optimal Values for each weight for the best functioning model using SciPy optimization methods like minimize
  Everything is subject to change as more and more data gets added to our dataset so I will constantly update which models work better longterm as the dataset becomes bigger
