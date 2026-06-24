# Distributed E-Commerce Data Pipeline & Analytics Platform 🚀

This repository showcases an end-to-end distributed data engineering platform designed to handle both high-throughput real-time streaming and large-scale batch processing workflows. The platform processes multi-source e-commerce datasets (modeled after the Olist Brazilian E-commerce schema) utilizing modern distributed computing systems, cloud infrastructure, and orchestration layers.

---

## 🛠️ Technologies & Tools Mastered

- **Distributed Processing & Analytics:** Apache Spark (PySpark), Spark SQL, Google Cloud Dataproc
- **Workflow Orchestration:** Apache Airflow (DAG design, task scheduling)
- **Real-Time Data Streaming:** Apache Kafka (Producer/Consumer architecture)
- **Containerization & Deployment:** Docker, Docker Compose
- **Databases & Cloud Storage:** MongoDB, MySQL, SQLite, Google Cloud Storage (GCS)
- **Core Languages:** Python, SQL

---

## 🏗️ System Architecture & Core Pipelines

### 1. Distributed Batch Processing Platform
- Orchestrated data migration from local storage layers to **Google Cloud Storage (GCS)** and **Dataproc clusters**.
- Processed 4+ synthetic and transactional e-commerce datasets in parallel using **PySpark DataFrames** and **Spark SQL** for data cleansing, complex relational joins, and analytics.

### 2. Real-Time Streaming Pipeline
- Engineered an **Apache Kafka** producer/consumer architecture with topic subscription patterns to simulate enterprise-scale real-time order transaction logs and event streaming.

### 3. Workflow Orchestration Platform
- Implemented **Apache Airflow DAGs** for defining cyclically scheduled ETL workflows, automating dependency tracking, data transformations, and system logs.

### 4. Containerized Data Environment
- Architected a multi-container local development framework using **Docker Compose** to seamlessly spin up integrated instances of Kafka brokers, NoSQL/SQL databases, and API ingestion tasks.

---

## 🗂️ Project Directory Structure

- `Apache_Spark_Pyspark_Jobs/` – PySpark scripts, processing workflows, and analytics notebooks.
- `Apache_Kafka_Streamline/` – Real-time Kafka infrastructure and data streaming configuration scripts.
- `Airflow_Orchestrations/` – Airflow DAG definitions for automated data workflows.
- `Docker_Deployments/` – Production-grade Dockerfiles and Docker Compose orchestration profiles.
- `Data_Ingestion_MySQL_MongoDB/` – Multi-source pipeline scripts for reading and writing data across relational and NoSQL storage.
- `GCP_Pyspark_Data_Analysis/` – Cloud-native analytics and schema modeling implementations on GCP.
- `Azure_Synapse_SQL_Queries/` & `ADF_Data_Ingestion_Pipeline/` – Analytical processing queries and cloud architecture tracking.

---

## 📈 Engineering Principles Demonstrated
- **Distributed Architecture:** Designing master-worker partition tasks to eliminate structural memory bottlenecks.
- **Medallion Schema Architecture:** Handling structured and unstructured data across raw ingestion (Bronze), validation (Silver), and analytical serving (Gold) layers.
- **Defensive Coding:** Removing hardcoded credentials, API keys, and database passwords from public version-controlled systems to secure production infrastructure.

---

