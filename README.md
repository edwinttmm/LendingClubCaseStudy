

# LendingClubCaseStudyv1

## Project Introduction/Objective
This will contain an Exploratory Risk Analysis for an online marketplace specializing in Personal Loans, business loans, and financing of medical procedures. The company likes to do an Exploratory Credit Risk Analytics on the lending data available to them, the main objective of this task is to understand the 'risky' applicants that can cause Credit loss due to default. If the analysis can be used to identify the risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss due to defaults.

The aim of this EDA(Exploratory Data Analysis) is to find the driving factors behind the loan default, variables that are strong indicators will be presented

## Methods Used for EDA (Exploratory Data Analysis):
* Data Handling and Cleaning
* Sanity Checks and Outlier Analysis
* Univariant Analysis
* Bivariant Analysis


#### Project Version : V1
#### Project Status  : Completed
#### Release Data    : 10/09/2022

### Language : 
* Python

### IDE: 
* jupyter Notebook

### Libraries Used :
* Pandas : 1.2.3
* numpy : 1.20.3
* matplotlib: 3.5.2
* seaborn : 0.11.2
* plotly : 5.9.0

### Files: 
* .pynb file -- jupyter file containing the code
* .pdf file -- power point  in PDF format
* .zip file --- containing original data (1 csv and 1 xlsx file)

## Summary

#### Univariate Analysis

 1. According to the **Loan Status Analysis**, we can conclude the following,
	 - **83.80%** of the borrowers **Fully Paid** the loan  
	 - **13.31%** of the borrowers **Charged Off** (which means defaulted)  
	 - **2.89%** of the borrowers are **Current** (which means in the process of paying the installments)
 2. According to the **Interest Rate Distribution Analysis**, we can conclude the following,
	 - Higher number of loans falling under interest rates between **10%** to **15%**  
	 - Number of borrowers gradually getting reduced when the interest rate is higher than **15%**
 3. According to the **Loan Amount Distribution Analysis**, we can conclude the following,  
	- Most of the loan amount falls between **5000** to **10000**
 4. According to the **Annual Income Distribution Analysis**, we can conclude the following,
	 - Most of the borrower's annual income falls between **40000** to **60000**  
	 - Borrower count gradually increases for annual income between **5000** to **50000** and decreases for annual income between **60000** to **145000**
 5. According to the **Loan Term Analysis**, we can conclude the following,  
	- **72.81%** loans are termed for 36 months  
	- **27.19%** loans are termed for 60 months
 6. According to the **Home Ownership Analysis**, we can conclude the following,  
	- 	**49.41%** of the borrowers have **rent** house  
	- **43.12%** of the borrowers have **mortgage** house  
	- **7.21%** of the borrowers have  **own** house
 7. According to the **Employment Length Analysis**, we can conclude the following,  
	- Most of the borrowers are employed for **10 or more** years
 8. According to the **Application Type Analysis**, we can conclude the following,  
	- **100%** of the borrowers are **individual** applicants
 9. According to the **State Analysis**, we can conclude the following,  
	- The state **CA** has the highest number of borrowers and the state **NE** has the least number of borrowers
 10. According to the **Loan Issued Year Analysis**, we can conclude the following,
		- Least number of loans issued in **2008** which is **2.75%** and the highest number of loans issued in **2011** which is **55.18%**  From **2008** to **2011** number of issued loans gradually getting **increased**

####  Bivariate Analysis

 1. According to the **Interest Rate to Loan Status Analysis**, we can conclude the following,  
	- When the loan **Interest Rate** is increasing, the loan **Charged Off** percentage get increases
 2. According to the **Loan Amount to Loan Status Analysis**, we can conclude the following,  
	- When the **Loan Amount** is increasing, the loan **Charged Off** percentage get increases
 3. According to the **Loan Amount to Loan Status Analysis**, we can conclude the following,  
	- When the **Loan Amount** is increasing, the loan **Charged Off** percentage get increases
 4.   According to the **Home Ownership to Loan Status Analysis**, we can conclude the following,  
		- When the borrower **Home Ownership** is other than **Rent, Mortgage or Own**, loan **Charged Off** percentage get increases
 5. According to the **Employment Length to Loan Status Analysis**, we can conclude the following,  
	- When the **Employment Length** is increasing, the loan **Charged Off** percentage get increases
 6. According to the **Loan Issued Year to Loan Status Analysis**, we can conclude the following,  
	- Most of the loans got **Charged Off**, issued between the years **2010 - 2011**
 7. According to the **Open Credit Lines to Loan Status**, we can conclude the following,  
	- When the **Open Credit Lines** is increasing, loan **Charged Off** percentage get increases
 8. According to the **Monthly Installment to Loan Status**, we can conclude the following,  
	- When the **Monthly Installment** is increasing from **0** to **1200**, the loan **Charged Off** percentage get increases
 9. According to the **Loan Grade to Loan Status Analysis**, we can conclude the following,  
	- When moving from grade **A to G**, the loan **Charged Off** percentage get increases
 10. According to the **Payback to Loan Status Analysis**, we can conclude the following,  
		- When the **Payback** is increasing, the loan **Charged Off** percentage get increases
 11. According to the **Loan Purpose to Loan Status**, we can conclude the following,  
		- Most of the loans **Charged Off** were borrowed for House purposes
 12. According to the **Revolving Line Utilization Rate to Loan Status**, we can conclude the following,  
		- When the **Revolving Line Utilization Rate** is increasing, the loan **Charged Off** percentage get increases

#### Recommendations 
 - Annual income less than 20K at higher risk of defaulting
 - Loan amount higher than 25K at risk of defaulting
 - Higher the interest rate, higher the risk of defaulting
 - People who pick longer loan term is slightly higher risk than the lower term people
 - People on the Home Ownership status ‘Other’ is at slightly higher risk than other
 - Overall loan(including interest) : As the loan gets higher the risk increases people are higher than 50K overall payback is at high risk
 - People with open credit lines of 30-40 are at higher risk
 - Smaller business is at higher risk of defaulting
 - As the revolving line utilization increases the risk of defaulting increases
 - As the ratio of income to debt gets closer the risk of defaulting gets higher.
 - It's recommended to introduce an point based system to assess the risk of being defaulted (since multiple risk factors are associated with getting defaulted, point based system will be an ideal solution)

#### Loan Performance
-	Payment Expected with Interest: **454,362,431.76**
-	Payment Expected without Interest: **364,618,850.00**
-	Payment Received: **396,578,430.16**
-	Expected Profit: **89,743,581.76**
-	Loss Due to Defaulting: **57,784,001.60**
-	Actual profit: **31,959,580.16**
-	Percentage of profit Achieved to Expected: **35.61%**
-	Percentage of Company Profit to investment: **8.77%**
-	Percentage of Expected Company Profit to investment: **24.61%**

#### Loan State Wise Distribution
(https://github.com/edwinttmm/LendingClubCaseStudyv1/blob/final_draft/loan_state_wise_dist.png)
 
## Acknowledgements 
 - Upgrad/IITB
 - Online Sources : Stackoverflow, Pandas , seaborn , plotly, numpy , matplotlib
