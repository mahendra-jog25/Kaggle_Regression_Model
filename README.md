# kaggle_Regression_Model

## E commerce Customers 

### Introduction
1. This dataset is having data of customers who buys clothes online. Our main objective is to predict the Yearly amount spent by the customers.
2. Data consists of 500 rows and 8 variables.
3. In my analysis I have tried to explored if data following all linear assumption and also fitting for different type of regularization like L1, L2 and elastic models. 

model	Mean Absolute Error	Mean Absolute percent error	Mean Squared Error	Root Mean Squared Error	R2 score
0	Base	7.851377	1.634675	94.557795	9.724083	0.984926
1	SF	7.849601	1.634302	94.502920	9.721261	0.984935
2	Rigde	7.849090	1.634241	94.495757	9.720893	0.984936
3	Lasso	7.848690	1.634191	94.492755	9.720738	0.984937
4	Elastic	7.841249	1.633292	94.390138	9.715459	0.984953
5	RandomForest	15.527252	3.212153	495.180382	22.252649	0.921062


## Conclusion:
1. Model with only 2 features i.e. "Length of Membership" and "Time on App" had RMSE score of 30.19 and variance can be explained 85%.
2. Comparing model with two feature with base model, has R-square score decrease from 98 to 85 and RMSE score increased from 9 to 30.
3. Therefore model with 2 feature "Length of Membership" and "Time on App" dont stands out much when compared with model having 3 features "Length of Membership", "Time on App" and "Avg. Session Length".
4. Risk- if dropping out any of this 3 features will impact overall score.
5. Concluding feature "Length of Membership", "Time on App","Avg. Session Length" variables are affecting the target the most.

## Limitation:
Data size provided is small for 500 size, which can lead to higher R square score and resulting to underfitting problem. Underfitting problem can be overcome by adding me feature and appropriate data size. Adding feature like date and previous purchase history would be effective for analysis. Based on trend and seasonality for date can provide insight for time spending pattern and yearly spending pattern by customers.

