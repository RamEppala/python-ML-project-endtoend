# python-ML-project-endtoend
project Name: predciting house prices- ML Project in python2 and Jupyter NB

Description: Practical Machine Learning Project in Python on House Prices Data

some characteristics of this project: The data is fairly large and high dimensional.This project will demonstrate data science life cycle and machine learning skills.

Table of Contents:

Process of Machine Learning Predictions: 

Making predictions using Machine Learning isn't just about grabbing the data and feeding it to algorithms. 

Understand the problem: 

This project aims at predicting house prices (residential)

Before getting the data, we need to understand the problem we are trying to solve. If you know the domain, think of which factors could play an epic role in solving the problem. 

Hypothesis Generation:

 hypothesis generation refers to creating a set of features which could influence the target variable given a confidence interval ( taken as 95% all the time). We can do this before looking at the data to avoid biased thoughts. This step often helps in creating new features.
 
 Ho - There exists no impact of a particular feature on the dependent variable. Ha - There exists a direct impact of a particular feature on the dependent variable.
 
 Based on a decision criterion (say, 5% significance level), we always 'reject' or 'fail to reject' the null hypothesis in statistical parlance. Practically, while model building we look for probability (p) values. If p value < 0.05, we reject the null hypothesis. If p > 0.05, we fail to reject the null hypothesis.
 
Get Data:

The target variable is SalePrice. the data set comprises numeric, categorical, and ordinal variables.

Determine which features are available and which aren't, how many features we generated in hypothesis generation hit the mark, and which ones could be created. Answering these questions will set us on the right track. 

Data Exploration:

Univariate Analysis - It is used to visualize one variable in one plot. Examples: histogram, density plot, etc.
Bivariate Analysis - It is used to visualize two variables (x and y axis) in one plot. Examples: bar chart, line chart, area chart, etc.
Multivariate Analysis - As the name suggests, it is used to visualize more than two variables at once. Examples: stacked bar chart, dodged bar chart, etc.
Cross Tables -They are used to compare the behavior of two categorical variables (used in pivot tables as well).

This step helps us understand the nature of variables (skewed, missing, zero variance feature) so that they can be treated properly. It involves creating charts, graphs (univariate and bivariate analysis), and cross-tables to understand the behavior of features. 

Data Pre-Processing:

impute missing values and clean string variables (remove space, irregular tabs, data time format) and anything that shouldn't be there. This step is usually followed along with the data exploration stage.

Feature Engineering - we create and add new features to the data set. Most of the ideas for these features come during the hypothesis generation stage. Create 331 new features

Model Training - used algorithms  XGBoost, Neural Network, Lasso to train the model

Model Evaluation-

Once the model is trained, we evaluate the model's performance using a suitable error metric. Here, we also look for variable importance, i.e., which variables have proved to be significant in determining the target variable. And, accordingly we can shortlist the best variables and train the model again.

Model Testing: 

Finally, we test the model on the unseen data (test data) set.

Finally, ensemble models to arrive final predictions.


