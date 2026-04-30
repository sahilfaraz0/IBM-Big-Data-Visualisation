# Big Data and Business Intelligence Transformation at IBM

**Author:** Sahil Faraz | **Date:** June 2025

> **Academic Disclaimer:** This repository contains an academic project for the **Pearson B-TEC HND in Digital Technologies (Cybersecurity) - Unit 21: Emerging Tecnologies** module. It is strictly for portfolio and demonstration purposes. Other students may not use or copy this material for their own academic submissions.

An in-depth data analysis and visualization project focused on improving decision-making procedures and operational efficiency for IBM's Big Data and Business Analytics division (Islamabad). This project transforms a raw dataset of 150 enterprise clients into strategic business intelligence using advanced data manipulation and statistical modeling.

## 📋 Project Overview
Data has become a strategic asset in the era of digital transformation. This project demonstrates how Data-Driven Decision Making (DDDM) empowers organizations to make smarter, faster, and more accurate decisions. By analyzing client revenue, churn risk, and AI adoption maturity, this project provides actionable insights for IBM's global operations.
![IBM Executive Dashboard](Images/dashboard.png)

## 🧠 Big Data Frameworks Applied
The analysis is grounded in the fundamental characteristics of Big Data:
* **Core Vs:** Handled data **Volume** (massive datasets), **Velocity** (speed of data generation), and **Variety** (structured/unstructured formats).
* **Extended Vs:** Ensured **Veracity** (data consistency/bias removal), managed **Variability**, applied interactive **Visualization**, and extracted business **Value**.
### Scientific Formulas for the Vs of Big Data:
| Vs of Big Data | Scientific Formula |
|------|-----------|
| Volume | ![Volume](Images/Volume.png) |
| Velocity | ![Velocity](Images/Velocity.png)  |
| Variety | ![Variety](Images/Variety.png)  |
| Variability | ![Variability](Images/Variability.png)  |
| Veracity | ![Veracity](Images/Veracity.png)  |
| Visualization | ![Visualization](Images/Visualization.png)  |
| Value | ![Value](Images/Value.png)  |

## 🛠️ Tools & Technologies
While industry-leading tools like Python, SQL, Power BI, and IBM Cognos Analytics were evaluated, this practical implementation was executed entirely in **Microsoft Excel** to demonstrate robust entry-level analysis, pivot aggregation, and dashboarding. 

## 🧹 Data Manipulation & Cleaning
To ensure data veracity, the dataset underwent rigorous preparation:
* **Data Cleansing:** Utilized `=TRIM()` and `=CLEAN()` to standardize formatting and remove invisible characters.
* **Deduplication:** Applied Excel's "Remove Duplicates" to eliminate redundant records.
* **Temporal Analysis:** Simulated subscription lifecycles using the `=EDATE()` function to calculate subscription end dates based on tenure.

## 📈 Statistical Analysis & Data Mining
Advanced statistical techniques were applied to extract meaningful patterns:

### 1. Regression Analysis
* Examined the correlation between **Monthly Subscription ($)** and **Predicted Client Lifetime Value ($)** to forecast trends.

### 2. A/B Testing
* Compared the Total IBM Revenue Contribution between churned and non-churned clients.
* **Result:** Non-churned average revenue ($4,108) vs. Churned average revenue ($4,292.75) yielded a p-value of **0.359109**, indicating specific revenue patterns.

### 3. Data Mining (High-Risk Churn Patterns)
* Utilized `COUNTIFS` to isolate specific client behaviors. For example, finding high-risk churned clients with low satisfaction:
  `=COUNTIFS(H2:H151,"Yes", I2:I151,">=4", G2:G151,"<=2")`

### 4. Descriptive Statistics
* Calculated aggregated metrics across regions and industries using `=SUMIF()`, `=AVERAGE()`, `=MAX()`, `=MIN()`, `=MEDIAN()`, and `=STDEV.P()`.

## 📊 Visualizations & Key Insights
The project features a comprehensive suite of visualizations to translate complex data into business intelligence:
* **Revenue Contribution by Industry (Bar Chart):** Revealed that **Healthcare ($89,826.77)** and **Government ($75,013.68)** are the most lucrative sectors.
* **Monthly Join Trend (Line Graph):** Tracked onboarding spikes, particularly in March, October, and November.
* **Client Risk & Satisfaction (Heatmap):** Color-coded matrix identifying concentrations of high-risk clients based on satisfaction scores.
* **Client Tenure Duration (Histogram):** Illustrated retention distribution, showing strong concentrations in the 27-35 month brackets.

<!-- PLACEHOLDER: Upload a screenshot of your Monthly Join Trend Line Chart here and name it 'trend.png' -->
![Monthly Join Trend](trend.png)

## ⚖️ Data Governance, Compliance & Ethics
As a Data Specialist, handling enterprise data required strict adherence to ethical and legal frameworks:
* **Regulatory Compliance:** Strategies were aligned with **GDPR, CCPA, and HIPAA** to ensure proper consent management, anonymization, and encryption of sensitive healthcare/financial data.
* **AI Bias Mitigation:** Monitored algorithmic fairness to prevent biased decision-making in high-stakes areas like loan approvals or risk assessments, ensuring trust and system transparency.

---
**Author:** Sahil Faraz  
**Focus:** HND in Digital Technologies (Cybersecurity) | Unit 5: Big Data & Visualisation
