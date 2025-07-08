#  Loan Default Insights – Power BI Project

## Table of Contents
- [Project Objective](#project-objective)
- [Dataset Overview](#dataset-overview)
- [Business Questions Answered](#business-questions-answered)
- [Power BI Report Features](#power-bi-report-features)
- [Tools & Technologies](#tools--technologies)
- [AI Assistance Used](#ai-assistance-used)
- [Project Workflow](#project-workflow)
- [Dashboard Previews](#-dashboard-previews)
- [Project Insight](#project-insight)
- [Final Conclusion](#final-conclusion)

---

##  Project Objective

This project simulates analyzing and visualizing loan default behavior to identify high-risk customer segments based on income, bank balance, and employment status. The entire analysis is built in Power BI.

---

##  Dataset Overview

* **Provided**: Employed status, Bank balance, Annual salary, Defaulters
* **Custom**: Salary group, Balance group, Risk profile, Defaulted status, Employed Status

---

##  Business Questions Answered

1. **Which salary groups have the highest default rate?**
2. **How does default rate change across risk profiles (Low/Medium/High)?**
3. **Is there a pattern between Annual Salary and Risk Profile?**
4. **Does a higher bank balance reduce the risk of default?**
5. **Which balance group (Bronze/Silver/Gold) has the lowest repayment success?**
6. **Are "Employed" users more likely to default than "Self-employed"?**
7. **Can we identify a risky cluster?**
8. **What share of our customer base falls into the high-risk group?**

---

##  Power BI Report Features

###  KPIs

* Total Clients
* Avg Salary
* Default Rate
* High Risk %

###  Trend Analysis

* Default Rate per Risk Profile, Salary Group, Employment Status

###  Risk Segmentation

* Identifies high-risk segments using multi-factor logic

###  Comparative Analysis

* Salary vs Risk
* Balance vs Default Rate
* Employment vs Default Rate

###  Segmentation Tables

* Summary metrics by group for targeted action

###  Interactive Filters

* Risk Profile
* Employment Status
* Salary Group

---

##  Tools & Technologies

* **Power BI Desktop** – for data modeling and dashboard creation
* **Excel** – used for mock data creation and basic cleaning
* **DAX (Data Analysis Expressions)** – for custom measures and calculations

  * Examples: `DIVIDE`, `CALCULATE`, `COUNT`, etc.

---

##  AI Assistance Used

I used **ChatGPT** to:

* Suggest the best visual types for presenting insights
* Structure the dashboard pages to tell a clear business story

---


##  Project Workflow

Below are the main steps followed to build this Power BI project:

1. **Data Cleaning**

   * Checked for missing values, errors, and duplicate entries.
   * Cleaned and transformed data using Excel and Power Query in Power BI.

2. **Data Preparation**

   * Assigned correct data types to each column (e.g., dates, numbers, text).
   * Created few **conditional column** for categorizing bank balane, salary, employment and defalut status.
   * Renamed columns for clarity and consistency.

3. **Dashboard Planning**

   * Created multiple report pages based on business questions:

     * Income-Based Risk Segmantation
     * Financial Health & Default Behavior
     * High Risk Client Identification

4. **Report Building**

   * Designed interactive visuals and KPIs.
   * Applied slicers and filters (salary group, status, balance group).
   * Used **DAX** for custom calculations like default rate, average salary, total high risk clients

5. **Testing & Review**

   * Validated all visuals against source data.
   * Ensured performance and clarity for end users.

---

## 📸 Dashboard Previews

### 1️ Executive Summary
![Executive Summary](https://github.com/NinadShenoy/Loan_Default_Insights-Data_Visualization/raw/main/Screenshot-Executive%20Summary.png)

### 2️ Income-Based Risk Segmentation
![Income-Based Risk Segmentation](https://github.com/NinadShenoy/Loan_Default_Insights-Data_Visualization/raw/main/Screenshot-Income-Based%20Risk%20Segmentation.png)

### 3️ Financial Health & Default Behavior
![Financial Health & Default Behavior](https://github.com/NinadShenoy/Loan_Default_Insights-Data_Visualization/raw/main/Screenshot-Financial%20Health%20%26%20Default%20Behavior.png)

### 4️ High-Risk Client Identification
![High-Risk Client Identification](https://github.com/NinadShenoy/Loan_Default_Insights-Data_Visualization/raw/main/Screenshot-High-Risk%20Client%20Identification.png)

---

### **Project Insight**

The dashboard reveals clear patterns in default behavior. Clients with higher bank balances (Platinum tier) surprisingly show the highest default rate. Low-salary segments (Class B & C) default more, while a majority of defaulters are employed. Risk clusters like Low Risk–Platinum are major contributors. Overall, 3.61% of customers fall under the high-risk group.

---

###  **Final Conclusion**

To reduce future defaults, banks should re-evaluate customers with high balances but poor repayment history. Instead of assuming high salary or balance equals low risk, banks should track real behavior and segment users better. Sending reminders, doing regular check-ins, and being more careful with “Platinum” users can help reduce risks and improve repayments.


---
