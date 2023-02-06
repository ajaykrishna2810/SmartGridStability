# OurAwesomeTeamProject
A collaborative project on studying and modeling the effect of various parameters and variables on the stability of a smart power network by using a data-driven machine-learning framework.

## Project members ##
Ajay Krishna and Danilo Giarlini

## Sources ##
Data source: https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+

Source paper: https://arxiv.org/pdf/1508.02217.pdf

## Problem statement ##

Given a data set that contains N number of independent variables (input features), predict the instability value (output feature). Based on the relation between the input features and the stability value, provide some insights/tips on selecting/controlling the input features such that the insatbility issue may be reduced.  

## Background ##

- [ ] Explain the problem and the parameters (\tau, p, g): create a slide explaining them
- [ ] Explain what is stability
- [ ] How can be evaluate the stability/instability basd on the input features? Motivate data-driven method

## Steps ## 

- [ ] Data cleaning: check for outliers, NaNs etc. Inspect the columns carefully
- [ ] Specify the input and output feature clearly
- [ ] Split the data into test-train
- [ ] For the train data, plot the relationship between X_train and y_train; make a slide on that
- [ ] For X_test, calculate y_test_predict using regression
- [ ] Compare the results: Plot between y_test and y_test_predict
 
