# 🚀 Data Engineering Project in AWS

## 🌍 Overview

This project is designed to **securely manage, streamline, and analyze structured and semi-structured data** using modern cloud-based tools. It focuses on building scalable, reliable pipelines to handle data ingestion, transformation, storage, and querying — all within the AWS ecosystem.

---

## 🎯 Project Goals

✅ **Data Ingestion** — Build robust mechanisms to ingest data from diverse sources.  
✅ **ETL System** — Transform raw CSV and JSON data into clean, structured formats ready for analysis.  
✅ **Data Lake** — Centralize data from multiple sources using Amazon S3 for scalable storage.  
✅ **Scalability** — Ensure the system grows effortlessly as data volume increases.  
✅ **Cloud-first** — Leverage AWS cloud services to overcome local machine limitations and handle large-scale data efficiently.

---

## ⚙️ AWS Services Used

- 🗂 **Amazon S3** — Data lake for centralized storage  
- 🔐 **AWS IAM** — Secure access management and roles  
- 🔄 **AWS Glue** — Serverless ETL service for data processing  
- ⚡ **AWS Lambda** — Event-driven compute for automation  
- 🔎 **AWS Athena** — Serverless SQL querying over S3 data

---

## 📦 Dataset Overview

We are using a **Kaggle dataset** containing daily trending YouTube video statistics across multiple countries and months.  
Each region’s data is in its own CSV file and includes:  
- Video title, channel title, publication time  
- Tags, views, likes, dislikes, comment counts  
- Descriptions and region-specific `category_id` (linked via a JSON mapping file)

---

## 🏗️ Architecture Diagram

<img src="architec
