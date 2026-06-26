# Customer Behavior Data Analyst Portfolio Project

This repository showcases a complete, industry-standard, end-to-end data analytics workflow designed to mirror the cross-functional responsibilities of a corporate Data Analyst. The project transitions seamlessly from programmatic data engineering to relational database warehouse design, analytical querying, and executive business reporting.

---

## 📌 Project Overview
The core objective of this project is to simulate an enterprise-grade analytics pipeline that translates raw, unstructured operational logs into strategic business intelligence. The workflow is executed across four main modules:

*   **Data Engineering & EDA (Python):** Programmatic ingestion, cleaning, feature transformation, and missing data architecture resolution.
*   **Relational Warehousing & Analytics (SQL):** Database schema population, performance indexing, and specialized query executions (CTEs, Window functions) to isolate customer lifetime habits.
*   **Business Intelligence (Power BI):** Construction of a highly optimized semantic data model and interactive visual ecosystem to track dynamic organizational KPIs.
*   **Executive Presentation & Reporting:** Distillation of analytical outputs into clear structural briefs and slide decks tailored for corporate stakeholders.

---

## 🛠️ Technologies Used
*   **Languages:** Python (Pandas, NumPy, Seaborn, Matplotlib), SQL (SQL Server / PostgreSQL / MySQL)
*   **Tools:** Jupyter Notebook, Power BI Desktop
*   **Core Methodologies:** Schema Normalization, Relational Modeling, Data Quality Control, Cohort Analysis, Segment Profiling

---

## 🔄 Project Workflow & Implementation

### Phase 1: Programmatic Engineering & Profiling
**File:** `Customer_Shopping_Behavior_Analysis.ipynb`
*   **Inspection & Integrity Auditing:** Programmatic evaluation of missing value matrices, invalid data entry types, and statistical anomalies.
*   **Data Wrangling & Standardization:** Enforced schema uniformity, stripped string formatting issues, and handled structural multi-collinearity outliers.
*   **Engine Connectivity Pipeline:** Automated local dataframe conversions into valid relational table mappings via database dialect wrappers (`SQLAlchemy`).

### Phase 2: Relational Schema & Database Seeding
*   **Warehouse Instantiation:** Established clean storage containers within the designated SQL engine workspace.
*   **ETL Execution Pipeline:** Ran automated programmatic loops to seed the fully cleaned datasets directly into relational staging and destination tables.

### Phase 3: Analytical SQL Querying
**File:** `customer_behavior_sql_queries.sql`
*   **Insight Mining Exploration:** Wrote advanced analytical query frameworks utilizing multi-table `JOINs`, `CTEs`, window ranking functions (`DENSE_RANK`), and conditional grouping blocks.
*   **Strategic Segmentation Mapping:** Quantified customer buying velocity vectors, purchase frequencies, loyalty cluster distributions, and category-level retention metrics.

### Phase 4: Interactive Dashboard Architecture
**File:** `customer_behavior_dashboard.pbix`
*   **Direct Query Optimization:** Linked the SQL engine staging views directly into the Power BI semantic layer.
*   **Dynamic Intelligence Delivery:** Engineered a suite of high-density visualizations, interactive performance cards, and custom DAX metrics tracking **5+ dynamic corporate KPIs**.

---

