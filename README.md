# Coursera-Files
Project Case  Scenario: 

You are a Data Scientist with a housing agency in Boston MA, you have been given access to a previous dataset on housing prices derived from the U.S. Census Service to present insights to higher management. Based on your experience in Statistics, what information can you provide them to help with making an informed decision? Upper management will like to get some insight into the following.
1.	Is there a significant difference in the median value of houses bounded by the Charles river or not?
2.	Is there a difference in median values of houses of each proportion of owner-occupied units built before 1940?
3.	Can we conclude that there is no relationship between Nitric oxide concentrations and the proportion of non-retail business acres per town?
4.	What is the impact of an additional weighted distance to the five Boston employment centres on the median value of owner-occupied homes?
Using the appropriate graphs and charts, generate basic statistics and visualizations that you think will be useful for the upper management to give them important insight given the question they are asking, in your graphs, include an explanation of each statistic. 

Task 1:

The following describes the dataset variables:
For all visualizations, please include a title in each graph and appropriate labels
1)	CRIM - per capita crime rate by town
2)	ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
3)	INDUS - proportion of non-retail business acres per town.
4)	CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
5)	NOX - nitric oxides concentration (parts per 10 million)
6)	RM - average number of rooms per dwelling
7)	AGE - proportion of owner-occupied units built prior to 1940
8)	DIS - weighted distances to five Boston employment centres
9)	RAD - index of accessibility to radial highways
10)	TAX - full-value property-tax rate per $10,000
11)	PTRATIO - pupil-teacher ratio by town
12)	LSTAT - % lower status of the population
13)	MEDV - Median value of owner-occupied homes in $1000's

TASK 2:

Generate the following and explain your findings:
•	For the "Median value of owner-occupied homes" provide a boxplot
•	Provide a  bar plot for the Charles river variable
•	Provide a boxplot for the MEDV variable vs the AGE variable. (Discretize the age variable into three groups of 35 years and younger, between 35 and 70 years and 70 years and older)
•	Provide a scatter plot to show the relationship between Nitric oxide concentrations and the proportion of non-retail business acres per town. What can you say about the relationship?
•	Create a histogram for the pupil to teacher ratio variable

Task 3:

Use the appropriate tests to answer the questions provided.
For each of the following questions;
•	Is there a significant difference in median value of houses bounded by the Charles river or not? (T-test for independent samples)
•	Is there a difference in Median values of houses (MEDV) for each proportion of owner occupied units built prior to 1940 (AGE)? (ANOVA)
•	Can we conclude that there is no relationship between Nitric oxide concentrations and proportion of non-retail business acres per town? (Pearson Correlation)
•	What is the impact of an additional weighted distance  to the five Boston employment centres on the median value of owner occupied homes? (Regression analysis)
