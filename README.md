# Home-Loan-Eligibility-Analysis
Project: Exploratory Data Analysis of Home Loan Eligibility with Dashboard Reporting
🔹 Project Description
This project focuses on analyzing the factors that influence home loan eligibility using real-world loan application data. Instead of building complex ML models, the objective is to apply Exploratory Data Analysis (EDA) and create a dashboard that provides insights into loan approval patterns.

Banks and financial institutions rely heavily on data-driven decision making. This project demonstrates how a Data Analyst can:

•	Clean and preprocess raw financial datasets.
•	Explore and identify trends in loan approval.
•	Build a dashboard for business stakeholders to quickly assess key factors affecting loan eligibility.
________________________________________
🔹 Objectives

1.	Understand the key factors that influence loan approval.
2.	Perform data cleaning and transformation for accurate analysis.
3.	Use EDA techniques to generate meaningful insights.
4.	Build an interactive dashboard to visualize results.
________________________________________
🔹 Methods / Approach
1. Data Collection

•	Dataset: Loan Prediction Dataset (Kaggle).
•	Contains applicant details like:
o	ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term
o	Credit_History, Gender, Education, Marital Status, Property_Area
o	Loan_Status (Approved / Rejected)
________________________________________
2. Data Cleaning & Preprocessing

•	Handle missing values: median (numeric), mode (categorical).
•	Encode categorical variables: Gender, Education, Property_Area, etc.
•	Feature Engineering:
o	TotalIncome = ApplicantIncome + CoapplicantIncome
o	Loan_Income_Ratio = LoanAmount / TotalIncome
o	EMI = LoanAmount / Loan_Amount_Term
________________________________________
3. Exploratory Data Analysis (EDA)

•	Univariate Analysis → Histograms & boxplots (Income, LoanAmount).
•	Bivariate Analysis →
o	Loan Approval % by Credit History
o	Loan Approval rate by Property_Area
o	Income vs Loan Amount scatterplot
o	Education & Gender impact on Loan_Status
•	Insights derived with charts and summary statistics.
________________________________________
4. Dashboard Development

•	Tools: Power BI / Tableau / Excel
•	Visuals included:
  o	Loan Approval Rate (KPI card)
  o	Credit History vs Approval % (bar chart)
  o	Property_Area-wise approval rate (stacked bar)
  o	Gender/Education breakdown (grouped bar)
  o	Loan Amount distribution (histogram)
•	Slicers/Filters: Gender, Education, Property_Area.
________________________________________
5. Conclusion / Insights

•	Applicants with good credit history had significantly higher approval chances.
•	Income and Loan Amount ratio plays a major role in approval.
•	Urban applicants had slightly higher approval rates compared to rural.
•	Female applicants and graduates showed slightly better approval rates.
________________________________________
🔹 Tools & Technologies Used

•	Python (for EDA & preprocessing): Pandas, Numpy, Matplotlib, Seaborn
•	Power BI / Tableau / Excel (for dashboard visualization)
•	Jupyter Notebook / Google Colab / VS Code (for coding environment)
________________________________________
🔹 Deliverables
•	Cleaned dataset ready for analysis.
•	Jupyter Notebook with EDA code and insights.
•	Interactive dashboard (Power BI / Tableau).
•	Final Presentation (PPT) summarizing process, visuals, and insights.
