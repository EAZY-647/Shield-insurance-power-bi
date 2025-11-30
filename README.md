# 🛡️ Shield Insurance Data Analysis

## 📄 Project Overview
This repository contains the source code (`.pbix`) for the **Shield Insurance Executive Dashboard**. This project is an end-to-end business intelligence solution designed to monitor KPIs, analyze monthly trends, and segment customer demographics for a simulated insurance provider.

**Note:** This is a comprehensive practice project demonstrating data modeling, complex DAX calculations, and interactive reporting.

## 💼 Business Problem
The goal of this dashboard is to provide a 360-degree view of business performance, helping stakeholders answer critical questions such as:
* How is revenue trending month-over-month?
* Which regions and sales modes are driving the most growth?
* Who is our target customer demographic?

## 📊 Key Insights & Findings
Based on the analysis of the dataset (Snapshot: Jan 2023):

* **Revenue Health:** The business generated **$141M** in revenue with a customer base of approximately **3,900** active policyholders.
* **Seasonality Trends:** The dashboard identifies a major seasonal revenue spike in March (peaking at **$264M**), signaling a critical window for operational scaling.
* **Regional Dominance:** **Delhi NCR** is the top-performing market, contributing **$58.1M** (approx. 40%) to the total revenue.
* **Customer Segmentation:** The **31-40 Age Group** was identified as the highest-value segment, outperforming other demographics in both revenue contribution and retention.

## 🛠️ Technical Implementation
* **Data Cleaning:** Used Power Query to transform raw data and ensure data quality.
* **Data Modeling:** Established a Star Schema architecture connecting Sales, Customer, and Date tables.
* **DAX Measures:** Implemented time-intelligence functions to calculate MoM (Month-over-Month) growth and dynamic aggregations.
* **Features:** The report includes cross-filtering, page navigation buttons, and dynamic slicers.

## 📥 How to View the Dashboard
Since this is an interactive Power BI file:
1.  **Download** the `ayush Shield Insurance.pbix` file from the file list above.
2.  Open the file using **Microsoft Power BI Desktop**.
3.  Interact with the slicers (City, Mode, Month) to see the visuals update in real-time.

---
**Author:** [Your Name]
