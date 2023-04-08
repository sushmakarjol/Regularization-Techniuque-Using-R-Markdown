# Regularization-Techniuque-Using-R-Markdown
A college dataset from the ISLR is used for the study. 'Glmnet'  package  is used to perform the Ridge and the Lasso Regression techniques

Ridge and Lasso are two common regularization techniques used in linear regression to address the problem of overfitting.

Ridge Regression:
Ridge regression adds a penalty term to the cost function that is proportional to the square of the magnitude of the coefficients. 
The penalty term shrinks the coefficients towards zero, reducing their variance and making the model more robust to noise.
Ridge regression is useful when there is a high multicollinearity among the predictor variables.

Lasso Regression:
Lasso regression also adds a penalty term to the cost function, but it uses the absolute value of the coefficients instead of their square. 
This results in some of the coefficients becoming exactly zero, effectively eliminating them from the model. 
Lasso regression is useful when there are many irrelevant variables in the dataset.

Both Ridge and Lasso techniques help to prevent overfitting by reducing the complexity of the model, 
but they differ in the way they penalize the coefficients. Ridge regression is used when all the variables are important, 
whereas Lasso regression is used when some variables are more important than others. 
The choice between these techniques depends on the specific problem at hand and the nature of the dataset.





