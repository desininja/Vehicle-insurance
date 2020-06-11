# Vehicle-insurance
Data science project


Vehicle Insurance data:
This dataset contains multiple features according to the customer’s vehicle and insurance type.

Business requirement is to increase the clv (customer lifetime value) that means clv is the target variable.

Data Cleansing:

This dataset is pretty clean already, a few outliers are there. Remove the outliers. 
Why remove Outliers?
Outliers are unusual values in dataset, and they can distort statistical analyses and violate their assumptions.

Feature selection:

This step is required to remove unwanted features.

VIF and Correlation Coefficient can be used to find important features.

VIF:  Variance Inflation Factor
It is a measure of collinearity among predictor variables within a multiple regression. It is calculated by taking the the ratio of the variance of all a given model's betas divide by the variance of a single beta if it were fit alone.

Correlation Coefficient:
A positive Pearson coefficient mean that one variable's value increases with the others. And a negative Pearson coefficient means one variable decreases as other variable decreases. Correlations coefficients of -1 or +1 mean the relationship is exactly linear.

Log transformation and Normalisation:
Many ML algorithms perform better or converge faster when features are on a relatively similar scale and/or close to normally distributed. 


Applying different ML Algorithms to the dataset for predictions. Their accuracies are in notebook.
