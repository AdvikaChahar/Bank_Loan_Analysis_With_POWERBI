# Bank_Loan_Analysis_With_POWERBI
<div align="center">

</div>

--

Welcome to the **Bank Loan Analysis and Dashboard** repository! This project showcases a comprehensive analysis of bank loan data and the development of interactive dashboards using Power BI. 

 


## Overview
This project involves analyzing bank loan data to understand various metrics and trends in the lending process. The insights gained from this analysis are presented through interactive dashboards in Power BI, providing a clear and comprehensive view of the data.

### How This Dashboard Can Be Used
The dashboards created in this project can be used by financial institutions to:
- Monitor key performance indicators (KPIs) such as loan applications, funded amounts, and repayment amounts.
- Analyze trends and patterns in loan data over time.
- Identify regional disparities in lending activities.
- Assess the impact of borrower characteristics such as employment length and home ownership on loan applications and disbursements.
- Evaluate the overall health and performance of the loan portfolio.

## Project Structure
1. **Data:**
   - `financial_loan.csv`: This file contains the raw dataset used for the project, detailing loan information such as application details, funded amounts, and repayment data.

2. **SQL_Scripts:**
   - `2.0 Data Preprocessing.sql`: This script preprocesses the data, including changing the data types of date columns from text to date to ensure accurate analysis.
   - `2.1 Dashboard_1_Summary.sql`: SQL queries designed to extract and process data specific to the problem statements of Dashboard 1: Summary.
   - `2.2 Dashboard_2_Overview.sql`: SQL queries formulated to address the problem statements of Dashboard 2: Overview, extracting relevant data points for analysis.

3. **SQL_query_results:**
   - `3.1 Dashboard_1_Summary_query_results`: Contains 22 Excel files that store the results of the SQL queries executed from `2.1 Dashboard_1_Summary.sql`. Each file captures specific query outputs, facilitating data validation and visualization.
   - `3.2 Dashboard_2_Overview_query_results`: Includes 6 Excel files with the results of the queries from `2.2 Dashboard_2_Overview.sql`, providing a foundation for the visualizations in Dashboard 2.

4. **PowerBI_Dashboard:**
   - `4.1 Bank Loan Reports.pbix`: The main Power BI file for the project, containing all the data models, measures, and visualizations used to create the dashboards.
   - `4.2 Bank Loan Reports.pdf`: A PDF export of the Power BI dashboards, offering a static, shareable version of the visual insights.

5. **Testing_and_validation_report:**
   - `5.0 Data_Connection_MySQL_to_PowerBI.docx`: Documents the steps and procedures used to establish a connection between MySQL Workbench databases and Power BI, ensuring seamless data integration.
   - `5.1 Loan Data Testing and Validation Report.docx`: A detailed report that includes all SQL queries and their corresponding results, used to validate the Power BI dashboards.

6. **Project Images :**
   - This folder contains images of the created dashboards .

7. **Documentation:**
   - `0.1 Bank Loan Process and Monitoring Guide.docx`: A domain knowledge document explaining the bank's data collection processes, loan approval procedures, and reasons for analyzing loan data.
   - `0.2 Data Dictionary.xlsx`: A detailed data dictionary that explains the meaning and usage of each column in the dataset, including a sheet on data processing that describes column data types before and after preprocessing.
   - `0.3 Measures, columns, table, group and field parameters.xlsx`: This document discusses the 28 measures, one date table, one field parameter, columns, and groups created to build the dashboards.

  
8. **README.md**: This readme file providing a comprehensive guide to the repository.

## Key Performance Indicators (KPIs)
The following KPIs are calculated and visualized in the dashboard:
1. **Total Loan Applications**: Total number of loan applications received during a specified period.
2. **Total Funded Amount**: Total amount of funds disbursed as loans.
3. **Total Amount Received**: Total amount received from borrowers.
4. **Average Interest Rate**: Average interest rate across all loans.
5. **Average Debt-to-Income Ratio (DTI)**: Average DTI for borrowers.
6. **Good Loan vs. Bad Loan KPIs**:
    - Good Loan Application Percentage
    - Good Loan Applications
    - Good Loan Funded Amount
    - Good Loan Total Received Amount
    - Bad Loan Application Percentage
    - Bad Loan Applications
    - Bad Loan Funded Amount
    - Bad Loan Total Received Amount

## Visualizations
### Dashboard 1: Summary
- Total Loan Applications (MTD, MoM)
- Total Funded Amount (MTD, MoM)
- Total Amount Received (MTD, MoM)
- Average Interest Rate (MTD, MoM)
- Average DTI (MTD, MoM)
- Good Loan vs. Bad Loan KPIs
- Loan Status Grid View

### Dashboard 2: Overview
- Monthly Trends by Issue Date (Line Chart)
- Regional Analysis by State (Filled Map)
- Loan Term Analysis (Donut Chart)
- Employee Length Analysis (Bar Chart)
- Loan Purpose Breakdown (Bar Chart)
- Home Ownership Analysis (Tree Map)

### Dashboard 3: Details
- Comprehensive grid view of all essential loan metrics and data points.



## Results
The analysis and dashboards provide valuable insights into loan applications, funded amounts, repayment patterns, and borrower profiles. These results help in making data-driven decisions and improving loan management strategies.

## Next Steps
Future enhancements to this project could include:
- Adding more advanced predictive analytics to forecast loan performance.
- Integrating real-time data updates to keep the dashboards current.
- Expanding the scope to include more financial products and services.

## Skills Demonstrated
### Technical Skills:
- **Data Analysis**: SQL, Data Preprocessing, Data Cleaning
- **Data Visualization**: Power BI, Dashboard Creation, Interactive Reports
- **Database Management**: MySQL, Data Connection Setup
- **Programming**: DAX (Data Analysis Expressions), SQL

### Non-Technical Skills:
- **Problem Solving**: Identifying key metrics, designing solutions to visualize data effectively
- **Attention to Detail**: Ensuring accuracy in data analysis and visualization
- **Communication**: Documenting processes, creating presentations, explaining technical details to a non-technical audience

