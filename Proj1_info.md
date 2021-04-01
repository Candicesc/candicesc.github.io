## Machine learning and advanced analytics with Python

**Project description:** 
A data analyst is tasked to perform loan analysis and to build Machine learning models to present to the Credit risk management of the bank
with the insights on how to minimise default risk for small-medium enterprises under Commercial Banking.

### 1. Data collection
Research from Kaggle: https://www.kaggle.com/mirbektoktogaraev/should-this-loan-be-approved-or-denied 

### 2. Exploratory Data Analysis (EDA), feature engineering and data preprocessing

- Explore and observe the relationships using statistical methods
- Identify outliers and skewness
- Assess the data for balance
- Perform feature engineering, i.e. create and derive new measurement SBA_guarantee%, loan status, industry code etc.
- Remove anomalies, inconsistencies and outliers
- Clean unwanted data that won't add value to the analysisg

### 3. Data analysis and visualization

Some notable correlations are

### 4. Machine learning model evaluation and recommendations 

Modeling w Logistic regression, Random forest, Multi level perceptron

With the Baseline model, we have a decent accuracy at 83%, however the F1-score of 75% for defaulted loans does not appear to be very promising. 
The precision suggests that the model is correct 80% of the time when the loan defaults, 
the recall suggests that the model identifies 70% of defaulted loans correctly. 
That means that 30% of loans that defaulted were incorrectly classified as loans that would be paid in full, which is not very good.

Random forest model performs better across the board
with a general accuracy of **93%**, but also the precision, recall and F1-score are all improved by quite a bit. 

<img src="images/mleval.png?raw=true"/>

<img src="images/mlrecommendation.png?raw=true"/>
