# Machine-Learning
This repository contains my personal side projects in machine learning. I attemped to build two types of simple linear regression models and one logistic regression model using Numpy and PyTorch. These models can be found [here](https://github.com/Heyimjiamin/Machine-Learning/tree/main/Regression%20Modeling).

### Simple Linear Regression Model
I predicted salary data based on work-experience data using simple linear regression modeling (y = w*x + b). I built two types of simple linear regression models. One is manual calculation, and the other is creating a neural network using PyTorch. The methods used are:
1. Cost function: Mean Squared Error (MSE)
2. Optimizer: Gradient Descent

The Coefficient of Determination (R^2) is calculated to check the model's accuracy.


### Multiple Linear Regression Model / Logistic Regression Model
The aim of the model is to predict people's chances of getting diabetes based on four features (age, weight, blood sugar, and gender). In data preprocessing, I classified genders with label encoding and adjusted the scale of the x data via standardization. 
The logistic regression model is built using the torch nn module. The methods used are:
1. Cost function: Binary Cross Entropy (BCE)
3. Optimizer: Stochastic Gradient Descent (SGD)

Finally, the predicted outcomes are converted by a sigmoid function into binary, and the model's accuracy is estimated based on the proportion of correct predictions.
