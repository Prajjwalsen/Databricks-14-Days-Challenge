# Databricks-14-Days-Challenge
This repository contains my daily progress, notebooks, and learnings from the Databricks 14 Days AI Challenge by Indian Data Club.

## 📅 Day 01 – Platform Setup & First Steps (Databricks)

### 📘 What I Learned
- Why Databricks is preferred over Pandas / Hadoop
- Basics of Lakehouse Architecture
- Databricks Workspace structure
- Introduction to PySpark DataFrames
- Loading external datasets using Kaggle API

### ✅ Tasks Completed
- Created Databricks Community Edition account
- Explored Workspace, Compute, and Catalog
- Created first Databricks notebook
- Ran basic PySpark commands
- Downloaded and loaded Kaggle dataset into Databricks

📂 **Detailed implementation with screenshots:**  
➡️ [View Day-01 Documentation](Day-01/)

---


## 📅 Day 02 – PySpark DataFrame Operations

### 📘 What I Learned
- Creating PySpark DataFrames using `Row`
- Understanding DataFrame schema with `printSchema()`
- Selecting specific columns from a DataFrame
- Filtering records using conditions
- Aggregating data using `groupBy`
- Sorting data using `orderBy`

### ✅ Tasks Completed
- Created sample E-commerce events DataFrame
- Explored DataFrame schema
- Performed select and filter operations
- Applied groupBy and orderBy for analysis

📂 **Detailed implementation with screenshots:**  
➡️ [View Day-02 Documentation](Day-02/)

---
## 📅 Day 03 – PySpark Transformations Deep Dive

### 📘 What I Learned
- PySpark vs Pandas comparison
- Performing joins (inner, left, right, outer)
- Revenue calculation using aggregations
- Window functions (running totals & ranking)
- Conversion rate analysis
- Creating and using User-Defined Functions (UDFs)

### ✅ Tasks Completed
- Loaded full e-commerce dataset
- Performed complex joins
- Calculated top products by revenue
- Implemented window functions
- Derived conversion metrics
- Built custom UDFs

📂 **Detailed implementation with screenshots:**  
➡️ [View Day-03 Documentation](Day-03/)

---

## 📅 Day 04 – Delta Lake Introduction

### 📘 What I Learned
- What is Delta Lake and why it is used
- ACID transactions in big data
- Schema enforcement & validation
- Delta vs Parquet
- Handling duplicate data using MERGE

### ✅ Tasks Completed
- Converted CSV data into Delta format
- Created Delta tables using PySpark and SQL
- Tested schema enforcement with invalid schema
- Detected and handled duplicate records using deduplication + MERGE

📂 **Detailed implementation with screenshots:**  
➡️ [View Day-04 Documentation](Day-04/)

---

## 📂 Repository Structure

```text
Databricks-14-Days-Challenge/
│
├── Day-01/
│   ├── README.md
│   └── Screenshots/
│
├── Day 02/
│   ├── README.md
│   └── Screenshots/
│
├── Day 03/
│   ├── README.md
│   └── Screenshots/
│
├── Day 04/
│   ├── README.md
│   └── Screenshots/
│
└── README.md   # Main project overview

