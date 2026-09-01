# SGD-Regressor-for-Multivariate-Linear-Regression

## AIM:
To write a program to predict the price of the house and number of occupants in the house with SGD regressor.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Create the input features and multiple output target data.
2. Initialize SGDRegressor and train it using MultiOutputRegressor.
3. Predict outputs for the training data and a new sample.
4. Compare actual and predicted outputs using scatter plots. 

## Program:
```
/*
Program to implement the multivariate linear regression model for predicting the price of the house and number of occupants in the house with SGD regressor.
Developed by: Surya Prakash S
RegisterNumber: 212225040443

from sklearn.linear_model import SGDRegressor
from sklearn.multioutput import MultiOutputRegressor
import numpy as np
import matplotlib.pyplot as plt

X = np.array([
    [1, 2],
    [2, 1],
    [3, 4],
    [4, 3],
    [5, 5],
    [6, 7],
    [7, 6]
])


Y = np.array([
    [5, 8],
    [6, 9],
    [9,12],
    [10,13],
    [13,16],
    [16,20],
    [17,21]
])

sgd = SGDRegressor(
    max_iter=1000,
    eta0=0.01,
    learning_rate='constant',
    random_state=42
)

model = MultiOutputRegressor(sgd)

model.fit(X, Y)

Y_pred = model.predict(X)

print("\nActual Outputs")
print(Y)

print("\nPredicted Outputs")
print(np.round(Y_pred,2))

new_sample = np.array([[8, 7]])
prediction = model.predict(new_sample)

print("\nPrediction for", new_sample)
print(prediction)


plt.figure(figsize=(6,4))
plt.scatter(Y[:,0], Y_pred[:,0], color='blue')
plt.plot([Y[:,0].min(), Y[:,0].max()],
         [Y[:,0].min(), Y[:,0].max()],
         'r--')
plt.xlabel("Actual Output 1")
plt.ylabel("Predicted Output 1")
plt.title("Output 1: Actual vs Predicted")
plt.grid(True)
plt.show()

plt.figure(figsize=(6,4))
plt.scatter(Y[:,1], Y_pred[:,1], color='green')
plt.plot([Y[:,1].min(), Y[:,1].max()],
         [Y[:,1].min(), Y[:,1].max()],
         'r--')
plt.xlabel("Actual Output 2")
plt.ylabel("Predicted Output 2")
plt.title("Output 2: Actual vs Predicted")
plt.grid(True)
plt.show()
*/
```

## Output:
![multivariate linear regression model for predicting the price of the house and number of occupants in the house](sam.png)

<img width="750" height="582" alt="ex4 ml graph" src="https://github.com/user-attachments/assets/7a11f2bb-0b2c-417f-a278-bb2da2ee8034" />
# SGD-Regressor-for-Multivariate-Linear-Regression

## AIM:
To write a program to predict the price of the house and number of occupants in the house with SGD regressor.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Create the input features and multiple output target data.
2. Initialize SGDRegressor and train it using MultiOutputRegressor.
3. Predict outputs for the training data and a new sample.
4. Compare actual and predicted outputs using scatter plots. 

## Program:
```
/*
Program to implement the multivariate linear regression model for predicting the price of the house and number of occupants in the house with SGD regressor.
Developed by: Surya Prakash S
RegisterNumber: 212225040443

from sklearn.linear_model import SGDRegressor
from sklearn.multioutput import MultiOutputRegressor
import numpy as np
import matplotlib.pyplot as plt

X = np.array([
    [1, 2],
    [2, 1],
    [3, 4],
    [4, 3],
    [5, 5],
    [6, 7],
    [7, 6]
])


Y = np.array([
    [5, 8],
    [6, 9],
    [9,12],
    [10,13],
    [13,16],
    [16,20],
    [17,21]
])

sgd = SGDRegressor(
    max_iter=1000,
    eta0=0.01,
    learning_rate='constant',
    random_state=42
)

model = MultiOutputRegressor(sgd)

model.fit(X, Y)

Y_pred = model.predict(X)

print("\nActual Outputs")
print(Y)

print("\nPredicted Outputs")
print(np.round(Y_pred,2))

new_sample = np.array([[8, 7]])
prediction = model.predict(new_sample)

print("\nPrediction for", new_sample)
print(prediction)


plt.figure(figsize=(6,4))
plt.scatter(Y[:,0], Y_pred[:,0], color='blue')
plt.plot([Y[:,0].min(), Y[:,0].max()],
         [Y[:,0].min(), Y[:,0].max()],
         'r--')
plt.xlabel("Actual Output 1")
plt.ylabel("Predicted Output 1")
plt.title("Output 1: Actual vs Predicted")
plt.grid(True)
plt.show()

plt.figure(figsize=(6,4))
plt.scatter(Y[:,1], Y_pred[:,1], color='green')
plt.plot([Y[:,1].min(), Y[:,1].max()],
         [Y[:,1].min(), Y[:,1].max()],
         'r--')
plt.xlabel("Actual Output 2")
plt.ylabel("Predicted Output 2")
plt.title("Output 2: Actual vs Predicted")
plt.grid(True)
plt.show()
*/
```

## Output:
![multivariate linear regression model for predicting the price of the house and number of occupants in the house](sam.png)

<img width="750" height="582" alt="ex4 ml graph" src="https://github.com/user-attachments/assets/7a11f2bb-0b2c-417f-a278-bb2da2ee8034" />

<img width="1162" height="612" alt="ex4 ml" src="https://github.com/user-attachments/assets/d16d1735-a17a-4aad-b5d2-7db73eaec7e3" />

## Result:
Thus the program to implement the multivariate linear regression model for predicting the price of the house and number of occupants in the house with SGD regressor is written and verified using python programming.


## Result:
Thus the program to implement the multivariate linear regression model for predicting the price of the house and number of occupants in the house with SGD regressor is written and verified using python programming.
