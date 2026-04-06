# 📊 Banking Data Analysis | Excel Project

## 🔹 Overview
This project focuses on analyzing a banking dataset using Excel Power Query and Power Pivot to build a structured data model and extract meaningful business insights.

The goal is to transform raw data into a clean, well-structured analytical model and develop interactive dashboards that support decision-making in areas such as financial performance, customer behavior, and risk analysis.

## 🔹 Tools & Technologies
- Excel  
- Power Query (Data Cleaning & Transformation)  
- Power Pivot (Data Modeling)  
- DAX (Calculated Columns & Measures)  
- Pivot Tables (EDA & Dashboarding)  

## 🔹 Dataset Description
The dataset consists of multiple related tables:
- **Customers**: Customer demographics and profile data  
- **Accounts**: Bank account details and balances  
- **Transactions**: Financial transactions data  
- **Loans**: Loan details including amount, interest rate, and duration  
- **Branches**: Branch-level information  

## 🔹 Data Cleaning (Power Query)
The following steps were applied:
- Handled missing and inconsistent values  
- Standardized categorical data (e.g., Gender, Customer Type)  
- Removed unnecessary columns  
- Fixed incorrect data types  
- Extracted numeric values from mixed text fields  
- Ensured data consistency across tables  

## 🔹 Data Modeling (Power Pivot)
A relational data model was built using a Star Schema (Star-ish) approach.

**Important Design Decisions:**
- Removed the direct relationship between Transactions and Branches to avoid ambiguous filter paths  
- Relied on Accounts as the bridge between Transactions and Branches  
- Ensured all relationships follow One-to-Many (Dimension → Fact) principles  

## 🔹 Feature Engineering (DAX)
Several calculated columns were created to enhance analysis:
- Customer_Tenure_Years  
- Tenure_Category (New / Regular / Loyal)  
- Loan_Duration_Months  
- Annual_Interest_Rate_Decimal  
- Monthly_Interest_Rate  
- Monthly_Payment (PMT)  

## 🔹 Exploratory Data Analysis (EDA)
Pivot Tables were used to:
- Validate relationships between tables  
- Explore transaction patterns across time  
- Analyze branch performance  
- Understand customer segmentation  
- Identify trends and anomalies  

## 🔹 Dashboards
### 1️⃣ Overview Dashboard
Provides a high-level summary of:
- Total transactions  
- Total loan amount  
- Customer distribution  
- Account balances  

### 2️⃣ Financial & Risk Dashboard
Focuses on:
- Loan performance  
- Interest rates  
- Default risk indicators  
- Monthly payments  

### 3️⃣ Customer Behavior Dashboard
Analyzes:
- Customer segmentation  
- Tenure distribution  
- Loan behavior per customer  
- Income vs borrowing patterns  

### 4️⃣ Portfolio Performance Dashboard
Tracks:
- Loan growth over time  
- Payment trends  
- Portfolio health  
- Default trends  

## 🔹 Key Insights (Example)
- Branch performance varies significantly across cities  
- Customers with longer tenure tend to have higher engagement  
- Certain loan types show higher risk levels  
- Transaction volume trends highlight seasonal patterns  

## 🔹 Conclusion
This project demonstrates how Excel can be used as a powerful BI tool to:
- Build a structured data model  
- Perform advanced analysis using DAX  
- Deliver business insights through dashboards  

## 🔹 Author
**Ibrahim Abdulghfar**  
Aspiring Data Analyst  

🔗 LinkedIn:  
[www.linkedin.com/in/ibrahim-abdulghfar-a0b13a364](www.linkedin.com/in/ibrahim-abdulghfar-a0b13a364)