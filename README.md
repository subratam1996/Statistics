# Statistics
# Statistics-Project
## OBJECTIVE:
This project aims to assess the Financial Literacy of the population in West Bengal. 
Financial Literacy refers to the knowledge of banking facilities and various concepts related to banking that helps individual make informed and effective decisions regarding their personal finances.
From World Bank Data we have studied the various trends in financial awareness in different socio-economic segments of the population in India and did a parallel study specific to West Bengal to draw a comparison with the World Bank Data. 
## METHODOLOGY:
We have done primary data collection through Google Forms and physical surveys. The Sampling Method used here is convenience sampling. 
The sample size of our data is 159 and there are 20 features. 
We have done hypothesis tests to understand how the association between different features in our data set. The two kinds of hypothesis tests that were applicable to our data were the Chi-Square Test of Association and the Z test for proportion. 
The Hypothesis of the Chi-Square Test:
1.	There is an association between monthly income and the use of ATM cards. 
2.	There is an association between locality and the use of Credit cards. 
3.	There is an association between locality and the Use of Net Banking.
4.	There is an association between Job Type and the use of Credit Cards.
5.	There is an association between Educational Qualifications and the use of Credit cards. 


Hypothesis for Z-test for proportions:
1.	The proportion of people using net banking with income above 10000 is larger than those using net banking with income below 10000.
2.	The proportion of people using credit cards with income above 30000 is larger than the proportion of people using credit cards with income below 30000.
3.	The proportion of people using Banking Apps with education above Higher Secondary is larger than the proportion of people using Banking Apps with education below Higher Secondary.

## Linear Regression:
We created a literacy score based on the financial features in the dataset. The financial features were given weights such that the modern banking techniques get the highest weight and then sequentially decrease as we move to the common banking practices. There were penalties given when the individuals missed out on any one of the features. 
This score was used as the dependent variable in the Linear Regression and the input features were the socio-economic features in our data set. The idea of this linear regression was to check how well the socio-economic features can explain the variation in the financial literacy of the sample. 
We used a top-down approach of regression to identify the significant input features. 

## CONCLUSION:
(1)	After eliminating all insignificant co-efficient associated features, we reached the final four i.e., Age, Educational Qualification, Gender, and Monthly Income.
(2)	Age has a negative coefficient, which that indicates the Financial Literacy score is better among younger than older people. So younger people are more prone to use modern banking technologies.
(3)	Educational Qualification and Monthly Income has a positive coefficient, so people with higher education and higher monthly income are more used to modern banking.
(4)	Gender woman has a negative coefficient, which gives some idea about the lack of knowledge regarding the modern banking system among women.
