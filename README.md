# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import pandas as pd

### Step2
Read the csv file.

### Step3
Get the value of x and y variable

### Step4
Create the linear regression model and fit.

### Step5
Predict the CO2 emission of a car where the weight is 2300kg and the volume is 1300cm cube

## Program:
```
#Developed by: RAJARAMAN V
#Reg.no: 23014299
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
![WhatsApp Image 2023-12-25 at 17 15 44_7c83f6f6](https://github.com/Rajaraman77/Multivariate-Linear-Regression/assets/150319383/b393cded-25a6-4b25-8ca8-acab1f6cf3ec)

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
