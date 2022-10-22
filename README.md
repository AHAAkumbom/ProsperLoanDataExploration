# ProsperLoanDataExploration-Data_Visualization
![prosper](https://user-images.githubusercontent.com/44718084/197364950-b83790fe-5c1c-4c94-931c-afb894dfafed.png)
### by (Achumbom Haggai Akumbom)
## Preliminary Wrangling
The ProsperLoan data set [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) Contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate),current loan status, borrower income, and many others. 
I perfromed the following
Frist I did a High level Overveiw of the data with the following fonctions 
<ul>
    <li>
print(loan.shape)
print(loan.dtypes)
print(loan.head(4)) and loan.info()
        </li>
    </ul>
 Then I went ahead to drop all duplicates and procecede with a brief descibtive statictics 
 on the data set using the loans_clean.describe() function.
 
 After this I selected the columns  I needed for my visualization and I procedded by checking for duplicates which I droped any duplicates, then I Ploted the data on a Univariate, Bivariate then on Multivariate Plots

## Summary of Findings

We Noticed through out our exploartion that Factors like Terms and Emplyoment status don't affect Loan Status mean While Factors Like BorrowerAPR ,IncomeVerifiable,BorrowerRate Affects the Loan Stauts


## Key Insights for Presentation

For the presentation, I focus on just the on the selected colums. I start by Ploting the distribution of the  Loan Status through out the data set, followed by the pointing out the distrubtion of the terms in month through out the data set

Afterwards, I introduce each of the varabiles of intrest in a univarent plot then, I Set on to look for the relation ship that these variables could possibly have with the Loan Status.
