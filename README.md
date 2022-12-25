# Linear-Regression

I used a dataset which contains information from 310 credit card holders.  I conducted a linear regression analysis in order to produce a model that can answer the business question, “What variables effectively contribute to predicting active cardholders’ credit card balances?” and “What credit card balance might a new active cardholder hold depending on certain variables?” The origial dataset is accessible on kaggle. Model will then be used to predict balances of new credit card holders based on predictor variables in a new dataset.


Variables: The variables I used for this analysis are:

- Income: Annual income, in dollars

- Limit: Credit limit for credit card, in USD dollars

- Rating: A credit rating calculated by the credit card company. (Not the same as a typical 
credit score)

- Age: Age in years

- Education: Number of years of education

- Student: Whether or not the cardholder is a student (No = 0, Yes = 1)

- Gender: The gender of the cardholder (Male = 0, Female = 1)

- Married: Whether or not the cardholder is married (No = 0, Yes = 1)

- Balance: The amount of each cardholder’s balance, in dollars

# Steps

-Generate summary statistics

-Partition dataset into training and validation (50/50 split)

-Create correlation matrix

-Conduct multiple regresssion  (MR) using training df with Balance as outcome variable, using ALL other predictor variables

-Conduct Variance Inflation Factor (VIF)

-Conduct MR with training df, Balance as outcome variable, and Income, Rating, Age, Education, Student, Gender, and Married as predictor variables. 

-MR conducted again but only with statistically significant predictor variables

-Conduct FINAL MR using validation df with Balance as outcome variable and statistically significant variables

-Use model to predict balance for new cardholders based on variables 

