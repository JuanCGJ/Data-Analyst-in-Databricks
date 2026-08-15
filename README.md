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

Each module folder below contains its own **showcase notebook** — a portfolio-style writeup (not a copy of the raw notes) built from my personal notes, the official course material, and the real screenshots from the exercises I completed on the Databricks platform.

---

## 🗂️ Module Structure

| # | Folder | Module | Showcase Notebook |
|---|--------|--------|--------------------|
| 1 | [`1_Understanding Data Engineering`](./1_Understanding%20Data%20Engineering) | Understanding Data Engineering | [`Understanding_Data_Engineering_Summary.ipynb`](./1_Understanding%20Data%20Engineering/Understanding_Data_Engineering_Summary.ipynb) |
| 2 | [`7_Introduction to Databricks SQL`](./7_Introduction%20to%20Databricks%20SQL) | Introduction to Databricks SQL | [`Databricks_SQL_Showcase.ipynb`](./7_Introduction%20to%20Databricks%20SQL/Databricks_SQL_Showcase.ipynb) |
| 3 | [`8_Data Management in Databricks`](./8_Data%20Management%20in%20Databricks) | Data Management in Databricks | [`Data_Management_Showcase.ipynb`](./8_Data%20Management%20in%20Databricks/Data_Management_Showcase.ipynb) |
| 4 | [`9_Data Visualization in Databricks`](./9_Data%20Visualization%20in%20Databricks) | Data Visualization in Databricks | [`Data_Visualization_Showcase.ipynb`](./9_Data%20Visualization%20in%20Databricks/Data_Visualization_Showcase.ipynb) |

---

## 📚 Module Details

### 📌 Module 1 — Understanding Data Engineering
> Folder: [`1_Understanding Data Engineering`](./1_Understanding%20Data%20Engineering)

A conceptual module (no coding) covering what data engineers do, how data pipelines and ETL work, structured vs. unstructured data, data warehouses vs. data lakes, and the five Vs of big data. The showcase notebook is a personal synthesis of these concepts and how they map onto the hands-on work in the modules that follow.

---

### 📌 Module 2 — Introduction to Databricks SQL
> Folder: [`7_Introduction to Databricks SQL`](./7_Introduction%20to%20Databricks%20SQL)

Hands-on querying and dashboarding over a real insurance claims dataset. Covers the SQL Editor, Unity Catalog, the medallion architecture (Bronze → Silver → Gold), and building interactive dashboards with filters and parameters. **22 exercise screenshots.**

---

### 📌 Module 3 — Data Management in Databricks
> Folder: [`8_Data Management in Databricks`](./8_Data%20Management%20in%20Databricks)

Delta Lake fundamentals applied to a healthcare dataset (patients, prescriptions, appointments): ACID transactions, managed vs. unmanaged tables, persistent and temporary views, and PII-aware access control through Data Explorer. **23 exercise screenshots.**

---

### 📌 Module 4 — Data Visualization in Databricks
> Folder: [`9_Data Visualization in Databricks`](./9_Data%20Visualization%20in%20Databricks)

Chart design and full dashboard lifecycle management using the NYC taxi trips and online retail datasets: every core chart type, formatting best practices, scheduled refreshes, cloning, exporting, permission-based sharing, and data-quality alerts. **27 exercise screenshots.**

---

## 📁 Repository Contents

Each module folder contains:
- **A showcase notebook (`.ipynb`)** — the polished, portfolio-ready writeup for that module.
- **`ChapterN-*.txt`** — personal notes taken during the course.
- **`chapterN.pdf`** — official slide decks from the course.
- **`*Screenshots.docx`** — the original Word document with the full set of exercise screenshots.
- **`screenshots/`** — those same screenshots, extracted as individual images and embedded in the showcase notebook.

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
