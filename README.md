## Analysis of A/B Test Results
An e-commerce website has submitted the results of an A/B test run for analysis to determine whether they should try a new page design to increase conversions. This notebook analyzes these results using bootstrapping for hypothesis testing and a logistic regression model. Completed as part of the requirements for Udacity's Data Analysis Nanodegree.

#### EDA
Remove miscategorized users from the dataset, drop duplicate users, calculate various observed statistics for later use during analysis.

#### Statistical Analysis
Conduct bootstrap hypothesis testing, plot histogram of conversion differences as simulated under the null, interpret p-value, verify with z-test, verify with logistic regression model, explore possible correlation between user country and probability of conversion.

#### Technologies
Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, StatsModels

#### Conclusions
* There is no evidence to suggest that the new page design will create more conversions than the old page design.
* User country and probability of conversion do not appear to have a relationship.

#### Date created
2018.11.02
