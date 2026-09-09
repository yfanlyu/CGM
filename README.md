## CGM
This file contains all of the dataset we have used in our project and provides the detailed coding on data merging, cleaning, and analysing

## pre-test
This file only contains Tradhist dataset where we applied it in CART, RF, and LASSO, because we want to check the potential important features in our primary dataset and get rid of the less important ones so as to retain as much information as possible when doing data cleaning. What's more, we want to see how different it would be in terms of model selection when we extend this primary dataset to include other covariates (i.e. greenhouse gas emissions and inflation rate).

## Project paper
By running this project, we try to answer the question whether machine learning (methods such as LASSO, Decision Tree, and Random Forest) can improve the prediction of bilateral international trade flows. Our result shows that ML can improve prediction compared to that of a linear regression. However, the relatively small improvement of ML over the linear model suggests that the ML methods can be advantageous when trade flows exhibit complex, evolving patterns and when multiple variables interact in ways that may not be well captured by traditional linear models.

The dataset we applied is mainly CEPII TRADHIST bilateral trade data, covering 1827–2014, combined with GHG emissions data and World Bank average price index (API) data. The final analysis covers 1990–2014 with 12,227 observations, using 90% for training and 10% for testing.
