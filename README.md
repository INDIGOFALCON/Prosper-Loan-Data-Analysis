# Prosper-Loan-Data-Analysis

Prosper Laon data is made of up several inventories of prosper loan. The aim of the analysis was to perform exploratory data analysis to find out the factors that affect Borrower's 
Application of prosper Loan


## Dataset
The prosperLoan data set was chosen for this exporatory analysis. It had a total of 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. 
Most of the variables in this dataset are numeric in nature. The categorical data in this dataset are Loan Status, Closed Date, Prosper rating(numeric), Prosper rating(Alpha), among a  few others. A total of 14 colums were chosen for effective visualisation in other to be able to provide adequeate insights and they were;
**LoanStatus,BorrowerAPR,BorrowerRate, ProsperRating (numeric), BorrowerState, EmploymentStatus,EmploymentStatusDuration,IsBorrowerHomeowner   CreditScoreRangeLower, CreditScoreRangeUpper, DebtToIncomeRatio,IncomeRange,StatedMonthlyIncome,LoanOriginalAmount** 

A few questios which directly influence borrowers were asked. These questions were divided into univariate, bivariate and multivaraite exploration questions and they are outlisted below;
**univariate Analysis Questions:**

*Quantitative Analysis:*

What is the distribution of the DebtToIncomeRatio of the borrowers?

What is thedistribution of the  OriginalLoanAmount being Borrowed by people ?

What is the distribution of the EmploymentStatusDuration of thye Borrowers?

*Qualitative Analysis:*

Which state do we have the highest borrowers?

What is the distribution of the  loanStatus of the borrowers?

What is the distribution of the EmploymentStatus of the borrowers?

What is the distribution of the Income Range of the Borrowers?

What is the distribution of the  CreditScoreRange of the Borrowers


**Bivariate Analysis Questions:**

What factors affect the debtToIncomeRatio?

Is Original Loan given out affected by high CreditScore Range Is?

Does employment status affect the amount of Loan being borrowed originally?

What is the relationship between income Range and employment Status?


**Multivariate Analysis Question:**

What effect does original loan amount have on Borrower APR and Borrower Rate?

What is the relationship between StatedMonthlyIncome and BorrowerRate and how does it affectLoanStatus

What is the relationship between employmet status and Stated MonthlyIncome and how does it affect homeownership?

## Summary of Findings

All questions were appropriately attended to with the aid of scatterplots, bar plots, heatmaps, kdeplots, violin plots, boxplots and facets for all three visualisation(i.e univariate, bivariate and  ultivariate visualisation).
**Numeric and categorical data were visualised.**

The mueric data chosen were analysed using histograma and KdepLOT for the univariate analysis **Histogram**was plotted for the numeric varible;DebtToIncomeRatio, 
LoanOriginalAmoount and EmploymentStatusDuration. It was found out that  plot of the DebtToIncome Ratio is a normal distribution> Although it looks positively skewed,
this is because of the outliers seen in the plot.
The Original Amounnt being  borrowed were wthin the range of 5000-10000. There are a few outliers with the highest loan being borrowed falling below 5000 i.,e  4,000
The EmploymentStatusDuration shows a positively skewed data as there is a steady decline of the employment status from beginning of the polot to the end.
The numeric data visualised especially the EmploymentStatusDuration showed a positively skewed data. This was later converted to a logform to even out the plot seen.

**A kdeplot** was doen to the Explore LoanOrignalAmount.It was found out that  there were  spikes in the density of the LoanOriginalAmount Borrowed with the highest peaking above 0.00012.
There was a steady rise in the am ount being borrowed from 0 to 5000, thereafeter, a decline was seen. A shape rise was also noticed at 10000 and 15000 markers. The lowest amount issued out was 30000
**The state of borrowers** was also analysed using a bar plot and it was discovered that a lot individuals were borrowing money from the state "CA". We also have a considerable large number of people borrowing from FL,NY,TX. 

The **categorical data** for univariate exploration was analysed using the barplot and it was discovered that
From this Analysis we see that, for the Employment status distribution, we had a high level of employed individuals. A highest number of individuals considered for loans were employed. A very small number of people given loan were unemployed.
The LoanStatus with the highest distribution was the current loan status
A lot of the individuals that were given loan had a high income range between 25,000-49000
A barplot pf CreditScoreRange was also plotted. This shows  a normal distribution as majority of the creditscore range fell on the  680-699 marker.  This is to say that a credit score range of that value is a good score to be considered when loan is to be given out


**The Bivariate Analysis** 
kicked off with a heatmap to compare all numeric variables explored in the analysis(i.e DebtToIncomeRatio','LoanOriginalAmount','BorrowerRate','EmploymentStatusDuration', 'StatedMonthlyIncome). Here we saw that most of the values had weak correlation to each other with the highest correlation seen at 0.201 comparing correlation between LoanOriginalAmount and StatedMonthlyIncome.
**DebtToIncomeRatio** was also compared with the variables EmploymentStatus, IncomeRange, CreditScoreRange and  LoanStatus.
Looking at the plot of the IncomeRange to DebtToIncomeRation and EmploymentStatus to DebtToIncomeRatio, we see that individuals with high DebtToIncomeRatio were unemployed.The employment status and IncomeRange strongly affect DebtToIncomeRatio.
**A barplot copmparing CreditScoreRAnge to LoanOriginalAmount** was done. Here we see that creditScoreRange of 800-819, 820-839, were given larger amount of money compared to borrowers with lowerCreditScoreRange.It seems a s though that the higher the CreditScore the larger the amount being given.
**A barplot of EmploymentStatus and LoanOriginalAmount** was From this plot we see truly that employment status affects the amount of Loan being given out, Employed individuals  had higher amount being given out followed by self-emplyed individuals.Thus employment status is a huge factor considered in giving out loan
Further exploration was done comparing  Comparing the LoanOriginalAmount, DebtToIncomeRatio and BorrowerRate to EmploymentStatus, 
we can see that throughout the violin plot of the LoanOriginalAmount to Employment Status, there is a spike in the amount being borrowed showing that all categories had a spike at about the 5000.
Comparing the DebtToIncomeRatio toEmploymentStatus,we can see a lot of spike, that is outliers up to the 1o.o mark on the y-axis
Comparing the BorrowerRate to the EmploymentStatus, we can see a spike at the Not employed marker showing that a lot of unemploymed individuals were borring money.


**The Multivariate  Analysis** was done by comparing LoanOriginalAmount, Borrower's Rate and ProsperRating and it was found out that
in the scatter plot the **higher the prosperRating the lower the rate at whcih people were borrowing.**
we also saw that some individuals with prosper ratinh 5,6,7 were given amount up till 35000 opposed to individuals with lower prosper rating(i.e 1,2,3..)
Also  a large number of individuals with low prosper rating were borrowing money at a low rate . 
The higher the borrower rate, the less ther number of individual borrowers and the lower the amount being borrowed

A **Multi-set bar chart** was also done comparing the variables **StatedMonthlyIncome, EmploymentStatus and IsBorrowerHomeowner**. It  was discovered that
generally a lot of borrowers are homeowners.( i.e we have people with houses borrowing more than people without houses.
We also see that the borrowers witht the highest income are selfemployed and are homeowners.




## Key Insights for Presentation

The persentation will be focused on the variables  Employment Status, Stated, Monthly Income , DebtToIncomeRatio amongst a few others as it affects Borrowers Loan Application
