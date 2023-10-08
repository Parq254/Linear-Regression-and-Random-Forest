# Linear-Regression-and-Random-Forest
Dive into which regression technique best fits prediction of airbnb price.

Let's look at the two in deapth to better understand which of the two works better.

**_Random forest regression_** is based on the ensemble machine learning technique of bagging. The two key concepts of random forests are:

- Random sampling of training observations when building trees.
- Random subsets of features for splitting nodes

Random forest regressions also discretize continuous variables since they are based on decision trees, which function through recursive binary partitioning at the nodes. This effectively means that we can split not only categorical variables, but also split continuous variables. Additionally, with enough data and sufficient splits, a step function with many small steps can approximate a smooth function for predicting an output.

**_Linear regression_** on the other hand is the standard regression technique in which relationships are modeled using a linear predictor function, the most common example of **y = Ax + B**. Linear regression models are often fitted using the least-squares approach.

There are also four main assumptions in linear regression:

- A normal distribution of error terms
- Independence in the predictors
- The mean residuals must equal zero with constant variance
- No correlation between the features
So how do we differentiate between random forest regression and linear regression independent of the problem statement?

The difference between random forest regression versus standard regression techniques for many applications are:

- Random forest regression can approximate complex nonlinear shapes without a prior specification. Linear regression performs better when the underlying function is linear and has many continuous predictors.
- Random forest regression allows the use of arbitrarily many predictors (more predictors than data points is possible)
- Random forest regression can also capture complex interactions between predictions without a prior specification
- Both will give some semblance of a “feature importance.
linear regression feature importance is much more interpretable than random forest given the linear regression coefficient values attached to each predictor.

**Conclusion.**
Random Forest tends to perform better than Linear Regression when: The data has a large number of features. The data has complex, non-linear relationships. The data contains missing values or outliers

