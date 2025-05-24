# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import Pandas library.

### Step2 : Import Linear_model from sklearn.

### Step3 : Read the csv file using pandas library.

### Step4 : Enter the parameters of the linear function.

### Step5 :Print the parameters of the linear function.


## Program:

```
Developed by: Pooja.P
Reg No: 212224100041

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("/content/car (1).csv")
x=df[["Volume","Weight"]]
y=df["CO2"]
regression = linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))


```
## Output:

![alt text](<Screenshot 2025-05-24 151550.png>)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.