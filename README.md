# Customer Behavior Analytics: Revenue, Retention, Subscription & Product Insights

> A portfolio-grade end-to-end analytics project focused on uncovering **customer revenue drivers, subscription value, discount efficiency, lifecycle behavior, and product demand insights** using **SQL, Power BI, and executive reporting**.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Business Objectives](#-business-objectives)
- [Dataset Overview](#-dataset-overview)
- [Tools & Technologies](#-tools--technologies)
- [Project Workflow](#-project-workflow)
- [Repository Structure](#-repository-structure)
- [Key Executive Insights](#-key-executive-insights)
- [SQL Business Questions Solved](#-sql-business-questions-solved)
- [Power BI Dashboard Preview](#-power-bi-dashboard-preview)
- [Executive Slide Preview](#-executive-slide-preview)
- [Strategic Recommendations](#-strategic-recommendations)
- [Business Impact](#-business-impact)
- [Power BI Integration](#-power-bi-integration)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---
  .                          <img width="600" height="406" alt="image" src="https://github.com/user-attachments/assets/abf2a64d-90fe-479d-b927-fde8c41310a9" />

## 📖 Project Overview

This project analyzes **3,900 customer purchase records** from `cx.csv` to identify the most important **commercial growth opportunities** across:

- Revenue concentration
- Customer loyalty
- Discount optimization
- Subscription performance
- Product satisfaction
- Product demand
- Customer lifecycle behavior
- Revenue by age bands

The project transforms raw transactional customer data into:

- **SQL-driven business answers**
- **Power BI executive dashboards**
- **stakeholder-ready PowerPoint storytelling**
- **strategic recommendations for growth**

This is designed as a **decision-support analytics case study** relevant to:
- Retail analytics
- Product analytics
- Customer intelligence
- Growth strategy
- CRM optimization
- Subscription business models

---



## 🎯 Business Problem

The business needs to understand:

- which customer groups contribute the most revenue
- whether discounts are improving valuable orders
- whether subscription is truly increasing customer value
- which products deserve promotion priority
- how customer lifecycle segments behave
- where retention opportunities exist
- how age demographics affect commercial performance

Without this visibility, pricing, campaigns, and retention strategies risk being **too broad and inefficient**.

---

## 🎯 Business Objectives

The main objective is to support leadership with **data-driven decisions** around:

1. Revenue optimization
2. Customer retention
3. Promotion efficiency
4. Subscription redesign
5. Product prioritization
6. Segment-based targeting
7. Power BI executive dashboarding

---

## 📊 Dataset Overview

- **Dataset:** `cx.csv`
- **Total Records:** 3,900
- **Total Revenue:** **$233,081**
- **Primary Grain:** customer purchase transaction level

### Key Features
- Gender
- Age
- Purchase Amount
- Subscription Status
- Shipping Type
- Product Category
- Product Name
- Review Rating
- Discount Applied
- Previous Purchases

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|---|---|
| SQL | Business question analysis |
| Power BI | Dashboarding and stakeholder reporting |
| Excel / CSV | Source dataset |
| Markdown | Documentation |
| PowerPoint | Executive storytelling |
| GitHub | Version control and portfolio publishing |

---

## 🔄 Project Workflow

1. Raw data inspection
2. SQL business question design
3. Query-level insight generation
4. KPI development
5. Power BI dashboard build
6. Executive slide storytelling
7. Strategic recommendation design
8. Portfolio publication on GitHub

---

## 📂 Repository Structure

```bash
customer-behavior-analytics/
│
├── data/
│   └── cx.csv
│
├── sql/
│   ├── q1_revenue_by_gender.sql
│   ├── q2_discounted_above_average.sql
│   ├── q3_top_rated_products.sql
│   ├── q4_shipping_comparison.sql
│   ├── q5_subscription_performance.sql
│   ├── q6_discount_rate_by_product.sql
│   ├── q7_customer_segments.sql
│   ├── q8_top_products_by_category.sql
│   ├── q9_repeat_buyer_subscription.sql
│   └── q10_revenue_by_age_group.sql
│
├── dashboard/
│   ├── customer_behavior_dashboard.pbix
│   └── screenshots/
│
├── reports/
│   ├── executive_report.md
│   └── executive_slides.pptx
│
├── images/
│   ├── dashboard_overview.png
│   ├── executive_summary_slide.png
│   ├── customer_segments.png
│   └── subscription_analysis.png
│
└── README.md
