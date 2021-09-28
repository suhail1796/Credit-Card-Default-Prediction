# Credit-Card-Default-Prediction

Problem statement of the Credit Card Default Prediction is to build a model to identify whether the credit card applicant will default or not based on his repayment history and other important factors. In order to achieve this, we need to develop a supervised machine learning model using classification algorithms.

To begin with we imported some of the required libraries for data analysis and visualization. We loaded the data and go over the basic features, shape and datatypes of various variables. We observed the data contains duplicate records and null values. By using Panda’s library, we handled duplicate records and null values. By using box plots we found some outliers and manipulated those outliers with python conditional statements. We added new parameters based on the existing ones, for ease of analysis.

We proceeded with exploratory data analysis to estimate how different factors like gender, marital status, education level, age, credit behavior are related to default rate.

We identified correlation between dependent and independent variables with the help of heat map. We split data into training and testing set before implementing model on it. We used Logistic Regression, Random Forest Classifier, Support Vector Machine and XG Boost Classification algorithms.

We evaluated our model to get the accuracies for used algorithm. We found that XG Boost classifier has higher accuracy (82.21 %) followed by SVM algorithm (82.03 %). Logistic regression algorithm had performed well will accuracy (81.43 %). Random forest classifier has fine performance with accuracy (81.43%).

From exploratory data analysis we concluded that default rate for male borrowers is slightly higher than female borrowers. The people between age group of 25 to 50 have good usage of credit card. The default rate higher for married and divorced borrowers. When payment is delayed more than 2 months, the chances of default go higher than 50%.
   
