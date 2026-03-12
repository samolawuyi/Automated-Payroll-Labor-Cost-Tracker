# Automated-Payroll-Labor-Cost-Tracker
This project is an automated Payroll Processing Model designed to manage and calculate employee compensation across multiple pay periods. It provides a robust framework for handling hourly wages, overtime hours, and total fiscal liabilities..
How it Works
​The workbook utilizes a horizontal data flow to process labor costs through several logical stages:
​The Calculation Pipeline
​Input Layer: Hourly wages and weekly hours worked.
​Logic Layer (Overtime): Extracts hours exceeding standard thresholds to calculate "Overtime Hours" separately.
​Financial Layer:
​Regular Pay: Hours \times Wage
​OT Pay: Calculated based on premium rates (e.g., OT Hours \times Wage \times 1.5).
​Total Pay: Summation of regular and premium compensation.
​Analytical Summaries
​The bottom of the sheet features a Summary Statistics section that provides:
​Average Hourly Wage: For workforce benchmarking.
​Total Expenditure: Real-time tracking of the total "Semester" or period budget.
​High/Low Earners: Quick identification of employees with the highest and lowest payouts for resource allocation review.
​Technical Implementation
​Formula Architecture: Extensive use of SUM, AVERAGE, and arithmetic operators to link 5 weeks of data into a final "Semester Pay" column.
​Data Validation: Ensures consistency across different pay periods.
​Visual Hierarchy: Integrated color-blocking (Red for OT Pay, Green for Regular) to facilitate quick error-checking during the auditing process.
​Impact
​This tool replaces manual "paper-and-pen" or simple calculator methods, reducing the risk of payment errors and providing clear, auditable documentation for both employers and employees.
