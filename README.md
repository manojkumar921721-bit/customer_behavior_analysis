# 📊 Data Analytics Project

## Overview

This project demonstrates an end-to-end **data analytics workflow**, from loading and cleaning raw data to performing SQL analysis, creating an interactive Power BI dashboard, and presenting business insights through a report and presentation.

The project uses **Python, SQL, Power BI, and Gamma** to transform raw data into meaningful, decision-ready insights.

---

## 📁 Dataset

The project begins with a raw dataset that is loaded and explored using Python.

### Dataset Workflow

- Load the dataset using Python.
- Understand the structure, columns, and data types.
- Check for missing and duplicate values.
- Identify inconsistencies and outliers.
- Clean and prepare the data for analysis.
- Use the cleaned data for SQL analysis and visualization.

> **Dataset:** Add your dataset name/source here.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
| --- | --- |
| **Python** | Data loading, cleaning, and exploratory data analysis |
| **Pandas** | Data manipulation and preprocessing |
| **Jupyter Notebook** | Python-based analysis |
| **PostgreSQL / MySQL / SQL Server** | SQL querying and data analysis |
| **Power BI** | Interactive dashboard and visualization |
| **Gamma** | Presentation/PPT creation |
| **Excel / CSV** | Data storage and initial inspection |

---

## 🔍 Steps

### 1\. Data Loading

- Import the dataset into Python.
- Inspect rows, columns, and data types.
- Understand the overall structure of the data.

### 2\. Exploratory Data Analysis (EDA)

- Analyze distributions and key metrics.
- Identify trends and patterns.
- Examine relationships between variables.
- Detect missing values, duplicates, and outliers.

### 3\. Data Cleaning

- Handle missing or invalid values.
- Remove duplicate records.
- Correct data types and formatting.
- Standardize inconsistent values.
- Prepare a clean dataset for further analysis.

### 4\. SQL Analysis

The cleaned data is loaded into a relational database and analyzed using SQL.

SQL queries are used to:

- Calculate KPIs and summary metrics.
- Filter and aggregate data.
- Analyze trends and categories.
- Compare performance across different segments.
- Answer key business questions.

The project can be implemented using **PostgreSQL, MySQL, or SQL Server**.

### 5\. Power BI Dashboard

The analyzed data is used to build an interactive Power BI dashboard.

The dashboard focuses on:

- Key Performance Indicators (KPIs)
- Trends and comparisons
- Category/segment performance
- Interactive filters and slicers
- Charts and visual summaries
- Business insights

---

## 📈 Dashboard

The Power BI dashboard provides an interactive view of the most important findings from the analysis.

**Dashboard Preview:**

> Add your Power BI dashboard screenshot here.

### Key Dashboard Features

- Executive-level KPI cards
- Trend analysis
- Category and segment breakdowns
- Interactive slicers
- Drill-down analysis where applicable
- Clear and business-friendly visualizations

---

## 📊 Results

The analysis helps identify the major patterns, trends, and insights within the dataset.

### Key Findings

- **Insight 1:** 72.77% of customers are non-subscribers.
- **Insight 2:** Clothing generates the highest sales and revenue.
- **Insight 3:** Young adults are the top-performing age group.
- **Insight 4:** Subscription growth and customer engagement offer strong business opportunities.

### Business Outcome

The project converts raw data into actionable insights that can support **data-driven decision-making, performance monitoring, and business strategy**.

---

## 📑 Report

A detailed report accompanies the project and covers:

1. Business problem/objective
2. Dataset overview
3. Data cleaning process
4. Exploratory data analysis
5. SQL analysis
6. Key findings
7. Power BI dashboard
8. Business recommendations
9. Conclusion

---

## 🎤 Presentation

A presentation has been created using **Gamma** to communicate the project in a concise and professional format.

The presentation includes:

- Project overview
- Business objective
- Dataset and methodology
- Key analysis
- Important insights
- Dashboard highlights
- Results and recommendations
- Conclusion

> **Presentation:** The project presentation summarizes the analysis, key findings, dashboard, and business recommendations.

📑 **[View Project Presentation](presentation/Customer_Behavior_Analysis.pptx)**

---

## ▶️ How to Run

### Prerequisites

Make sure the following are installed:

- Python 3.x
- Jupyter Notebook
- PostgreSQL / MySQL / SQL Server
- Power BI Desktop

### Step 1: Clone the Repository

```
git clone <repository-url>
cd <project-folder>
```

### Step 2: Install Python Dependencies

```
pip install pandas numpy matplotlib seaborn jupyter
```

Add any additional libraries required by the project.

### Step 3: Run the Python Analysis

Open the Jupyter Notebook:

```
jupyter notebook
```

Run the notebooks in the recommended order:

1. Data Loading
2. EDA
3. Data Cleaning
4. Data Preparation

### Step 4: Run SQL Queries

Import the cleaned dataset into your preferred database:

- PostgreSQL
- MySQL
- SQL Server

Then execute the SQL scripts available in the `sql/` folder.

### Step 5: Open the Power BI Dashboard

Open the `.pbix` file using **Power BI Desktop**.

If required, update the data source connection and refresh the dashboard.

---

## 📂 Project Structure

```
data-analytics-project/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   ├── 01_data_loading.ipynb
│   ├── 02_eda.ipynb
│   └── 03_data_cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
└── README.md
```

---

## 💡 Conclusion

This project showcases a complete **data analytics pipeline**, combining Python, SQL, Power BI, and presentation tools to turn raw data into meaningful business insights.

It demonstrates practical skills in **data cleaning, EDA, SQL analysis, data visualization, dashboard development, reporting, and business storytelling**.# customer_behavior_analysis
data analytics project showcasing customer behavior analysis using python, sql and power Bi 
