# Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn

## AIM:
To write a program to implement the Decision Tree Classifier Model for Predicting Employee Churn.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
STEP 1:Start

STEP 2:Import pandas and read the csv file.

STEP 3:Import Decision tree classifier.

STEP 4:Fit the data in the model.

STEP 5:Find the accuracy score

STEP 6:STOP
## Program:
```
/*
Program to implement the Decision Tree Classifier Model for Predicting Employee Churn.
Developed by: M.ARJUN
RegisterNumber: 212222040012 
*/
/*
import pandas as pd
df=pd.read_csv("CSVs/Employee.csv")
df.head()
df.info()
df.isnull().sum()
df['left'].value_counts()
from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()
df["salary"]=le.fit_transform(df['salary'])
df.head()
x=df[['satisfaction_level','last_evaluation','number_project','average_montly_hours',
      'time_spend_company','Work_accident','promotion_last_5years','salary']]
x.head()
y=df['left']
from sklearn.model_selection import train_test_split as tts
Xtrain,Xtest,Ytrain,Ytest=tts(x,y,test_size=0.2,random_state=100)








from sklearn.tree import DecisionTreeClassifier
dt=DecisionTreeClassifier(criterion='entropy')
dt.fit(Xtrain,Ytrain)
Ypred=dt.predict(Xtest)
from sklearn import metrics
accuracy=metrics.accuracy_score(Ytest,Ypred)
accuracy
dt.predict([[0.5,0.8,9,260,6,0,1,2]])
*/
```

## Output:
## df.head()
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119429483/0e3658df-639c-4195-94cc-1bfb045d5b26)
## df.info()
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119429483/b0f2e1d7-2a30-4146-a218-0e68451fd69f)
## df.isnull().sum()
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119429483/d95a5337-5e5c-41fd-b0af-8daecf576ce2)
## df['left'].value_counts()
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119429483/eb5f66b2-1d47-4d8e-b75e-9a70eec03f08)
## df["salary"]
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119429483/4548594a-760e-4d95-86ad-93ff6ce700d2)
## x.head()
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119429483/632738da-03bc-480d-a78a-e602992bf00f)
## accuracy
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119429483/34164e55-62fa-4175-ad19-6c19970e4617)
## dt.predict
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119429483/bb7ef9c2-f63c-42ee-aedc-ef832817d24b)



## Result:
Thus the program to implement the  Decision Tree Classifier Model for Predicting Employee Churn is written and verified using python programming.
