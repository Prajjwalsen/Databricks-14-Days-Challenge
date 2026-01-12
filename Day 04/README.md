# 📅 Day 04 – Delta Lake Introduction

This day focused on understanding **Delta Lake fundamentals** and implementing core features like **ACID transactions, schema enforcement, and duplicate handling** using both **PySpark and SQL** in Databricks.

---

## 📘 What I Learned

- What is **Delta Lake** and why it is used
- Difference between **Delta vs Parquet**
- Importance of **ACID transactions**
- **Schema enforcement** in Delta tables
- Handling **duplicate records** using MERGE operations

---

## 🛠️ Tasks Completed

### 1️⃣ Convert CSV to Delta Format
Converted the input dataset into **Delta format** using PySpark.

📸 **Screenshot:**  
![Convert to Delta](Screenshots/convert_to_delta.png)

---

### 2️⃣ Create Delta Tables (PySpark & SQL)

Created a **managed Delta table** using PySpark and verified it using SQL queries.

📸 **Create Delta Table using PySpark:**  
![Create Delta Table PySpark](Screenshots/create_delta_table_pyspark.png)

📸 **Verify Delta Table using SQL:**  
![Create Delta Table SQL](Screenshots/create_delta_table_sql.png)

---

### 3️⃣ Schema Enforcement Test

Tested Delta Lake’s schema enforcement by trying to append data with an incorrect schema.  
Delta Lake correctly **blocked the write operation**.

📸 **Schema Enforcement Error:**  
![Schema Enforcement Error](Screenshots/schema_enforcement_error.png)

---

### 4️⃣ Handle Duplicate Inserts

Handled duplicate records using **deduplication logic** and **MERGE operation**.

#### 🔍 Identify Duplicate Records
![Duplicate Insert](Screenshots/duplicate_insert.png)

#### 🧹 Create Deduplicated Source View
![Deduplicated Source View](Screenshots/deduplicated_source_view.png)

#### 🔁 Merge Deduplicated Data into Delta Table
![Merge After Deduplication](Screenshots/merge_after_deduplication.png)

#### ✅ Final Table Without Duplicates
![Final No Duplicates](Screenshots/final_no_duplicates.png)

---

## ✅ Key Takeaways

- Delta Lake provides **ACID guarantees** for big data workloads
- **Schema enforcement** prevents bad data ingestion
- **MERGE + deduplication** is the correct way to handle duplicates
- Delta Lake is reliable, scalable, and production-ready

---

## 📌 Summary

Day 04 helped me understand how Delta Lake improves data reliability and consistency in real-world data engineering pipelines.  
All tasks were successfully implemented and validated using Databricks.

---

📂 **Folder Structure:**

```text
Day 04/
├── README.md
└── Screenshots/
    ├── convert_to_delta.png
    ├── create_delta_table_pyspark.png
    ├── create_delta_table_sql.png
    ├── schema_enforcement_error.png
    ├── duplicate_insert.png
    ├── deduplicated_source_view.png
    ├── merge_after_deduplication.png
    └── final_no_duplicates.png

