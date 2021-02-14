# DIABETES PREDICTION
A hospital will conduct tests on various parameters of a person’s health information which can then be used by an expert to make conclusion whether the person is having diabetes or not.  
In some regions of the country, there is lack of specialised doctors present, and this might create difficulties for people of the region to avail the preferred service. While getting tests results of various parameters can be done through machines, can the process of concluding/predicting whether a person has diabetes or not can also be done through machines? Will it have high accuracy so that the predictions will be reliable and can be used without an expert?

# Steps involved in predicting the outcome:
1) Data Wrangling
2) Exploratory Data Analysis
3) Pre-processing and Training Data Development
4) Model Evaluation and Optimization

The raw dataset was consisting of 2000 rows and 9 columns. 
The columns data consists of health-related parameters of a person like number of pregnancies occurred, glucose levels, blood pressure levels, skin thickness, BMI, DiabetesPedigreeFunction, age and outcome (whether the person has diabetes or not). 

We used the following models for predicting the model:
1) Logistic Regression
2) Decision Tree
3) Random Forest
4) SVM
5) Gradient Boosting

We get the highest accuracy of 94.5% from the random forest model.
We have applied some hypertuning to the random forest model for getting better accuarcy.

After hypertuning the random forest model we get 99.8% accuracy on our training dataset and 96% accuracy on the test dataset.

# Possibility of Further Research on the Problem
Here we have used the data to predict whether a person has diabetes or not.
Diabetes is also divided into two types. This project can be further expanded into the following:
1)	Predicting Type I diabetes
2)	Predicting Type II diabetes 

Thanks for reading out till the end.
