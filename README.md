# ml_project
Machine Learning Project

Housing Market Consultants
We have been hired by a construction company to research which ‘cosmetic’ features add the most value to a house.
The construction company is looking to buy old houses to remodel them. They need to understand which features will add the most value to the house.


- Remove duplicates (rows)
- Calculate NaN of each column
- Missing value imputation if needed. (Knn, mean, etc…)
- Select subset of features that add the most value (top 10)(chi-square, f-test, p-test)(feature and model selection jump start by Aiko)
- Lasso to select features?
- Check for multicollinearity
- Check for multicollinearity, Linearity, Constant Variance(Homoscedasticity), Normality, Independent Errors. For multiple linear regression, these assumptions should be checked and confirmed for each predictor variable to help ensure a valid model. 
- Check for normality of the Y (dependent variable)( this will indicate 
- Select those features that are valid for our customer requirements


- Create model with best features

- Data Analysis (Percentage of NaN in each column. It will help us identify which columns to remove)

- Check for multicollinearity, Linearity, Constant Variance(Homoscedasticity), Normality, Independent Errors. For multiple linear regression, these assumptions should be checked and confirmed for each predictor variable to help ensure a valid model. 
- 


- Feature engineering (If it is a Descriptive model then we may include some columns that we would not include if the goal is a Predictive model.) (Either by adding brand new features from outside sources, Or adding new features derived from the original features, Or using such new features to replace the original features,  Eliminate any unnecessary features. (Combine number of bedrooms and number of bathrooms)
- Should we ignore categorical features? (dumminfication) (for data analysis use pandas, for better performance us sklearn)
