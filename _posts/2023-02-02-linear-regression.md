---
layout: post
title: Linear Regression
date: 2023-01-01 12:00:00 +530
categories: [datascience,beginner,analytics]
tags: [datascience,analytics,machinelearning,beginner,projects,linearregression] #TAG Names
---

# Linear Regression

Here's what ChatGPT had to say about Linear Regression:

![ChatGPT](https://ibb.co/svnrMjH)


#Beginning

Let's take a look at this simple code:

```Python
from sklearn.linear_model import LinearRegression
import numpy as np

# Input training data
x_train = np.array([[1], [2], [3], [4], [5]])
y_train = np.array([[1], [2], [3], [4], [5]])

# Train the model
reg = LinearRegression().fit(x_train, y_train)

# Predict output for test data
x_test = np.array([[6],[7]])
y_pred = reg.predict(x_test)

print("Prediction:", y_pred)
```

This code trains a linear regression model on a simple 1-dimensional training data set, x_train and y_train, and then uses the trained model to make a prediction for a few test data points x_test.

Output:

```
[[6.]
[7.]]
```