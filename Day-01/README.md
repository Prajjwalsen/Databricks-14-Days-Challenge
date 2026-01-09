# Day 01 – Platform Setup & First Steps 🚀

## 📌 Challenge
Databricks 14 Days AI Challenge by Indian Data Club

## ✅ Tasks Completed
- Created Databricks Community Edition account
- Explored Workspace, Compute & Data Explorer
- Created first Databricks notebook
- Ran basic PySpark commands
- Created & filtered Spark DataFrame

## 🧪 PySpark Practice Code
```python
data = [("iPhone", 999), ("Samsung", 799), ("MacBook", 1299)]
df = spark.createDataFrame(data, ["product", "price"])
df.show()

df.filter(df.price > 1000).show()
