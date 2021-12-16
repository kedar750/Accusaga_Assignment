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
-	Customer_id column dropped as it is irrelevant.
-	Standardization used for scaling the data.
-	There are some outliers are present, using inter-quartile range outliers are removed.
-	Simple train-test-split validation method used as data is not overfitted.

# EDA -
![var1 scatterplot](https://user-images.githubusercontent.com/82714026/146306618-82823404-3066-44e5-91dc-90e6ccd789b3.png)
- Scatterplot shows us Var1 distribution and using this we can find out the outliers.

![var2 scatter](https://user-images.githubusercontent.com/82714026/146306623-2ccd6ee4-ce89-4f27-8560-04834ff06add.png)
- This scatterplot also shows Var2 distribution, also this shows outliers.

![group count](https://user-images.githubusercontent.com/82714026/146298584-dcf696f1-1180-4849-b3b0-f99b80645f62.png)
- This plot shows count of each group of customers, G1 having highest customers amongst others.

![category count](https://user-images.githubusercontent.com/82714026/146298554-7b37ad41-e2c7-4f50-8b19-aae247c11ea2.png)
- Count plot shows me how customers are splitted amongst category.

- ![rating count](https://user-images.githubusercontent.com/82714026/146298653-3d98406d-90e2-4c87-b463-d9e6d9197ad6.png)
-This also shows count of ratings.

![Purchased count](https://user-images.githubusercontent.com/82714026/146298647-35f38e32-83fd-43cd-afb6-d73f965bd2e9.png)
- This count plot shows that count of purchased of ABC product is balanced.

![category var1 group catplot](https://user-images.githubusercontent.com/82714026/146298562-a4964dea-61a0-45d7-bcaa-891fa7945756.png)
-This graph shows us the count for particular group for particular category based on Var1.

![correlation](https://user-images.githubusercontent.com/82714026/146298573-6a93af5f-2e3d-4d6a-bd77-4a663394916d.png)



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
