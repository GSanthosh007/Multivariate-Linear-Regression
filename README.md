# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import panda as pd
### Step2
Import linear model from sk learn
### Step3
Read the csv file
### Step4
Find the multivariate regression
### Step5
Display the output
## Program:
```
#Developed by: SANTHOSH G
#Register Number: 212223240152

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))
```
## Output:
![Screenshot 2024-05-12 220711](https://github.com/GSanthosh007/Multivariate-Linear-Regression/assets/147527586/9e094d5f-56b7-49d5-bca5-24c58ab3717c)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
