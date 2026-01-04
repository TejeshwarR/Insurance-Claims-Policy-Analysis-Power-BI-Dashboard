# 🛡️ Insurance Claims & Policy Analysis – Power BI Dashboard

## 📌 Project Overview
This project presents an **end-to-end Insurance Analytics solution built using Power BI**, with data sourced from **Microsoft SQL Server (MSSQL)** and supplemented by a **cleaned CSV extract** for analysis and portability.

The dashboard provides insights into **premium collection, claim amounts, policy status, customer demographics, and claim outcomes**, enabling stakeholders to monitor **risk exposure, operational efficiency, and portfolio health**.
<img width="1330" height="723" alt="image" src="https://github.com/user-attachments/assets/e10ba2f6-55f9-4582-a1ae-fda8c1641ca6" />
<img width="1338" height="770" alt="image" src="https://github.com/user-attachments/assets/b5277c4e-248f-48a7-9caf-2fe4959ff951" />


---

## 🎯 Goal of the Project
The primary goals of this project are to:

- Analyze **insurance premium and claim performance**
- Track **policy activity** *(Active vs Inactive)*
- Understand claim distribution by **status, age group, and policy type**
- Support business decisions related to **underwriting, claims management, and customer segmentation**

---

## 🗄️ Data Source & Ingestion

### 🔹 Primary Data Source
- **Microsoft SQL Server (MSSQL)**
  <img width="1258" height="817" alt="Screenshot 2025-12-28 200340" src="https://github.com/user-attachments/assets/2270ea5f-4672-4f4d-8edf-62786982b28c" />

- Data extracted from insurance transactional tables including:
  - Policies  
  - Customers  
  - Premiums  
  - Claims  

### 🔹 Secondary / Attached File
- **InsuranceData.csv**

This file is a **downloaded and cleaned extract from MSSQL**, attached for:
- Data validation  
- Reproducibility  
- Portfolio review without database dependency  

### 🔹 Power BI Model
- Data imported into Power BI using **Import mode**
- Relationships defined between **Policy, Customer, and Claims tables**
- **DAX measures** created for KPIs and aggregations

---

## 📂 Project Files
- **insurance_dashboard.pbix** – Power BI dashboard and data model  
- **InsuranceData.csv** – Cleaned data exported from MSSQL Server  

---

## 🔄 Procedure / Methodology

### 1. Data Extraction
- Queried insurance data from **MSSQL Server** using SQL

### 2. Data Cleaning & Preparation
- Cleaned null values  
- Standardized **policy types, claim statuses, and age groups**
- Exported validated data to CSV

### 3. Data Import into Power BI
- Imported cleaned CSV into Power BI
- Cross-validated results with MSSQL outputs

### 4. Data Modeling
- Established relationships between fact and dimension tables
- Created calculated measures for:
  - Premium Amount  
  - Claim Amount  
  - Coverage Amount  
  - Policy & Claim Counts  

### 5. Dashboard Development
- Designed:
  - KPI cards  
  - Charts  
  - Tables  
  - Interactive slicers  

### 6. Insight Generation
- Interpreted visuals to derive **business insights and recommendations**

---

## 📊 Dashboard Highlights
- KPI Cards:
  - **Premium Amount**
  - **Coverage Amount**
  - **Claim Amount**
- Policy-level premium distribution by **policy type**
- **Active vs Inactive** policy ratio
- Claim count by **claim status** *(Rejected, Settled, Pending)*
- Claim amount by **age group**
- Policy-type-wise **claim settlement table**
- Interactive slicers for:
  - Claim Number  
  - Policy Number  
  - Customer ID  

---

## 📈 Visualization-Based Insights

### 1️⃣ Overall Portfolio Summary
- **Total Premium Amount:** 5.97M  
- **Total Coverage Amount:** 600.33M  
- **Total Claim Amount:** 16.90M  

**Insight:**  
High coverage exposure relative to premiums highlights the importance of effective **risk assessment and claim control**.

---

### 2️⃣ Premium Amount by Policy Type
- **Travel** policies generate the highest premium
- **Health** and **Auto** follow as major contributors
- **Home** and **Life** policies contribute relatively less

**Insight:**  
Travel and Health policies are key **revenue drivers** and should be prioritized for growth strategies.

---

### 3️⃣ Active vs Inactive Policies
- **Active Policies:** ~58%  
- **Inactive Policies:** ~42%  

**Insight:**  
A significant inactive base indicates strong opportunities for **renewals and customer re-engagement campaigns**.

---

### 4️⃣ Claim Status Analysis
- **Rejected claims** form the largest share
- **Settled claims** represent a substantial portion
- **Pending claims** indicate operational backlog

**Insight:**  
High rejection rates may signal **strict underwriting criteria or documentation gaps**.

---

### 5️⃣ Claim Amount by Age Group
- **Adults** account for the highest claim amount
- **Elder** group shows moderate claim value
- **Young adults** contribute the least

**Insight:**  
The adult age group represents the **highest risk exposure segment**.

---

### 6️⃣ Policy Type vs Claim Outcome
- **Travel** and **Health** policies have the highest settled claim amounts
- **Auto** and **Home** policies show higher pending/rejected ratios

**Insight:**  
Claim settlement efficiency varies by policy type, requiring **targeted operational improvements**.

---

## ⭐ Key Business Insights
- Premium concentration in **specific policy types**
- High **coverage-to-premium ratio** increases risk exposure
- Adult customers drive the majority of claims
- Large inactive policy base presents **retention opportunities**
- Claim outcomes vary significantly across policy types

---

## 🧠 Business Recommendations
1. Improve **renewal strategies** for inactive policies  
2. Strengthen underwriting for **high-claim policy types**  
3. Optimize claim settlement processes to **reduce pending cases**  
4. Use **age-based risk profiling** for pricing strategies  

---

## 🚀 Next Steps
- Sentiment analysis using Insurance+Customer+Feedback.xlsx data
- Implement **DirectQuery with MSSQL** for real-time dashboards
- Add **fraud detection** and **claim severity analysis**
- Build **SLA tracking** for claim settlement timelines
- Enhance the model with **historical trends and forecasting**

---

## 👤 Author
**Tejeshwar R**  
Data Analyst | Power BI | SQL | Excel | Python | Statistics
