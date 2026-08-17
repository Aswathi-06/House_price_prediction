House Price Prediction uses the Linear Regression model in Machine Learning to predict house prices based on different features of the houses.
The California Housing dataset is loaded from Scikit-learn using the fetch_california_housing() function. It contains 20,640 samples and 8 input features related to housing and population characteristics.
Linear Regression is a supervised machine learning model that finds a relationship between the input features and the target value and uses this relationship to predict a continuous numerical value.
Linear Regression is used because this is a regression problem, where the goal is to predict a continuous value such as house price. It is also simple and easy to understand.
The dataset is divided into training and testing sets using an 80-20 split. 
StandardScaler is used to scale the input features.
The performance of the model is evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.
A histogram and correlation heatmap is used for visualization.
An Actual vs. Predicted House Prices scatter plot is also created to compare the actual house prices with the prices predicted by the model.
