This note summerize methods to reduce overfitting in different machine learning method.

1. **Linear Regression** Add regularization term in the loss function.

  - Lasso: $L1$ ($L0$) norm
  - Ridge: $L2$ norm
  - Elastic net: $\beta L1 + (1-\beta)L2$

2. **Tree Based Modeling**

  - Set limitations on tree width and depth.

3. **Navie Bayesian**

  - Laplacian smooth for multinomial Naive Bayesian.
