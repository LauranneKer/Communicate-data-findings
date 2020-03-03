# Communicate-data-findings
Project using Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships

## Steps followed for this analysis
### First part in Jupyter Notebook: Exploratory analysis
1. Introduction
2. Wrangling
5. Exploratory data analysis (Univariate, bivariate, multivariate)


### Second part in Slides deck: Explanatory analysis
Polished relevant visualisations extracted from exploratory analysis and build story out of these findings

## Dataset
There are 113,066 loans in the dataset. The attributes include 10 features out of which 5 features to describe the borrower's profile (Income Range, Employment Status, Employment Status Duration, Is Borrower Homeowner?, Total Credit Lines in the past 7 years) then Listing Creation Date, Borrower Rate (interest rate), Loan Category, Loan Original Amount and the Monthly Loan Payment. The full dataset containing more than 80 variables can be downloaded [here] (https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.)


## Summary of Findings

In the exploration, I found that there was a slight relationship between some of the borrower's profile features ( employment status and income range) but also the loan categories and the interest rate.  So in general, employed borrowers with higher income get access to lower interest rates as expected, Then I also found that there was an interesting but also not so strong correlation between interest rate and loan amount. As the loan amount gets higher, there is more likelihood to get a lower interest rate on the loan.

Outside of the main variables of interest, I verified the relationship between interest rate and number of credit lines in the past 7 years, and also with the employment duration but there was no striking correlation between those variables.

## Key Insights for Presentation

For the presentation, I focus on just the influence of the main variables of interest which are the interest rate, the employment status, the income range, the loan amount and the loan categories.

I start by introducing the interest rate variable in a histogram to see the extend of the rates among the selected dataset. Then, I present the distribution of loans according to borrowers profiles in bar charts. After which I show the interaction between our interest rate and borrowers' pofiles features in box plots because our borrowers features are categorical. Finally, I use a set of scatter plots to show the interaction between our interest rate and the loan amount in combination with looking at each loan category (one category by plot) and looking at employment status thanks to a color legend.

## Note
This project has been submitted as Project # 5 in the scope of the Data Analyst Nanodegree Program of Udacity
