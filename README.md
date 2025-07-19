# 🔥 pyspark_tutorial 🔥

## 📌 What is Apache Spark?

[Apache Spark](https://spark.apache.org/) is an **open-source, distributed computing system** designed for **fast processing of large-scale data**. It provides a powerful engine for both **batch** and **streaming** data workloads using a simple programming interface.

Unlike traditional big data tools like Hadoop MapReduce, Spark stores intermediate data **in memory**, making it **much faster** for complex data pipelines and iterative algorithms.

---

## 🚀 Why Do We Need Spark?

### ✅ Key Benefits:

- **Fast**: In-memory computation makes Spark up to 100x faster than Hadoop MapReduce.
- **Unified Engine**: Supports SQL, machine learning (MLlib), graph processing (GraphX), and streaming in one platform.
- **Scalable**: Easily handles petabytes of data across a cluster of machines.
- **Flexible**: Supports Java, Scala, Python (PySpark), and R.
- **Big Data Friendly**: Integrates with HDFS, Hive, Cassandra, S3, and more.

---

## 🧠 Core Components

| Component   | Purpose                                       |
|------------|-----------------------------------------------|
| Spark SQL   | Query structured data using SQL or DataFrames |
| Spark Core  | Basic execution engine                        |
| Spark MLlib | Machine Learning library                      |
| Spark Streaming | Real-time stream processing               |
| GraphX      | Graph computation engine                      |

---
## Intro to pySpark
Before going into installation, let’s understand what PySpark is. PySpark allows you to leverage the massive computational power of Apache Spark using Python. Whether you’re analyzing terabytes of data, building machine learning models, or running ETL (Extract, Transform, Load) pipelines, PySpark allows you to work with data more efficiently than ever.

## 🔧 Getting Started with PySpark (Python API)

### install Java (I used jdk 17 on ubuntu 22.0.4 LTS)
```bash
sudo apt install --upgrade openjdk-17-jdk
```

### 1. Install PySpark (v4.0.0):
```bash

pip install pyspark
```
