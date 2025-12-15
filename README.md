## 📊 E-Commerce Analytics Pipeline using Apache Spark & Databricks

### 🚀 GitHub Project Description (with Dashboard)

This project showcases an **end-to-end E-Commerce Analytics pipeline** built using **Apache Spark on Databricks**, following the **Medallion Architecture (Bronze 🟫, Silver 🩶, Gold 🟨)**. The objective is to convert raw CSV data into **high-quality, analytics-ready datasets** and deliver meaningful insights through **interactive dashboards**.

Raw data related to **brands, products, categories, customers, calendar, and order items** is ingested into the **Bronze layer** with minimal transformations to preserve source fidelity 📥. The **Silver layer** focuses on **data quality and standardization** by handling null values 🧹, correcting data types, removing duplicates, and applying business rules to ensure consistency and reliability.

The **Gold layer** contains well-designed **dimension and fact tables** such as customer, product, date dimensions, and order transaction facts ⭐. These curated datasets are optimized for **Business Intelligence (BI)**, analytics, and **AI/ML use cases**.

Using the final Gold tables, an **interactive Databricks Dashboard 📊** was created to visualize:

* Sales trends over time 📈
* Top-performing products 🛍️
* Customer purchasing behavior 👥
* Revenue and order insights 💰

The project leverages **Delta Lake** for ACID transactions, schema evolution, and reliable data storage 💾. It follows best practices in **data engineering**, including modular Spark transformations, schema enforcement, and scalable design.

This repository is ideal for **Data Engineering and Analytics learners** looking for real-world experience with Databricks, Spark SQL, dimensional modeling, and dashboard-driven insights.

---

## 📘 README.md

### 🏗️ Architecture Overview

**Bronze 🟫** → Raw CSV ingestion
**Silver 🩶** → Cleaned & validated data
**Gold 🟨** → Analytics-ready dimension & fact tables

---

### 🛠️ Tech Stack

* Apache Spark (PySpark) ⚡
* Databricks 🧱
* Delta Lake 💾
* SQL & Python 🐍

---

### 📈 Dashboard & Use Cases

* BI dashboards 📊
* Sales & revenue analysis 💰
* Customer insights 👥
* Product performance tracking 🛒


---

## 💻 Author

- Naveen Kumar S- [Contact me ](https://github.com/naveenkumar279)
- Data Analyst & Python Enthusiast
