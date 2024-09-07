# 🚀 StreamlineDE: Real-time Data Streaming & Processing Pipeline


<p align="center">
  <img src="https://img.shields.io/badge/Real--Time--Processing-Spark-orange?style=for-the-badge" alt="Real-Time Processing">
  <img src="https://img.shields.io/badge/Data--Streaming-Kafka-blue?style=for-the-badge" alt="Data Streaming">
  <img src="https://img.shields.io/badge/Orchestration-Airflow-brightgreen?style=for-the-badge" alt="Airflow">
  <img src="https://img.shields.io/badge/Storage-Cassandra-yellow?style=for-the-badge" alt="Cassandra">
  <img src="https://img.shields.io/badge/Containers-Docker-lightblue?style=for-the-badge" alt="Docker">
</p>

✨ **StreamlineDE** is your one-stop solution for building a scalable, end-to-end data engineering pipeline that streams, processes, and stores data in real time. Containerized with Docker, it’s easy to deploy and scale across environments!

## 📖 Table of Contents
- [🎯 Introduction](#-introduction)
- [📐 System Architecture](#-system-architecture)
- [🌟 What You'll Learn](#-what-youll-learn)
- [🛠 Technologies Used](#-technologies-used)
- [🚀 Getting Started](#-getting-started)


---

## 🎯 Introduction

**StreamlineDE** is a hands-on project aimed at demonstrating real-time data streaming and processing using state-of-the-art tools like Apache Kafka, Apache Spark, Apache Airflow, and Cassandra. Learn how to orchestrate a complex pipeline, process streaming data, and store the processed information in distributed databases. Best of all, it’s all containerized for effortless deployment!

---

## 📐 System Architecture

![Architecture Diagram](https://github.com/badhanhitesh/StreamlineDE-/blob/main/Data%20engineering%20architecture.png)

### Key Components:

1. **📡 Data Source**: Data from `randomuser.me` API simulates real-world, continuous data flow.
2. **⚙️ Apache Airflow**: Orchestrates the pipeline by fetching data into PostgreSQL.
3. **🚛 Apache Kafka**: Streams data from PostgreSQL to the processing engine.
4. **🧩 Apache Zookeeper**: Synchronizes Kafka clusters.
5. **📊 Apache Spark**: Processes data in real-time.
6. **🗄️ Cassandra**: Stores the processed data in a NoSQL, distributed database.
7. **🐳 Docker**: Containerizes the entire architecture for ease of deployment.

---

## 🌟 What You'll Learn
- ✅ Build a **real-time data pipeline** with Apache Airflow.
- ✅ Handle **data streaming** using Apache Kafka.
- ✅ Use Apache Spark for **real-time data processing**.
- ✅ Store processed data in **Cassandra** and relational data in **PostgreSQL**.
- ✅ **Containerize** a full data pipeline using Docker.
- ✅ Monitor and manage Kafka streams using **Control Center** and **Schema Registry**.

---

## 🛠 Technologies Used

<p align="center">
  <img src="https://img.shields.io/badge/Apache-Airflow-orange?style=flat-square&logo=apache-airflow" alt="Apache Airflow">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Apache-Kafka-231F20?style=flat-square&logo=apache-kafka" alt="Apache Kafka">
  <img src="https://img.shields.io/badge/Apache-Spark-E25A1C?style=flat-square&logo=apache-spark" alt="Apache Spark">
  <img src="https://img.shields.io/badge/Cassandra-1287B1?style=flat-square&logo=apache-cassandra&logoColor=white" alt="Cassandra">
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
</p>

---

## 🚀 Getting Started

To get started with **StreamlineDE**, follow these steps:

### 🔧 Prerequisites
Ensure you have the following installed:
- [Docker](https://www.docker.com/get-started)
- [Git](https://git-scm.com/)

### 🛠 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/badhanhitesh/StreamlineDE.git

2. **Navigate to the project directory**:
   ```bash
   cd StreamlineDE
   
3. **Spin up the services with Docker Compose**:
   ```bash
   docker-compose up
4. **Access the interfaces:**
Airflow: http://localhost:8080
Kafka Control Center: http://localhost:9021

