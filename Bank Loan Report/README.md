# Detailed Loan Analysis Report

## Overview
This report provides a comprehensive analysis of the bank's lending activities, focusing on key performance indicators (KPIs) related to loan applications, disbursements, repayments, and borrower financial health. The insights derived from this analysis will help in making data-driven decisions, monitoring the health of the loan portfolio, and identifying trends that can inform our lending strategies.

Certainly! Here's an explanation of the dataset in terms of the types of data it contains, categorized by their respective data types:

### Dataset Overview

The dataset contains information about loans issued by the bank, including details on the borrowers, loan characteristics, and loan performance. Each row represents a unique loan.

### Data Types

#### 1. **Numerical Data**
These columns contain quantitative data, which can be either integers or floats:

- **loan_amount**: The amount of money disbursed as a loan.
- **annual_income**: The borrower's annual income.
- **dti**: Debt-to-income ratio, representing the borrower's financial health.
- **installment**: Monthly installment amount to be paid by the borrower.
- **int_rate**: Interest rate of the loan.
- **total_payment**: Total amount paid by the borrower to date.

#### 2. **Categorical Data**
These columns contain data that can be categorized into distinct groups:

- **address_state**: The state in which the borrower resides.
- **application_type**: The type of application (e.g., individual, joint).
- **emp_length**: Length of the borrower's employment, typically categorized (e.g., < 1 year, 1-3 years, etc.).
- **emp_title**: The title of the borrower's job.
- **grade**: Loan grade, typically an indicator of creditworthiness.
- **home_ownership**: Borrower's home ownership status (e.g., own, rent, mortgage).
- **loan_status**: Current status of the loan (e.g., Fully Paid, Current, Charged Off).
- **sub_grade**: A more detailed categorization within the loan grade.
- **term**: The duration of the loan (e.g., 36 months, 60 months).
- **verification_status**: Status of the income verification (e.g., Verified, Source Verified, Not Verified).
- **purpose**: Purpose of the loan (e.g., debt consolidation, credit card refinancing).

#### 3. **Date Data**
These columns contain dates, which can be used for time-based analysis:

- **issue_date**: The date the loan was issued.
- **last_credit_pull_date**: The date of the last credit pull for the borrower.
- **last_payment_date**: The date of the last payment made by the borrower.

## Data Preprocessing

The dataset was preprocessed to ensure accurate analysis. Key steps included:

- Converting date columns to datetime format.
- Creating additional columns for month and year to facilitate time-based analysis.
- Aggregating data based on relevant categories (e.g., loan term, state, loan status).


## Database Management and Analysis with MySQL
For the analysis of the bank's lending activities, MySQL was utilized as the primary database management system. The use of MySQL provided a robust and reliable platform for managing the large and complex dataset containing detailed information on loan applications, borrower details, and loan performance metrics. By leveraging MySQL's powerful query capabilities, we were able to efficiently retrieve and manipulate data to calculate key performance indicators (KPIs) such as total loan applications, total funded amounts, total amounts received, average interest rates, and average debt-to-income ratios. MySQL's support for complex queries, joins, and aggregations enabled us to perform in-depth data analysis and derive meaningful insights from the raw data.

Additionally, MySQL's scalability and performance ensured that the analysis could handle the significant volume of data without compromising on speed or accuracy. The database's ability to handle concurrent queries allowed for simultaneous analysis of different aspects of the data, such as regional loan performance and borrower demographics. By using MySQL, we were able to create a comprehensive and detailed report that included visualizations and trend analysis, ultimately supporting data-driven decision-making within the bank. The structured and organized nature of the MySQL database also facilitated seamless integration with data visualization tools, enabling the creation of intuitive and interactive dashboards to further enhance the analysis.

## Data Visualization with Tableau

