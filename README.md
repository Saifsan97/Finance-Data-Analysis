# Bank-Loan-Data-Analysis
 ![Loan Logo](https://www.paymentsdive.com/imgproxy/z8XI7jiVIoY3LyRSMEANFKLJ0VVe5yVObShcA-KRl6E/g:ce/rs:fill:1200:675:1/bG9jYWw6Ly8vZGl2ZWltYWdlL0dldHR5SW1hZ2VzLTY0NDE5MTczOF92TTNPcjJ1LmpwZw==.webp)
 
 
# Introduction:
This project is focused on designing a robust dashboard to track and analyze key performance indicators (KPIs) related to the bank’s lending operations. The dashboard will offer real-time visibility into essential metrics such as loan applications, funded amounts, repayments, and borrower characteristics. By incorporating advanced data visualizations, the tool will highlight monthly trends, regional activity, and borrower profiles, providing a holistic view of the lending landscape.

The project aims to support the bank's efforts in making informed decisions, optimizing lending strategies, and enhancing overall operational efficiency. Through the careful monitoring of key metrics, the bank will be able to respond proactively to changes in the lending environment and address potential risks or opportunities as they arise. 
The analysis is further enhanced with advanced visualizations and explorations using SQL, Excel, and Tableau.

# Objective:
The primary objectives of this project are to develop a comprehensive, data-driven dashboard that will allow the bank to:

* **Track Loan Applications**: Measure the total number of loan applications, including Month-to-Date (MTD) and Month-over-Month (MoM) changes, to gain insight into the trends and demands of loan applicants.
  
* **Monitor Disbursed Loans**: Calculate and track the total amount of loans funded during a specific period, including MTD funded loans and MoM changes, to understand lending volumes and variations over time.
  
* **Assess Loan Repayment**: Track the total amount received from borrowers and analyze MTD and MoM changes to evaluate the bank's cash flow and repayment patterns.
  
* **Analyze Financial Health**: Calculate the average interest rate and Debt-to-Income (DTI) ratio across all loans, providing a comprehensive look at the cost of lending and the financial stability of borrowers.
  
* **Visualize Lending Patterns**: Provide detailed data visualizations, including monthly trends, regional analysis, loan term distributions, and borrower demographics, allowing for better insights into loan activity across different dimensions.
  
* **Support Decision-Making**: Enable stakeholders to make data-informed decisions by identifying lending trends, understanding borrower behavior, and recognizing regional disparities in loan applications and funding.
  


 # Tools used:

1. **Microsoft Excel** - to clean the dataset
2. **Excel & MySQL** - to data normalization and analysis process
3. **Datawrapper** - to create data visualizations
4. **Tableau** - to create dashboard
5. **GitHub** - for documentation

# Data Dictionary:

| Column name  | Description |
| :---   | :--- |
| Loan ID |  Loan ID is a unique identifier assigned to each loan application or loan account. It serves as a primary key for tracking and managing individual loans |
| Address State |   The U.S. state where the borrower resides, represented by its two-letter abbreviation |
| Employment Length |   The length of time the borrower has been employed (e.g., "10+ years", "2 years") |
| Employment Title |   The borrower's occupation or job title. It helps lenders understand the source of the borrower's income |
| Grade |   The assigned risk grade for the loan (e.g., A, B, C) |
| Subgrade |   A more detailed risk rating within the grade (e.g., A1, B2) |
| Home Ownership |  The borrower's home ownership status (e.g., "Rent", "Mortgage", "Own") |
| Issue Date |  	 The date when the loan was issued |
| Last Payment Date |  The most recent loan payment received |
| Loan Status	|   The current status of the loan, such as "Fully Paid," "Charged Off," etc |
| Purpose	|  The reason for the loan (e.g., "Debt Consolidation", "Home Improvement") |
| Loan Term |   The length of the loan (e.g., "36 months", "60 months") |
| Verification Status	|  Indication whether the borrower's financial information has been verified |
| Annual Income	|  The borrower's total yearly earnings. It assesses repayment capacity |
| Debt to Income (DTI) |   The Ratio of borrower’s monthly debt payments to their income |


# Recommendations for various stakeholders:

## Bank Employees
* **Advanced Employee Performance Metrics**: Develop tools to track employee-specific KPIs, such as loan officer performance, application approval rates, and customer satisfaction, to enhance individual accountability and productivity.

*  **Enhance Customer Interaction for Mortgage Holders and Renters**: Focus on offering personalized loan products, such as refinancing options, home equity loans, and tailored personal loans for renters, particularly for home improvement and debt consolidation. 
*  **Data-Driven Loan Offerings**: Use the data to guide personalized loan offers. For example, customers with strong repayment histories could receive targeted offers for larger loans, lower interest rates, or refinancing options.
*  **Gather More Customer Insights**: Employees should collect data and conduct surveys to better understand why certain customer segments, like "none" and "other," have minimal engagement with the bank's loan offerings.



## Bank Management
* **Predictive Analytics for Strategic Planning**: Integrate AI and machine learning models that can predict future loan demand, repayment likelihood, and default risks. These tools can assist management in setting more accurate financial targets and adjusting strategies in advance.
* **Geographical Targeting**: Focus on regions where loan applications are low but repayment rates are high, like certain underutilized states. Marketing campaigns and outreach programs tailored to high-potential regions could increase loan applications. Regions such as California, Texas, New York, and Florida demonstrate high loan activity and repayments. Management should continue to focus on these areas, but also consider expanding to underrepresented states with good repayment rates, such as Washington, Colorado, and Massachusetts.

* **Product Innovation for Underrepresented Groups**: Investigate opportunities in the "none" and "other" homeownership categories. Even though these segments are small, there may be a niche for unique financial products, such as shared housing loans or alternative housing financing.

* **Leverage Employee Tenure Data**: Utilize the insights from employee length of employment to develop loan products targeting mid-career professionals. Employees with 2 to 5 years of tenure tend to be high loan applicants with strong repayment, so specialized loan products for this group, like career development loans or advanced education loans, could be attractive.

* **Monitor External Economic Trends**: Incorporate economic indicators such as changes in interest rates, inflation, and housing market trends into future loan projects. This will help the bank to be more adaptable to market shifts and continue targeting the right customer segments.







# Limitation of the project:

  
* **Regional Disparities**: Some states have negligible loan activity. The bank’s market penetration appears to be uneven across regions, potentially missing growth opportunities in underrepresented states.
  
* **Narrow Loan Terms**: The data only reflects two loan term options: 36 months and 60 months, which limits insight into customer preferences for other potential loan durations, such as shorter-term or longer-term loans (e.g., 12 months, 48 months). This gap restricts understanding of broader customer needs.
  
* **Lack of Creditworthiness Data**: The analysis does not account for credit scores, income levels, or debt-to-income ratios. This omission limits the bank's ability to understand the risk associated with different borrower groups and the likelihood of defaults.
  
* **Limited Data on Certain Demographics**: There is very little data on loan applications from the "none" and "other" homeownership categories. This limits the bank's understanding of potential market opportunities or challenges in these smaller segments.








