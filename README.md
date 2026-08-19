# 🧱 Data Analyst in Databricks

![Databricks](https://img.shields.io/badge/Platform-Databricks-FF3621?logo=databricks&logoColor=white)
![SQL](https://img.shields.io/badge/Language-SQL-4479A1?logo=postgresql&logoColor=white)
![Modules](https://img.shields.io/badge/Modules-9-orange)
![Level](https://img.shields.io/badge/Level-Intermediate-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **Platform:** [DataCamp](https://www.datacamp.com/)

---

## 📖 About This Course

*Data Analyst in Databricks* covers the full workflow of a data analyst working inside the Databricks Lakehouse platform: understanding the fundamentals of data engineering, learning SQL from the ground up, querying and transforming data with Databricks SQL, managing data safely with Delta Lake, and turning query results into clear, decision-ready visualizations and dashboards.

Each module folder below contains its own **showcase notebook** — a portfolio-style writeup (not a copy of the raw notes) built from my personal notes, the official course material and, where the module involved hands-on platform work, the real screenshots from the exercises I completed in Databricks.

---

## 🗂️ Module Structure

| # | Folder | Module | Showcase Notebook |
|---|--------|--------|--------------------|
| 1 | [`1_Understanding Data Engineering`](./1_Understanding%20Data%20Engineering) | Understanding Data Engineering | [`Understanding_Data_Engineering_Summary.ipynb`](./1_Understanding%20Data%20Engineering/Understanding_Data_Engineering_Summary.ipynb) |
| 2 | [`2_Introduction to Databricks`](./2_Introduction%20to%20Databricks) | Introduction to Databricks | [`Databricks_Fundamentals_Showcase.ipynb`](./2_Introduction%20to%20Databricks/Databricks_Fundamentals_Showcase.ipynb) |
| 3 | [`3_Introduction to SQL`](./3_Introduction%20to%20SQL) | Introduction to SQL | [`Introduction_to_SQL_Showcase.ipynb`](./3_Introduction%20to%20SQL/Introduction_to_SQL_Showcase.ipynb) |
| 4 | [`4_Intermediate SQL`](./4_Intermediate%20SQL) | Intermediate SQL | [`Intermediate_SQL_Showcase.ipynb`](./4_Intermediate%20SQL/Intermediate_SQL_Showcase.ipynb) |
| 5 | [`5_Joining Data in SQL`](./5_Joining%20Data%20in%20SQL) | Joining Data in SQL | [`Joining_Data_In_SQL.ipynb`](./5_Joining%20Data%20in%20SQL/Joining_Data_In_SQL.ipynb) |
| 6 | [`6_Data Manipulation in SQL`](./6_Data%20Manipulation%20in%20SQL) | Data Manipulation in SQL | [`Data_Manipulation_In_SQL.ipynb`](./6_Data%20Manipulation%20in%20SQL/Data_Manipulation_In_SQL.ipynb) |
| 7 | [`7_Introduction to Databricks SQL`](./7_Introduction%20to%20Databricks%20SQL) | Introduction to Databricks SQL | [`Databricks_SQL_Showcase.ipynb`](./7_Introduction%20to%20Databricks%20SQL/Databricks_SQL_Showcase.ipynb) |
| 8 | [`8_Data Management in Databricks`](./8_Data%20Management%20in%20Databricks) | Data Management in Databricks | [`Data_Management_Showcase.ipynb`](./8_Data%20Management%20in%20Databricks/Data_Management_Showcase.ipynb) |
| 9 | [`9_Data Visualization in Databricks`](./9_Data%20Visualization%20in%20Databricks) | Data Visualization in Databricks | [`Data_Visualization_Showcase.ipynb`](./9_Data%20Visualization%20in%20Databricks/Data_Visualization_Showcase.ipynb) |

---

## 📚 Module Details

### 📌 Module 1 — Understanding Data Engineering
> Folder: [`1_Understanding Data Engineering`](./1_Understanding%20Data%20Engineering)

A conceptual module (no coding) covering what data engineers do, how data pipelines and ETL work, structured vs. unstructured data, data warehouses vs. data lakes, and the five Vs of big data. The showcase notebook is a personal synthesis of these concepts and how they map onto the hands-on work in the modules that follow.

---

### 📌 Module 2 — Introduction to Databricks
> Folder: [`2_Introduction to Databricks`](./2_Introduction%20to%20Databricks)

A conceptual module covering the Databricks Data Intelligence Platform: how the Lakehouse architecture unifies data warehouses and data lakes, the Control Plane vs. Compute Plane split, workspace administration, structured/semi-structured/unstructured data, Delta Lake, Unity Catalog, Apache Spark compute (cluster types and runtime), and how Databricks SQL fits in as the platform's warehousing layer.

---

### 📌 Module 3 — Introduction to SQL
> Folder: [`3_Introduction to SQL`](./3_Introduction%20to%20SQL)

SQL fundamentals: what a relational database and a table are, naming conventions for tables and fields, core data types and schemas, writing basic `SELECT` queries, aliasing, `DISTINCT`, views, and a comparison of the PostgreSQL and SQL Server (T-SQL) flavors.

---

### 📌 Module 4 — Intermediate SQL
> Folder: [`4_Intermediate SQL`](./4_Intermediate%20SQL)

Querying, filtering, aggregate functions, and sorting/grouping data with PostgreSQL, practiced on a films/reviews/people dataset — from `COUNT()` and `DISTINCT` through `WHERE`/`LIKE`/`IN`/`NULL` filtering, `AVG()`/`SUM()`/`ROUND()`, and `GROUP BY`/`HAVING`.

---

### 📌 Module 5 — Joining Data in SQL
> Folder: [`5_Joining Data in SQL`](./5_Joining%20Data%20in%20SQL)

All major SQL join types and set operations — INNER, OUTER, CROSS and SELF JOINs, set theory operations, and subqueries — practiced on a countries database (cities, economies, populations, languages, currencies).

---

### 📌 Module 6 — Data Manipulation in SQL
> Folder: [`6_Data Manipulation in SQL`](./6_Data%20Manipulation%20in%20SQL)

Advanced SQL data manipulation — `CASE` statements, subqueries, correlated queries, CTEs, and window functions — practiced on the European Soccer Database (12,800+ matches across 11 countries, 2011–2015).

---

### 📌 Module 7 — Introduction to Databricks SQL
> Folder: [`7_Introduction to Databricks SQL`](./7_Introduction%20to%20Databricks%20SQL)

Hands-on querying and dashboarding over a real insurance claims dataset. Covers the SQL Editor, Unity Catalog, the medallion architecture (Bronze → Silver → Gold), and building interactive dashboards with filters and parameters. **22 exercise screenshots.**

---

### 📌 Module 8 — Data Management in Databricks
> Folder: [`8_Data Management in Databricks`](./8_Data%20Management%20in%20Databricks)

Delta Lake fundamentals applied to a healthcare dataset (patients, prescriptions, appointments): ACID transactions, managed vs. unmanaged tables, persistent and temporary views, and PII-aware access control through Data Explorer. **23 exercise screenshots.**

---

### 📌 Module 9 — Data Visualization in Databricks
> Folder: [`9_Data Visualization in Databricks`](./9_Data%20Visualization%20in%20Databricks)

Chart design and full dashboard lifecycle management using the NYC taxi trips and online retail datasets: every core chart type, formatting best practices, scheduled refreshes, cloning, exporting, permission-based sharing, and data-quality alerts. **27 exercise screenshots.**

---

## 📁 Repository Contents

Module folders generally contain:
- **A showcase notebook (`.ipynb`)** — the polished, portfolio-ready writeup for that module.
- **`ChapterN-*.txt` / notes files** — personal notes taken during the course, where applicable.
- **`chapterN.pdf`** — official slide decks from the course.
- **`*Screenshots.docx` + `screenshots/`** — for the hands-on Databricks modules, the original exercise screenshots and the same images embedded in the showcase notebook.
- **`Resources/`** — datasets (CSV/zip) used for the SQL exercises, for the SQL-track modules.

---

## 🚀 How to Run

```bash
git clone https://github.com/JuanCGJ/Data-Analyst-in-Databricks.git
cd Data-Analyst-in-Databricks
jupyter notebook
```

Then open any module's showcase notebook directly.

---

*Built with 🤍 as part of a continuous learning journey in Data Analytics.*
