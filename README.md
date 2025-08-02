# 📊 Power BI Project – Insurance Data Analysis with RLS, Sentiment & Word Cloud

This Power BI project presents an advanced analysis of insurance data, integrating customer sentiment feedback, secure row-level access, and AI-powered insights. The dashboard combines SQL Server connectivity, Power Query transformation, and enhanced storytelling visuals like word clouds and drillthrough pages.

---

## 📁 Project Overview

The objective is to analyze insurance policy and claim data along with customer feedback to identify trends, understand sentiment, and support business decision-making. The data is sourced from both **structured Excel/CSV files** and **SQL Server**, processed in Power BI, and published to Power BI Service with automated refresh and RLS.

---

## 📦 Datasets Used

### 🔹 `InsuranceData.csv`
- Contains policy-level and claim-level details for 10,000+ customers  
- Key fields: `PolicyNumber`, `PolicyType`, `Premium`, `Claim Amount`, `Claim Status`, `Gender`, `Age`

### 🔹 `Insurance Customer Feedback.xlsx`
- Contains free-text customer feedback  
- Used for **Sentiment Analysis** and **Word Cloud generation**  
- Processed using AI functions in Power Query

---

## 🛠️ Tools & Techniques Used

- **Microsoft SQL Server** – backend data storage  
- **Power BI Desktop** – dashboard creation  
- **Power Query Editor** – for:
  - Column profiling and type correction  
  - Data cleaning and deduplication  
  - **Sentiment tagging** with built-in AI  
- **DAX** – to define calculated KPIs  
- **Row-Level Security (RLS)** – applied in Desktop and published to Service  
- **Power BI Service** – used for refresh scheduling, sharing, and RLS testing  
- **Custom Visual** – Word Cloud for feedback analysis

---

## 📊 Visuals & Features

- **Bar & Line Chart** – for performance trends  
- **Donut Chart** – breakdown by claim status or policy type  
- **Ribbon Chart** – to compare top/bottom categories  
- **KPI Cards & Multi-Row Cards** – for aggregated insights  
- **Matrix View** – detailed tabular display  
- **Drillthrough Filters** – e.g., by Policy Type  
- **Slicers & Textboxes** – for interactive storytelling  
- **Word Cloud** – customer feedback visualization  
- **Sentiment Analysis** – Positive, Neutral, Negative classification  
- **Row-Level Security (RLS)** – restricts view by roles  
- **Scheduled Refresh** – via Power BI Service

---

## 🚀 Key Learnings

- Connecting Excel and SQL data into one Power BI model  
- Performing sentiment analysis using Power Query AI  
- Using custom visuals for better engagement (Word Cloud)  
- Enforcing data security using RLS  
- Publishing and maintaining reports in Power BI Service

---

## 📂 Files Included

- `power_bi_project_2.pbix` – Final Power BI dashboard  
- `InsuranceData.csv` – Policy and claims data  
- `Insurance Customer Feedback.xlsx` – Text feedback used for sentiment analysis & word cloud
- `Page_1.png` – Dashboard overview  
- `Page_2.png` – Claims & Policy analysis  
- `Page_3.png` – Sentiment & Word Cloud visuals


---

## 📌 Credits

This project was developed as part of the **Power BI course by Krish Naik on Udemy**.  
The dataset used is synthetic and intended for educational purposes only.
