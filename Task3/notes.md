Feature scaling is necessary because features like Salary and Age have very
different ranges. Models such as Linear and Logistic Regression use distance-
based optimization, and scaling ensures that no feature dominates the learning
process due to its magnitude.


Linear Regression is used for HousePrice prediction because the target variable is continuous and numerical. The objective is to estimate an exact numeric value based on input features, which makes linear regression the appropriate choice.

Logistic Regression is used for BuyHouse prediction because the target variable is binary (Yes/No or 1/0). Logistic regression is designed for classification tasks and predicts the probability of belonging to a particular class, making it suitable for this problem.

Analyze impact of outliers

Outliers can significantly affect model performance by pulling the regression
line toward extreme values, leading to poor generalization. In linear models,
outliers can inflate error metrics like RMSE. 


methods to detect overfitting

Overfitting can be detected by comparing training and validation performance.
A large gap indicates overfitting. Other methods include cross-validation,
learning curves, and monitoring performance on unseen test data.

	