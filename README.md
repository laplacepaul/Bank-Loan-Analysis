# Bank-Loan-Analysis

## Project Overview

### 1. Project Introduction
#### Objective:
The Bank Loan Analysis project aims to provide comprehensive insights into the bank's loan portfolio using Power BI. 
The visualization and analytics will enable stakeholders to make informed decisions regarding loan applications, portfolio performance, and risk management.

### 2.  Project Components
#### a. Data Source:
Data is sourced from the bank's SQL Server database, containing information about loan applications, approved loans, disbursed amounts, and related metrics.

#### b. Power BI Components:
- Reports:

Multiple reports are created to cater to different aspects of the loan portfolio, including application trends, fund allocation, and interest rate analysis.
Dashboards:

- Dashboards:

Dashboards are designed for a consolidated view, featuring key performance indicators, trend analyses, and a snapshot of the current loan portfolio.

- Slicers and Filters:

Implemented slicers and filters for user interactivity, allowing stakeholders to drill down into specific loan grade, loan types, loan purpose and state .

### 3. Key Measures

- Total Loan Applications:

Calculated as the count of unique loan applications.

- Total Amount Funded:

Sum of the disbursed amounts for all approved loans.

- Total Amount Received:

Aggregated sum of payments received against disbursed loans.

- Average Interest Rate:

Calculated as the average interest rate across all loans.

- Good loan:

  Calculated as the count of loan applications whose loan status is either Fully paid or Current.

 - Bad Loan:

    Calculated as the count of loan applications whose loan status is Charged Off.

### 4. Visualizations

- Loan Application Trend:
Area chart depicting the trend of loan applications over time.

- Average Interest Rate:
 Displayed as a card visualization for quick reference.

- Total Funded Amount:
 Displayed as a card visualization.

- Total Loan Applications:
  Displayed as a card visualization.

- Total Amount Received:
  Displayed as a card visualization.

- Average DTI:
  Displayed as a card visualization.

- Other KPIS displayed as card visualization:
 
    1. Month To Date (MTD) (Total Loan Applications)
    2. Month Over Month (MoM)(Total Loan Applications)
    3. MTD(Total Funded Amount)
    4. MoM(Total Funded Amount)
    5. MTD(Total Amount Received)
    6. MoM(Total A mount Received)
    7. MTD(Average Interest Rate)
    8. MoM(Average Interest Rate)
    9. MTD(Average DTI)
    10. MoM(Average DTI)
    11. Good loan Total Loan Applications
    12.Bad loan Total Loan Applications
    13. Good loan Total Funded Amount
    14. Bad loan Total Funded Amount
    15. Good loan Total Amount Received
    16. Bad loan Total Amount Received
    
- Donut Chart:

  Showing the distribution of the Good loan and the Bad loan.

 - Shape map:

  Showing the Total Loan Applications by state.

- Donut chart:

 Illustrating the distribution of loan applications by Term.

- Bar charts:

Illustrating the Total Loan Applications by Employee length, purpose and home ownership.


### 5. User Interaction

Users can interact with the reports and dashboards through slicers and filters to explore data based on their specific needs.


### 6. Documentation

A README file in this project repository on GitHub provides comprehensive documentation. It includes details on data sources, measures, visualizations, and usage instructions.

### 7. Deployment and Maintenance

The Power BI report is published to the Power BI service for broader accessibility.

Scheduled data refresh is set up to keep the report up-to-date.

Regular monitoring of usage and user feedback is incorporated for continuous improvement.

Here's the link to the project on  power bi service : 
[click here](https://app.powerbi.com/reportEmbed?reportId=5c9b1232-2587-4b87-9a12-23879cee1a5b&autoAuth=true&ctid=6f2a7eb7-1c5c-4dd4-b851-2a796a9cbe97)

### 8. Conclusion

The Bank Loan Portfolio Analysis project on Power BI empowers stakeholders with actionable insights, fostering data-driven decision-making in loan management and risk assessment. The project's flexibility and user-friendly design facilitate a seamless exploration of the bank's loan portfolio.
