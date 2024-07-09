# Titanic Survival Prediction
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.

## AIM
Analyze the survival distribution of different parameters using visualization tool such as bar chart. The dataset used contains categorical data of various features like passenger id, age, gender, fare, etc.

## METHODOLOGY
1. Importing Dataset
2. Data Cleaning
3. Data Analysis and Visualization
4. Repeative analysis of chosen feature

## Features of data
- PassengerId
- Survived : 0 = Did not survive, 1 = Survived
- Pclass : Ticket class where 1 = First class, 2 = Second class, 3 = Third class. This can also be seen as a proxy for socio-economic status.
- Name : Passenger Name
- Sex : Male or female
- Age : Age in years, fractional if less than 1
- SibSp (Sibling/Spouse) : Number of siblings or spouses aboard the titanic
- Parch (Parent/Child) : Number of parents or children aboard the titanic
- Ticket :  Passenger ticket number
- Fare : Passenger fare
- Cabin : Cabin number
- Embarked : Point of embarkation where C = Cherbourg, Q = Queenstown, S = Southampton

## Libraries used
- `pandas` : Data manipulation and analysis
-  `seaborn` : Data visualization library 
-  `matplotlib.pyplot` : Plotting library for static and interactive visualizations
-  `KNeighborsClassifier` : Constructs a nearest Neighbors class from an array representing the data set

## Conclusion
This project offers insights into the survival rate of various categories. Using `KNeighborsClassifier` we get a score of 80.47% with three nearest neighbors of the trained data.
