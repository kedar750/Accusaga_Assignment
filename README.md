# Accusaga_Assignment

# Problem statement – 
- In this problem, We are going to predict the quantity of product is taken by each customer. Data contains customer id, first variable, second variable, Group, category, Rating, Purchased abc product.
- Customer Id is the column that gives customers count with their unique Ids,
- Var1 gives you parameter in numerical form that is taken by particular customer.
- Var2 values shows amount that is taken by each customer.
- Group – this columns shows that customer is belongs to particular customer.
- Category -  Category shows that customer is belongs to particular category.
- Rating – Rating given to customer.
- Purchased_ABC_Products – This is our dependent value that shows us count of products purchased by customer.

- Our problem statement is to predict that customer will buy a ABC product or not and Also we have to plot the performance matrix and gain more accuracy without overfitting the model.

# Feature engineering –
-	Customer_id column dropped as it was irrelevant.
-	Standardization used to scale the data.
-	There are some outliers are present using Inter-quartile range outliers are removed.
-	Simple train-test-split validation method used as data is not overfitted.

# EDA - 


# Model Building – 
-	Lazy Classifier (Lazy predict shows all classifier models and using this we are going to check which model performed better.)
-	LGBM Classifier
-	XGB Classifier
# Hyperparameter Tuning - 
- Hyperparameters were tuned using grid search.
- Optimal model found out using tuning.


# Model Interpretation –
-	Model interpretation is done using SHAP values.

# Metric of Evaluation – 
-	Confusion Matrix
-	Precision 
-	Recall 

# Conclusion- 
-	LGBM, XGB, SVC, ADAboost perform almost same.
-	Using hyperparameter tuning find out the best parameter for LGBM.
