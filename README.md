# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step2:
Read the csv file.

Step3:
Get the value of X and y variables.

Step4:
Create the linear regression model and fit.

Step5:
Predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm cube.

Step6:
Print the predicted output.

## Program:
```
Developed by: GUGHAN S
Reg.No: 212223240043
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
print("Account",regr.predict([[3300,1300]]))
```
## Output:
![ex10](https://github.com/GUGHAN-3001/Multivariate-Linear-Regression/assets/150009432/7bce4f50-693a-44a0-99dd-9992c69d52ad)




## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
