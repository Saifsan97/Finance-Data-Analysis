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
2. **MySQL** - to data normalization and analysis process
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
| Last Credit Pull Date |  The records when the borrower's credit report was last accessed |
| Last Payment Date |  The most recent loan payment received |
| Loan Status	|   The current status of the loan, such as "Fully Paid," "Charged Off," etc |
| Next Payment Date |  The date of the next loan payment. It assists in cash flow forecasting |
| Purpose	|  The reason for the loan (e.g., "Debt Consolidation", "Home Improvement") |
| Loan Term |   The length of the loan (e.g., "36 months", "60 months") |
| Verification Status	|  Indication whether the borrower's financial information has been verified |
| Annual Income	|  The borrower's total yearly earnings. It assesses repayment capacity |
| Debt to Income (DTI) |   The Ratio of borrower’s monthly debt payments to their income |
| Installment |   The monthly payment amount the borrower must pay |
| Interest Rate |   The percentage interest charged on the loan, stored as a decimal value |
| Loan Amount |  The total amount of the loan, typically stored with two decimal places for precision  |

# Recommendations for various stakeholders:

## Bank Employees
* **Advanced Employee Performance Metrics**: Develop tools to track employee-specific KPIs, such as loan officer performance, application approval rates, and customer satisfaction, to enhance individual accountability and productivity.

* **Loan Risk Prediction Models**: Implement predictive analytics using machine learning to provide employees with early warnings on high-risk loans based on historical borrower behavior, improving loan approval decisions and risk management.

## Bank Management
* **Predictive Analytics for Strategic Planning**: Integrate AI and machine learning models that can predict future loan demand, repayment likelihood, and default risks. These tools can assist management in setting more accurate financial targets and adjusting strategies in advance.

* **Granular Regional Analysis**: Develop more detailed regional insights, possibly by city or neighborhood, allowing management to identify micro-market trends and tailor regional lending strategies accordingly.



# Limitation of the project:

* **Data Dependency**: The effectiveness of the dashboard heavily depends on the accuracy and completeness of the data input. Any inconsistencies or delays in data collection may result in skewed results, leading to misinformed decision-making.
  
* **Limited Predictive Capabilities**: The current system is focused on historical data analysis and trend identification, but it lacks predictive analytics or machine learning capabilities that could forecast future loan demand or borrower behavior.
  
* **Regional Insights May Lack Granularity**: While the dashboard provides regional analysis by state, it may not offer sufficient granularity to assess lending trends at a more localized level (e.g., by city or county), which might be crucial for certain decision-making processes.
  
* **Static Visualizations**: The dashboard is limited to pre-defined KPIs and visualizations. It lacks real-time customization features that allow users to adjust filters, compare different periods dynamically, or conduct ad-hoc analysis based on emerging questions.




