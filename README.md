# CA04: Ensemble Models
Comparing the performance of different ensemble models. 

**Data Overview** <br />
The datset is obtained from the Census Bureau with the salaries of people that are categorized as less than 50k or more than or equal to 50k. These people are categorized by numerous demographic variables, including age, capital gain/loss, education, hours worked per week, marriage status and relationship, occupation, and race and sex.

## Steps 
1. Data Quality Anaysis 
2. Data Cleaning
3. Finding Optimal Value for Decision Tree Classifier Model
4. Finding Optimal Value for AdaBoost
5. Finding Optimal Value for Gradient Boost Classifier
6. Finding Optimal Value for XGB Model 
7. Compare Performance in a Table 

## Packages 
import pandas as pd <br />
import numpy as np <br />
from sklearn.impute import SimpleImputer <br />
import matplotlib.pyplot as plt <br />
from sklearn.preprocessing import LabelEncoder <br />
from sklearn.tree import DecisionTreeClassifier <br />
from sklearn.ensemble import RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier <br />
from xgboost import XGBClassifier <br />
from sklearn.metrics import confusion_matrix, accuracy_score, precision_score, f1_score, roc_curve, roc_auc_score, recall_score, auc <br />

## Author
[Karina Ramirez](https://github.com/kramire8 )

## Contributors 
This project was provided by Dr. Arin Brahma at Loyola Marymount University for the Intro to Machine Learning course. <br />
