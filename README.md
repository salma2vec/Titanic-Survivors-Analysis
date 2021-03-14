# Titanic Survivors Analysis 🚢
## Data Analysis and Prediction of Survivors on the Titanic Dataset
My first data analysis/data visualization using Python and required modules and libraries.
## Overview
<img src="https://static1.squarespace.com/static/5006453fe4b09ef2252ba068/5095eabce4b06cb305058603/5095eabce4b02d37bef4c24c/1352002236895/100_anniversary_titanic_sinking_by_esai8mellows-d4xbme8.jpg"/>


### Kaggle Competition | Titanic Machine Learning from Disaster
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. 

Although there was some element of luck involved in surviving the sinking ship, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

Here, we try to analyze which factors were more likely to contribute to the death of the passengers and classify who is more likely to survive depending on these features.

This Kaggle Getting Started Competition provides an ideal starting place for people who may not have a lot of experience in data science and machine learning.


### Dependencies
- pandas.
- numpy.
- matplotlib.
- math.
- sklearn.
- scipy.

### Features
- Dataset based on a CSV file : The data has been split into two groups: training set (train.csv) test set (test.csv)
While the training set is used to build our machine learning models, the test set is used to see how well our model performs on unseen data.
- NumPy with Pandas to merge, group, and aggregate various data
- Matplotlib with Seaborn for the scatterplot visualization.

### What is to be done?
Using the data set, The following questions will be explored and analyzed:

- How do the summary statistics of passengers, including their age, gender, and class of ticket,vary by survival?
- What is the relationship between passenger's age and their chance of survival?
- What is the relationship between passenger's gender and their chance of survival?
- What is the relationship between passenger's ticket fare and their chance of survival?
- What is the relationship between passenger's class of cabin and their chance of survival?
- What is the relationship between port of embarkation and chance of survival?
- How did different factors interact in determining the chance of survival?

 & For each passenger in the test set, Our model will be trained to predict whether or not they survived the sinking of the Titanic.

### How to?
- Import the data.
- Describe the data.
- Clean the data: Data cleansing
- Visualize it's features using some of the Data Visualization Techniques.
- Select features.
- Apply Machine Learning Algorithm, like Random Forest, Support Vector Machine, Logistic Regression, Gradient Boosting Classifier, and evaluate its model's accuracy, using confusion matrix.
- Apply Machine Learning Algorithm from scratch, like Logistic regression, to Titanic Dataset.



### The data set
| Variable Name |  Variable Description |
|---------------|-----------------------|
|PassengerID| Passenger ID|
|   Survived  |  Survival (0 = No;1 = Yes)|
|Pclass|Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)|
|Name|Name|
|Sex|Sex|
|Age|Age|
|SibSp| Number of Siblings/Spouses Aboard|
|Parch|Number of Parents/Children Aboard|
|Ticket|Ticket Number|
|Fare|Passenger Fare|
|Cabin|Cabin|
|Embarked|Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)|


You can view a description of this dataset on the Kaggle website (kaggle.com/c/titanic), where the data was obtained.

### Results

It can be seen that the total number of passengers in this data set is 891, among which 549 (61.62%) died in the disaster and 342(38.38%) survived.
