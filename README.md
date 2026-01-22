# Bank-Loan-Performance-Analysis-Using-SQL-Python 
## Project Overview
This project involves the development of a comprehensive Bank Loan Report designed to monitor and assess a bank's lending activities. By transforming raw data into actionable insights, this report helps stakeholders track loan portfolio health, identify seasonal trends, and evaluate borrower risk profiles.  

## Problem Statement
The bank required a data-driven solution to monitor lending performance. Key objectives included:  

● Tracking MTD (Month-to-Date) and MoM (Month-over-Month) growth for applications and funding.  
● Distinguishing between Good Loans (Fully Paid/Current) and Bad Loans (Charged Off) to assess portfolio risk.  
● Analyzing borrower demographics (Employment, Home Ownership) and loan characteristics (DTI, Interest Rates).  
● Support data-driven lending and risk management decisions  

## Tools & Technologies
● SQL Server Management Studio – Used to store, manage, and query bank loan data.  
● Python – Used for data cleaning, validation, and analytical support.  
● Jupyter Notebook – Interactive environment for executing Python analysis.  
● Pandas – For data manipulation and tabular analysis.  
● NumPy – For numerical computations and aggregations.  
● Matplotlib – For basic data visualizations.  
● Seaborn – For statistical and distribution-based visualizations.  

## Installation and Setup
● Install Python (3.8 or later) and Jupyter Notebook
● Install the required Python libraries using:
```bash
pip install pandas numpy matplotlib seaborn plotly
```
● Install SQL Server Management Studio (SSMS).  
● Clone this repository to your local machine.  
● Load the loan dataset into SQL Server and execute the provided SQL queries.  
● Open the Jupyter Notebook and run the analysis cells.  

## Key KPIs Analyzed
● Total Loan Applications  
● MTD Loan Applications  
● MoM Loan Application Growth  
● Total Funded Amount  
● Total Amount Received  
● Average Interest Rate  
● Average Debt-to-Income Ratio (DTI)  

## Dashboard Highlights
### 1. Summary Dashboard  
Provides a quick pulse check on the bank’s overall lending health and performance.   
● KPIs: Total Applications (38.6K), Total Funded Amount ($435.8M), and Total Amount Received ($473.1M).    
● Risk Metrics: Visual breakdown of "Good vs. Bad" loans. Currently, the portfolio maintains an 86.2% Good Loan rate.  

### 2. Overview Dashboard
Focuses on trends and segmentation.      
● Seasonality: A line chart showing a steady increase in loan applications from January through December.    
● Demographics: Analysis by employment length (10+ years being the largest segment) and home ownership (Rent/Mortgage).    
● Purpose: "Debt Consolidation" identified as the primary reason for borrowing.  

### 3. Details Dashboard
Provides complete transparency through a detailed, record-level loan view.  
● Displays individual loan records with Loan ID, Purpose, Grade, and Sub-Grade.    
● Includes borrower and loan attributes such as Home Ownership, Issue Date, Interest Rate, Installment Amount, and Amount Received.  
● Enables granular analysis through dynamic filters for State, Grade, and Loan Quality.  
● Supports audit-level validation and deep-dive analysis for operational and risk teams.  

## Key Insights
● Portfolio Growth: Applications showed a 6.9% MoM increase, indicating growing demand.  
● Risk Profile: Bad loans account for 13.8% of total applications, representing $65.5M in funded capital.  
● Regional Performance: Strategic lending activity is concentrated in specific states.    
● Loan Characteristics: The average DTI stands at 13.3%, suggesting a generally healthy borrower profile.  

## Project Outcomes
● Identified 13.8% Charged-Off loans ($65.5M) through Good vs Bad loan segmentation, supporting risk control.  
● Tracked 6.9% MoM growth, reaching 38.6K applications and $435.8M in total funding.  
● Confirmed strong recovery with $473.1M collected against an average 12.0% interest rate.  
● Automated MTD and MoM KPI tracking using SQL for real-time performance monitoring.  
● Revealed Debt Consolidation as the top loan purpose and 10+ year employees as the most stable borrowers.  

## Conclusion
This project successfully delivers an end-to-end bank loan analysis solution using SQL, Python, and interactive dashboards. By tracking key lending KPIs, classifying loan risk, and analyzing borrower behavior, the report provides clear visibility into portfolio performance and credit quality. The insights generated support data-driven decision-making, risk mitigation, and strategic planning, making this analysis highly relevant for real-world banking and financial analytics use cases.