For the visualization of the loan data and the creation of insightful dashboards, Tableau was utilized as the primary tool. Tableau's powerful data visualization capabilities allowed for the creation of interactive and dynamic charts, maps, and dashboards that effectively communicate the key insights derived from the loan data. The integration with MySQL facilitated real-time data retrieval and enabled seamless updates to the visualizations as the underlying data changed. The user-friendly interface of Tableau enabled quick development of visualizations that were easy to interpret, aiding stakeholders in making informed, data-driven decisions. The visualizations included line charts for monthly trends, filled maps for regional analysis, donut charts for loan term analysis, bar charts for borrower analysis, and tree maps for home ownership analysis, providing a comprehensive view of the bank's lending activities.

The complete dashboard can be viewed [here](https://public.tableau.com/app/profile/deborah.odunlami/viz/BankLoanReport_17190080816210/SummaryDashboard)

![image](https://github.com/deborahodunlami/Portfolio-Projects/assets/26973838/4af28c26-dde5-4e8f-bba9-31e239b33df0)

![image](https://github.com/deborahodunlami/Portfolio-Projects/assets/26973838/c6106a92-a9a3-416e-8949-aedc17b245c3)

## Key Findings
1. **Total Loan Applications**: There has been a steady increase in the number of loan applications received over time, with significant month-to-month variations. The MTD data shows a healthy inflow of new loan applications.

2. **Total Funded Amount**: The total amount funded has shown consistent growth, reflecting the bank's robust lending activities. MTD funding remains strong, indicating sustained lending performance.

3. **Total Amount Received**: The total amount received from borrowers has also increased, highlighting effective loan repayment and cash flow management. MTD amounts show continued strong repayment activity.

4. **Average Interest Rate**: The average interest rate has shown minor fluctuations month-to-month. Monitoring these changes helps in understanding the cost of lending and borrower affordability.

5. **Average Debt-to-Income Ratio (DTI)**: The DTI ratios suggest that borrowers are maintaining healthy financial balances, with slight month-to-month variations.

### Good Loans vs. Bad Loans

- **Good Loans**: A significant majority of the loans fall under the 'Good Loans' category, with a high percentage of applications classified as fully paid or current. This indicates a high quality of the loan portfolio.
- **Bad Loans**: A smaller percentage of loans are classified as 'Bad Loans' (charged off), reflecting effective credit risk management and borrower assessment processes.

### Regional Analysis

The regional analysis by state reveals disparities in lending activities across different regions. States with higher total loan applications, funded amounts, and amounts received can be targeted for further strategic initiatives.

### Loan Term Analysis

Different loan terms show varying levels of applications and funding amounts. Understanding the distribution of loans across term lengths helps in tailoring products to meet borrower preferences.

### Borrower Analysis

- **Employee Length**: Lending metrics vary across different employment lengths, indicating the importance of stable employment in loan approval processes.
- **Loan Purpose**: Different loan purposes show distinct trends in applications and funding amounts, helping in understanding borrower needs.
- **Home Ownership**: Home ownership status impacts loan metrics, with different categories showing varied levels of applications and funding.

## Conclusion

This detailed analysis provides a clear and insightful view of the bank's lending activities. By leveraging these insights and continuously monitoring key metrics, the bank can optimize its lending strategies, enhance risk management, and achieve sustained growth. If further analysis or specific visualizations are needed, additional data exploration and modeling can be conducted to support strategic initiatives.


## Recommendations

1. **Strategic Focus**: Target regions with higher loan activity for strategic initiatives and marketing efforts to further boost lending activities.
2. **Product Tailoring**: Develop loan products tailored to the preferences observed in the loan term analysis to attract more borrowers.
3. **Risk Management**: Continue focusing on maintaining a high quality of loan portfolio by enhancing credit risk assessment processes.
4. **Customer Insights**: Utilize insights from borrower analysis to develop personalized financial products and services, improving customer satisfaction and retention.

By continuously monitoring these KPIs and leveraging the insights provided by the visualizations, the bank can enhance its lending operations, manage risks effectively, and achieve sustained growth.

