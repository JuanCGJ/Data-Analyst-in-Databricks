# 🧱 Data Analyst in Databricks

![Databricks](https://img.shields.io/badge/Platform-Databricks-FF3621?logo=databricks&logoColor=white)
![SQL](https://img.shields.io/badge/Language-SQL-4479A1?logo=postgresql&logoColor=white)
![Modules](https://img.shields.io/badge/Modules-4-orange)
![Level](https://img.shields.io/badge/Level-Intermediate-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **Platform:** [DataCamp](https://www.datacamp.com/)

---

## 📖 About This Course

*Data Analyst in Databricks* covers the full workflow of a data analyst working inside the Databricks Lakehouse platform: understanding the fundamentals of data engineering, querying and transforming data with Databricks SQL, managing data safely with Delta Lake, and turning query results into clear, decision-ready visualizations and dashboards.

👉 **[Open the final showcase notebook](./Data_Analyst_in_Databricks_Showcase.ipynb)** for a curated walkthrough of the key concepts, SQL exercises, and dashboard screenshots from every module.

---

## 🗂️ Module Structure

| # | Folder | Module | Key Topics |
|---|--------|--------|-------------|
| 1 | [`1_Understanding Data Engineering`](./1_Understanding%20Data%20Engineering) | Understanding Data Engineering | Data engineering vs. data science, data pipelines, structured/unstructured data, data warehouses & lakes, the 5 Vs of big data |
| 2 | [`7_Introduction to Databricks SQL`](./7_Introduction%20to%20Databricks%20SQL) | Introduction to Databricks SQL | SQL Editor, Unity Catalog, queries, visualizations, ingesting & cleaning data (Bronze → Silver → Gold), dashboards, Partner Connect |
| 3 | [`8_Data Management in Databricks`](./8_Data%20Management%20in%20Databricks) | Data Management in Databricks | Delta Lake & ACID transactions, managed vs. unmanaged tables, views & temp views, data exploration, access control & PII |
| 4 | [`9_Data Visualization in Databricks`](./9_Data%20Visualization%20in%20Databricks) | Data Visualization in Databricks | Chart types, formatting & data storytelling, dashboards, filters/parameters, alerts & sharing |

---

## 📚 Module Details

### 📌 Module 1 — Understanding Data Engineering
> Folder: [`1_Understanding Data Engineering`](./1_Understanding%20Data%20Engineering)

Conceptual foundation: what data engineers do, how data pipelines work, structured vs. unstructured data, data warehouses vs. data lakes, and the 5 Vs of big data.

---

### 📌 Module 2 — Introduction to Databricks SQL
> Folder: [`7_Introduction to Databricks SQL`](./7_Introduction%20to%20Databricks%20SQL)

Hands-on querying and dashboarding over an insurance claims dataset. Covers the SQL Editor, Unity Catalog, the medallion architecture (Bronze → Silver → Gold), and building dashboards with filters and parameters.

---

### 📌 Module 3 — Data Management in Databricks
> Folder: [`8_Data Management in Databricks`](./8_Data%20Management%20in%20Databricks)

Delta Lake fundamentals on a healthcare dataset: ACID transactions, managed vs. unmanaged tables, views vs. temp views, data exploration, and PII governance.

---

### 📌 Module 4 — Data Visualization in Databricks
> Folder: [`9_Data Visualization in Databricks`](./9_Data%20Visualization%20in%20Databricks)

Chart design and dashboarding over the NYC taxi trips and retail sales datasets: bar/line/combo charts, choropleth maps, formatting best practices, and data storytelling.

---

## 📁 Repository Contents

Each module folder contains:
- **`ChapterN-*.txt`** — personal notes taken during the course.
- **`chapterN.pdf`** — official slide decks from the course.
- **`*Screenshots.docx`** — full set of exercise screenshots completed on the Databricks platform.

The root also includes:
- **`Data_Analyst_in_Databricks_Showcase.ipynb`** — final showcase notebook summarizing key concepts, SQL snippets, and results from every module (for résumé/portfolio purposes).
- **`assets/`** — screenshots referenced by the showcase notebook.

---

## 🚀 How to Run

```bash
git clone https://github.com/JuanCGJ/Data-Analyst-in-Databricks.git
cd Data-Analyst-in-Databricks
jupyter notebook Data_Analyst_in_Databricks_Showcase.ipynb
```

---

*Built with 🤍 as part of a continuous learning journey in Data Analytics.*
