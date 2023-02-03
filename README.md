# OurAwesomeTeamProject
A collaborative project on studying and modeling the effect of various variables on carbon footprint by using a data-driven machine-learning framework.

Project steps

1. Exploratory data analysis
2. Data cleaning
3. Data transformation
4. Modeling and regression
5. Documentation
6. Slides

Problem statement

Given a data set that contains N number of independent variables (input features), predict the carbon footprint (output feature). Based on the relation between the input features and the carbon footprint, provide some insights/tips on selecting/controlling the input features such that the carbon footprint can be reduced.  


Challenges encountered

- [ ] Challenge 1
- [x] Challenge 2

Steps

- [ ] In df1, keep onle the 'total emissions' and drop the other specific emissions (for simplicity).
- [ ] For food, keep the naming in df1 as the standard and then rename the 'item' column in df2 accordingly. If there are entries in df2['Items'] which do not fall into the food items in df1, kick them out. 
- [ ] Expected output: Updated df2 with countries, food item produced and the corresponding emissions.
- [ ] Clean the updated df2 table.
- [ ] Split the data set into train-test and input-output, where the output is the emission. And input feature X is [nation, food item]. Think about aggregating nations into a region for more high level explanation/plotting. 
- [ ] Train our model, get the parameters which map X_train ---> Y_train. Then, for the test data (25%), predict Y_test from X_test.
- [ ] Calculate the error/residual between the predicted Y_test and the actual Y_test. And plot them.


