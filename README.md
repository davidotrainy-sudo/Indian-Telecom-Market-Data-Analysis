# 📊 Indian Telecom Market Analysis (TRAI)

## Overview

This project analyzes the competitive landscape of the Indian telecom industry using monthly Telecom Regulatory Authority of India (TRAI) subscription reports.

The project demonstrates an end-to-end data analytics workflow by extracting data from official PDF reports, transforming it into a structured time-series dataset, analyzing trends using SQL, and visualizing key market indicators through an interactive Tableau dashboard.

---

## Objectives

- Build an automated pipeline to extract telecom data from PDF reports.
- Transform unstructured regulatory reports into a clean analytical dataset.
- Analyze subscriber trends over time.
- Compare market performance of major telecom operators.
- Measure market concentration using the Herfindahl–Hirschman Index (HHI).
- Present insights through an interactive business intelligence dashboard.

---

## Dataset

**Source:** Telecom Regulatory Authority of India (TRAI)

**Reports Used:**
- Monthly Telecom Subscription Reports
- Period Covered: June 2024 – June 2026

The dataset was created by extracting data from multiple official TRAI PDF reports using Python.

---

## Technologies Used

- Python
- Pandas
- pdfplumber
- SQLite (SQL)
- Tableau
- Git & GitHub

---

## Project Workflow

```
TRAI PDF Reports
        │
        ▼
PDF Extraction (Python)
        │
        ▼
Data Cleaning & Transformation
        │
        ▼
Structured Time-Series Dataset
        │
        ▼
SQL Analysis
        │
        ▼
Tableau Dashboard
        │
        ▼
Business Insights
```

---

## Data Preparation

The data preparation process involved:

- Extracting tables from PDF reports using pdfplumber
- Cleaning inconsistent table formats
- Standardizing provider names
- Creating a monthly time-series dataset
- Formatting dates for chronological analysis
- Preparing data for SQL querying and Tableau visualization

---

## Dashboard Overview

The Tableau dashboard provides a high-level view of India's telecom market through four key analytical perspectives.

### 1. Subscriber Base

Tracks subscriber growth of major telecom operators across time, enabling comparison of market leaders and emerging trends.

### 2. Growth Rates

Visualizes month-over-month subscriber growth to identify periods of expansion or decline for each telecom provider.

### 3. Market Share

Illustrates the competitive position of telecom companies by showing changes in market share over time.

### 4. Herfindahl–Hirschman Index (HHI)

Measures market concentration and competitive intensity within the Indian telecom industry.

---

## Key Metrics

- Subscriber Base
- Monthly Growth Rate
- Market Share
- HHI (Market Concentration)

---

## SQL Analysis

SQL was used to perform:

- Provider-wise subscriber analysis
- Time-series ordering
- Monthly comparisons
- Growth calculations
- Market share analysis
- Ranking of telecom providers

---

## Key Insights

- Reliance Jio consistently maintained the largest subscriber base throughout the analysis period.
- Bharti Airtel demonstrated steady subscriber growth.
- Vodafone Idea's subscriber base remained relatively stable compared to the market leaders.
- The Indian telecom market remained highly concentrated, as reflected by consistently high HHI values.
- Subscriber trends highlight the dominance of a few major telecom operators within the industry.

---

## Repository Structure

```
Indian-Telecom-Market-Analysis/

│
├── data/
│   ├── telecom_market_analysis.csv
│   └── TRAI_PDFs/
│
├── notebooks/
│   ├── extraction.ipynb
│   ├── cleaning.ipynb
│   └── analysis.ipynb
│
├── sql/
│   └── telecom_queries.sql
│
├── tableau/
│   └── Telecom_Market_Dashboard.twb
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

## Dashboard Preview

<img width="1250" height="1000" alt="Dashboard 1" src="https://github.com/user-attachments/assets/8e44ef70-a052-489c-93a0-3a97f97fcaea" />
Link: https://prod-in-a.online.tableau.com/t/davidotrainy-07aa460ae3/views/Indian-Telecom-Market-Data-Analysis/Dashboard1?:origin=card_share_link&:embed=n

---

## Skills Demonstrated

- Data Extraction
- ETL Pipeline Development
- PDF Data Processing
- Data Cleaning
- SQL Querying
- Time-Series Analysis
- Market Analysis
- Competitive Analysis
- Business Intelligence
- Dashboard Design
- Data Visualization

---

## Future Enhancements

- Automate monthly report updates
- Support OCR for scanned PDFs
- Forecast subscriber growth using time-series models
- Add regional (Circle-wise) telecom analysis
- Develop a web-based interactive dashboard

---

## Author

**David Otniel**

Economics Graduate | Data Analytics | Business Intelligence

GitHub: *((https://github.com/davidotrainy-sudo))*

LinkedIn: *(https://www.linkedin.com/in/david-otniel-2b9032268/)*
