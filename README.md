# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Open new file in jupiter notebook.
<br>

### Step2
Import the neccessary libraries and load the data.
<br>

### Step3
Define input (Volume, Weight) and output (CO2)
<br>

### Step4
Create regression model
<br>

### Step5
Predict for new input
<br>

## Program:
```
mport pandas as pd
from sklearn import linear_model
df=pd.read_csv("car (1).csv")
x=df[["Volume","Weight"]]
y=df["CO2"]
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))

```
## Output:

<img width="805" height="350" alt="Screenshot 2026-03-23 222040" src="https://github.com/user-attachments/assets/67c2ba3e-57e1-4475-ab67-ce442a1a9580" />


<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
