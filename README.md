## Analysis of A/B Test Results
An e-commerce website has submitted the results of an A/B test run for analysis to determine whether they should try a new page design to increase conversions. This notebook analyzes these results using bootstrapping for hypothesis testing and a logistic regression model. Completed as part of the requirements for Udacity's Data Analysis Nanodegree.

#### EDA
Removed miscategorized users from the dataset, dropped duplicate users, calculated various observed statistics for later use during analysis.

#### Statistical Analysis
Conducted bootstrap hypothesis testing, plotted histogram of conversion differences as simulated under the null, interpreted p-value, verified with z-test, verified with logistic regression model, explored possible correlation between user country and probability of conversion.

#### Technologies
Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, StatsModels

#### Conclusions
* There is no evidence to suggest that the new page design will create more conversions than the old page design.
* User country and probability of conversion do not appear to have a relationship.

#### Date created
2018.02.11
