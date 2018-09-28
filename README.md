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
ML Terms :

Cost Function : Goal is to minimize cost function

![cost](https://user-images.githubusercontent.com/27011804/46183422-796d2080-c2ee-11e8-83d8-401faa2b02db.PNG)

[Source : Andrew NG]

Gradient Descent : Gradient descent is an optimization algorithm used to find the values of parameters (coefficients) of a function (f) that minimizes a cost function (cost). [Source: https://machinelearningmastery.com/gradient-descent-for-machine-learning/]

![](https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2017/03/06100746/grad.png)

---------------
ML Models:

1. Linear Regression -- Supervised
2. Logistic Regression (For Classification ) Supervised
3. Decision Tree & Random Forest (For Classification & Regression) Supervised
4. PCA -- Unsupervised
5. KNN -- (For Classification & Regression)
6. K-Means (For Classification & Regression) Unsupervised
- Ref: https://www.datascience.com/blog/k-means-clustering
Hirarchical Clustering :
- Agglomerative (Bottom-up clustering Method)
- Divisive (Top-down clustering Method )
7. Naive Bayes
8. SVM

[ Classification Model : https://medium.com/fuzz/machine-learning-classification-models-3040f71e2529 ]
