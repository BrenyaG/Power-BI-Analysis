# Zomato Customer Segmentation Analysis (2017–2020)

## 📊 Project Overview

This repository contains a data analysis project focused on **customer segmentation and behavioral trends on the Zomato platform** from 2017 to 2020. The goal is to uncover who Zomato’s customers are, how they behave, and what factors influence their engagement, retention, and spending. The project was developed using **Power BI** for data visualization and dashboarding.

## 🚀 Executive Summary

- Zomato’s core user base is composed of young adults aged **18–24**, with highly volatile ordering and spending patterns.
- Despite strong acquisition (especially in 2018), **retention is a challenge**: ~65% churn within their first year.
- Average order value is steady, but **repeat usage is low**, indicating gaps in customer loyalty.
- Suggested improvements include:
  - Short-term: push notifications, incentives.
  - Medium-term: loyalty program enhancements, churn prediction.
  - Long-term: targeting older age groups and diversifying services.

## 🎯 Business Objectives

- Segment customers based on **demographics**, **spending**, and **behavioral patterns**.
- Identify purchasing habits, retention rates, and frequency of engagement.
- Generate actionable insights to **boost user engagement**, improve **service quality**, and **streamline operations**.

## 🔍 Key Questions

- Who are Zomato’s customers?
- How can they be segmented by age, income, and order behavior?
- What drives retention and churn?
- How do ordering patterns vary by cohort and over time?

## 📁 Data Sources

- **Users Table**: Age, gender, occupation, education, family size, and income.
- **Orders Table**: Order dates, user IDs, and sales amounts. Derived columns include cohort year, order bins, and years active.
- **Menu Table**: Food items, cuisine types, and restaurant relationships.

> **Note:** Direct menu-to-order mapping was not possible due to missing order-item links, a known data limitation.

## 🛠️ Methodology

- Data cleaning and joining via `user_id`, `r_id`, and `f_id` keys.
- Feature engineering: age groups, order frequency bins, first-order indicators, and cohort grouping.
- Visual analysis using **Power BI dashboards**, leveraging DAX expressions for temporal and cohort-based segmentation.
- Core techniques: trend analysis, cohort analysis, segmentation modeling.

## 📈 Key Insights

### 📌 Sales Trends
- Sales peaked in **2018**, particularly for the **18–24** segment.
- Sharp decline in 2019–2020 indicates poor retention post-acquisition.

### 📌 Order Frequency
- High frequency in year one followed by significant drop-off.
- 18–24 group placed the **majority of orders** but had lower repeat usage.

### 📌 Retention & Churn
- Most users churn within the **first 12 months**.
- Only a small fraction make it to year two or three.
- Retention is the biggest opportunity for improving revenue and engagement.

## 📊 Tools Used

- [Power BI](https://powerbi.microsoft.com/) for data visualization and dashboarding.
- DAX for custom measures and calculated columns.

## 📌 Deliverables

- Interactive Power BI report
- Segmentation insights by age, income, and behavior
- Recommendations for Zomato’s product and marketing teams

## ✅ Recommendations

| Time Frame   | Action Items                                                  |
|--------------|---------------------------------------------------------------|
| Short-term   | Push notifications, targeted offers, cart abandonment nudges |
| Medium-term  | Loyalty programs, churn prediction models                     |
| Long-term    | Expand to new demographics and services                       |

## Data Visualizations
https://docs.google.com/document/d/1zMhETHcWht2p9KefmgiFwmxwHEglu6ixkD3h7Oq_f_Y/edit?usp=sharing

## 📂 Repository Structure

```bash
📁 Zomato-Customer-Segmentation/
│
├── README.md                  # Project documentation
├── /data/                     # Sample anonymized data files
├── /visuals/                  # Exported Power BI visualizations (PNG/PDF)
├── Zomato_Segmentation.pbix   # Power BI dashboard file
├── report_summary.pdf         # Executive summary of findings
└── insights_notes.txt         # Analyst notes and business implications
