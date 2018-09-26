# ML_Basics


Variables are classified as

A. Quantitavtive 

B. Qualitative 

---------------
A. Quantitavtive 
- 1. Descrete : Whole number - Ex. Age
- 2. Contineous : Ex Salary

B. Qualitative :
- 1. Nominal : No order  Ex. Gender, Region
- 2. Ordinal : Ex. Size of Shirt, Rating,
---------------
Depending on type of dependent variable you have you will choose Linear Or Logistic Regression Model.

y = mx + b

- If dependent variable y is numerical then use Linear Regression.
- If dependent variable y is categorical or Qualitative then use Logistic Regression.

y - dependent variable/ Target / label / response
x - independent variable / Features / Covariates / predictors

Supervised & Unsupervised Learning :
- When we have x & y values and we try to link them then that is called Supervised 

---------------
Simple linear regression:
- There is on one x and one y

Multiple linear regression :
- There are x1,x2,x3... and one y 
---------------

[Parsimony Principle ]

- Don't add unnecessary variables if not needed or e is same.

y = B0 + B1X1 + B2X2 + .... + e

e is difference between actual and predicted value.

---------------
Model Evaluation Errors :
- MAE
- MSE
- RMSE

[info http://scikit-learn.org/stable/modules/model_evaluation.html]

https://datafai.com/2017/10/31/python-machine-learning-linear-regression-with-scikit-learn/

R^2 =  Coefficient of determination 
adjusted R^2 = Compensation of #of variables

adjusted R^2 <= R^2

---------------

1. Mostly in scikit learn Make everything numerical 
2. x - features | y - labels
3. Standardize data
4. Split data into train and test 
5. Instantiation of Model
- Create instance of Model
- Fit (train data)
- transform/predict (test data)
---------------

ML Models:

1. Linear Regression
2. Logistic Regression
3. Decision Tree & Random Forest
4. PCA
5. KNN
6. Naive Bayes
7. K-Means
8. SVM

