# Implementation-of-Linear-Regression-Using-Gradient-Descent
# Date: 22-04-2026
## AIM:
To write a program to predict the profit of a city using the linear regression model with gradient descent.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import the necessary libraries.
2. Read the csk file.
3. Assign the initial parametre.
4. In iteration find the partial derivtive of m and b .
5. Update the values of m and b in the for loop itself.
6. print the values of slope and intercept.
7. Plot the data in the graph.
8. Run the program.

## Program:
```
/*
Program to implement the linear regression using gradient descent.

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
data = pd.read_csv("Startup.csv")
X=data['R&D Spend'].values
Y=data['Profit'].values
X=(X-X.mean())/X.std()
m=0
b=0
lenr=0.01
epo=1000
for i in range(epo):
    Y_pred=(m*X)+b
    dm=(-2/n)*np.sum(X*(Y-Y_pred))
    db=(-2/n)*np.sum(Y-Y_pred)
    m=m-lenr*dm
    b=b-lenr*db
print("Slope:",m)
print("Intercept:",b)
Y_pred=m*X+b
plt.scatter(X,Y,label="Actual Data")
plt.plot(X,Y_pred,label="Best fitted")
plt.xlabel("R&D Spend")
plt.ylabel("Profit")
plt.title("Gradient descent")
plt.legend()
plt.show()

Developed by: MUTTHU M
RegisterNumber:  212225040269
*/
```

## Output:
<img width="918" height="565" alt="image" src="https://github.com/user-attachments/assets/7bd5d3a6-7482-421a-b52e-171c29339206" />

## Result:
Thus the program to implement the linear regression using gradient descent is written and verified using python programming.
