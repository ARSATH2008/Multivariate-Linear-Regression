# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import the required libraries and define the input dataset with multiple independent variables and one dependent variable.

### Step2
Split the dataset into input features X and target output y.
### Step3
Train the Multivariate Linear Regression model using the training data.
### Step4
Predict the output for new input values and display the result.

## Program:
```


\*
DEVELOPED BY : J.MOHAMED ARSATH
REGISTER NUMBER: 212225040237
import numpy as np
from sklearn.linear_model import LinearRegression

# Input data
# [Feature1, Feature2]
X = np.array([[1, 2],
              [2, 3],
              [4, 5],
              [3, 6],
              [5, 8]])

# Output data
y = np.array([3, 5, 8, 10, 13])

# Create model
model = LinearRegression()

# Train the model
model.fit(X, y)

# Predict output for new data
new_data = np.array([[6, 9]])
prediction = model.predict(new_data)

# Display coefficients and prediction
print("Coefficients:", model.coef_)
print("Intercept:", model.intercept_)
print("Predicted Output:", prediction[0])


```
## Output:

### Insert your output

<img width="1138" height="709" alt="image" src="https://github.com/user-attachments/assets/1a4c3cb4-f0ea-4eb9-aff8-bd0c4911b762" />


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
