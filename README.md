# 🛒 E-Commerce Realtime Data Pipeline

This project simulates a real-time data engineering pipeline for an e-commerce platform. It covers core data engineering concepts including data generation, ingestion, streaming, transformation, and visualization using modern open-source tools and cloud-native practices.

---

## 🚀 Tech Stack

- **Data Generation**: Python, Faker, Geopy
- **Data Orchestration**: Apache Airflow
- **OLTP Database**: PostgreSQL
- **Streaming Platform**: Apache Kafka, Debezium (CDC)
- **Analytics Engine**: ClickHouse with Materialized Views
- **Visualization**: Grafana
- **Deployment**: Docker & Docker Compose

---

## 📌 Project Highlights

- Simulates user behavior and order transactions using Python and stores in PostgreSQL.
- Streams real-time database changes to Kafka using Debezium CDC.
- ClickHouse consumes Kafka topics and maintains analytical tables via materialized views.
- Airflow orchestrates scheduled data tasks and batch jobs.
- Grafana displays real-time sales metrics and user behavior dashboards.
- Entire architecture is containerized using Docker Compose for easy deployment.

---

## 🧠 Learning Outcomes

- Practical experience building real-time pipelines with open-source tools.
- Understanding of CDC with Debezium, Kafka integration, and analytics workflows.
- Hands-on experience with orchestration, ETL patterns, and observability.

---

## 🛠️ Getting Started

### Prerequisites
- Docker
- Docker Compose

### Setup Instructions
```bash
git clone https://github.com/bhuwan980/ecommerce_realtime_data_pipeline.git
cd ecommerce_realtime_data_pipeline
docker-compose up
