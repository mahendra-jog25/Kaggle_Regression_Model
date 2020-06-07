# Kaggle_Regression_Model

## E commerce Customers 

### Introduction
Dataset provided consists of 500 rows and 8 variables. It is data of customers who buys clothes online. Our main objective is to predict the Yearly amount spent by the customers. Data consists of 500 rows and 8 variables.In my analysis I have tried to explored if data following all linear assumption and also tried fitting for different type of regularization like L1, L2 and elastic models. 

### Conclusion:
1. Model with only 2 features i.e. "Length of Membership" and "Time on App" had RMSE score of 30.19 and variance can be explained 85%.
2. Comparing model with two feature with base model, has R-square score decrease from 98 to 85 and RMSE score increased from 9 to 30.
3. Therefore model with 2 feature "Length of Membership" and "Time on App" dont stands out much when compared with model having 3 features "Length of Membership", "Time on App" and "Avg. Session Length".
4. Risk- if dropping out any of this 3 features will impact overall score.
5. Concluding feature "Length of Membership", "Time on App","Avg. Session Length" variables are affecting the target the most.

### Limitation:
Data size provided is small for 500 size, which can lead to underfitting problem and and resulting to higher R square score. Underfitting problem can be overcome by adding me feature and appropriate data size. Adding feature like date and previous purchase history would be effective for analysis. Based on trend and seasonality for date can provide insight for time spending pattern and yearly spending pattern by customers.

