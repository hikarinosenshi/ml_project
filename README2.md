## Data Cleansing

- Remove duplicate rows
- Consider removing columns/features with high percentage of NaN
- Eliminate correlated variables (collinearity)
- https://towardsdatascience.com/data-cleansing-where-to-start-90802e95cc5d
    - Methodology (C-R-A-I)
        - Consistency (Every column of the data should be consistent on the same scale.)
        - Rationality (All the values in each column should comply with common sense.)
        - Atomicity (The data entries should not be duplicated and the data column should not be dividable.)
        - Integrity (The data entries should have all the features available unless null value makes sense.)
- https://towardsdatascience.com/data-preparation-for-machine-learning-cleansing-transformation-feature-engineering-d2334079b06d
    - Data Cleansing
        - Dealing with missing values
        - Dealing with outliers
        - Correcting typos
        - Grouping sparse classes
        - Dropping duplicates
    - Data Transformations
        - Categorical encoding
        - Dealing with skewed data
        - Bias mitigation
        - Scaling
        - Rank transformation
        - Power functions
    - Feature Engineering
        - Feature extraction, and 
        - Capturing Feature Relationships (Possible methods to derive relationships include calculating the sum, the difference, the product or the quotient.)

## FEATURE SELECTION
- https://towardsdatascience.com/feature-selection-techniques-in-machine-learning-with-python-f24e7da3f36e
    - Univariate Selection (scikit-learn library SelectKBest class)
    - Feature Importance (Tree Based Classifiers)
    - Correlation Matrix with Heatmap

- https://towardsdatascience.com/the-5-feature-selection-algorithms-every-data-scientist-need-to-know-3a6b566efd2
    - Filter Methods
        - Pearson Correlation
        - Chi-Squared
    - Wrapper Based Method
        - Recursive Feature Elimination
    - Embedded Method
        - Lasso: SelectFromModel
        - Tree-based: SelectFromModel
    - https://towardsdatascience.com/feature-selection-with-pandas-e3690ad8504b (same as above)



> Written with [StackEdit](https://stackedit.io/).
