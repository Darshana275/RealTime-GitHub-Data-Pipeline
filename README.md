# 🚀 GitHub Data Pipeline (Student Project) — Docker, Kafka, Spark, MySQL, React Dashboard

This project was developed as part of my academic coursework in "Big Data Analytics" to demonstrate a **real-time, end-to-end data pipeline** using modern data engineering tools. It collects GitHub event data, processes it using Apache Spark, stores it in MySQL, and visualizes the results through a custom React dashboard. All components are containerized using Docker and orchestrated via Terraform and LocalStack for local AWS simulation.

---

## 📦 Tech Stack

- **Docker & Docker Compose** – Containerization.
- **LocalStack** – Local AWS Cloud Simulation (S3).
- **Terraform** – Infrastructure as Code.
- **Apache Kafka** – Real-time Data Streaming.
- **PySpark** – Big Data Processing.
- **MySQL** – Relational Database Storage.
- **Flask** – Backend REST API.
- **React** – Frontend Dashboard for Visualization.

---

## 📊 Pipeline Workflow
| Step | Description                          | File                   |
| ---- | ------------------------------------ | ---------------------- |
| 1    | GitHub data producer to Kafka        | `github_producer.py`   |
| 2    | Kafka consumer writes to S3          | `kafka_to_s3.py`       |
| 3    | Spark job transforms S3 data → MySQL | `spark_s3_to_mysql.py` |

---

## ✨ Outcome
- Learned about Kafka event streaming, Spark batch processing, and REST API integration.
- Built a full-stack data pipeline with containerized microservices and infrastructure as code.
- Developed strong hands-on experience with data ingestion, transformation, and visualization.


