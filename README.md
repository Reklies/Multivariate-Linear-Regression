# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
# Python program to implement multivariate linear regression
# Developed by:Reklies J
# Register Number:212223110041
import pandas as pd
from sklearn import linear_model
data=pd.read_csv("cars (1).csv")
x=data[['Weight','Volume']]
y=data[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(x,y)
print('Coefficients:',regr.coef_)
print('Intercept:',regr.intercept_)
predictCO2=regr.predict([[3300,1300]])
print('Predicted CO2 for the corresponding weight and volume',predictCO2)

```
## Output:
![image](https://github.com/Reklies/Multivariate-Linear-Regression/assets/147139232/dde531ea-dd5a-4e0c-9763-79024664aa2e)


### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
