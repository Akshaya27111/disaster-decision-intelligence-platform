# 🌍 Disaster Decision Intelligence Platform

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Framework-009688?logo=fastapi)
![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?logo=docker)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?logo=postgresql)
![AWS EC2](https://img.shields.io/badge/AWS-EC2-FF9900?logo=amazonaws)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-success)

**An AI-powered cloud-based platform for disaster monitoring, data processing, and intelligent decision support using Machine Learning, FastAPI, PostgreSQL, Docker, and AWS EC2.**

</div>

---

# 📌 Project Overview

The **Disaster Decision Intelligence Platform** is an end-to-end cloud-based system that collects earthquake and weather information, processes it through an ETL pipeline, stores it in PostgreSQL, performs machine learning-based disaster prediction, and exposes REST APIs using FastAPI.

The complete application is containerized using Docker and deployed on AWS EC2, making it easily accessible through interactive Swagger API documentation.

---

# 🚀 Features

✅ Earthquake Data Processing

✅ Weather Data Integration

✅ ETL Pipeline

✅ Machine Learning Prediction

✅ Disaster Decision Engine

✅ FastAPI REST APIs

✅ PostgreSQL Database

✅ Dockerized Deployment

✅ AWS EC2 Cloud Hosting

✅ Interactive Swagger Documentation

---

# 🏗️ System Architecture

> <img width="758" height="776" alt="image" src="https://github.com/user-attachments/assets/72b4cccc-0ebb-4481-87b6-ad64b3efcb50" />


```text
docs/architecture.png
```

```markdown
![Architecture](docs/architecture.png)
```

---

# ⚙️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Backend | FastAPI |
| Machine Learning | Scikit-learn |
| Database | PostgreSQL |
| Data Processing | Pandas, NumPy |
| ORM | SQLAlchemy |
| API Documentation | Swagger UI |
| Containerization | Docker, Docker Compose |
| Cloud Platform | AWS EC2 |
| Version Control | Git & GitHub |

---

# 📂 Project Structure

```text
disaster-decision-intelligence-platform/

│

├── data/
│ ├── raw/
│ └── processed/
│
├── docs/
│ ├── architecture.png
│ ├── swagger_home.png
│ ├── predict_endpoint.png
│ ├── latest_earthquake.png
│ ├── docker_ps.png
│ ├── aws_ec2.png
│ └── powerbi_dashboard.png
│
├── ml/
│
├── src/
│ ├── api.py
│ ├── decision_engine.py
│ ├── predictor.py
│ ├── load.py
│ ├── load_weather.py
│ ├── weather.py
│ └── database/
│
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── README.md
└── .gitignore
```

---

# 🔄 System Workflow

```
Earthquake Dataset
        │
        ▼
ETL Pipeline
        │
        ▼
Processed Dataset
        │
        ▼
PostgreSQL Database
        │
        ▼
Machine Learning Model
        │
        ▼
Decision Intelligence Engine
        │
        ▼
FastAPI REST API
        │
        ▼
Swagger UI
        │
        ▼
AWS EC2 Deployment
```

---

# 📡 REST API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /health | API Health Check |
| GET | /latest-earthquake | Retrieve latest earthquake information |
| POST | /predict | Predict disaster severity |

---

# 📸 API Documentation (Swagger UI)

>  **<img width="1870" height="1000" alt="image" src="https://github.com/user-attachments/assets/7dff6661-1c3e-47c4-94dc-81c37a446055" />
**

```markdown
![Swagger UI](docs/swagger_home.png)
```


`
---

# 📸 Latest Earthquake Endpoint

>  <img width="1600" height="716" alt="WhatsApp Image 2026-07-17 at 4 14 00 PM" src="https://github.com/user-attachments/assets/1a024c45-1cad-4f5a-a0fa-ca9175ee2e3c" />


```markdown
![Latest Earthquake](docs/latest_earthquake.png)
```

---

# 📸 Docker Containers

The application is fully containerized using Docker.

> <img width="1896" height="566" alt="image" src="https://github.com/user-attachments/assets/d9b8db1f-a0c2-443a-95bb-d3ab0f64a611" />


```bash
docker ps
```

```markdown
![Docker Containers](docs/docker_ps.png)
```

---

# 📸 AWS EC2 Deployment

The platform is deployed on an Ubuntu AWS EC2 instance.

>  <img width="1917" height="912" alt="image" src="https://github.com/user-attachments/assets/3b6d0256-bbc8-4843-8e1f-0b23463a168e" />


```markdown
![AWS EC2](docs/aws_ec2.png)
```

---

# 📊 Power BI Dashboard

The processed disaster data can be visualized using an interactive Power BI dashboard.

> <img width="1385" height="776" alt="image" src="https://github.com/user-attachments/assets/b9b4f5d3-f7e5-4725-b178-7f18db004c0a" />


```markdown
![Power BI Dashboard](docs/powerbi_dashboard.png)
```

---

# 🧠 Machine Learning Pipeline

- Data Collection
- Data Cleaning
- Feature Engineering
- Model Training
- Model Evaluation
- Model Serialization
- Prediction API Deployment

---

# 🐳 Docker Deployment

Build

```bash
docker compose build
```

Run

```bash
docker compose up -d
```

Stop

```bash
docker compose down
```

---

# ☁️ AWS Deployment

The application is deployed on:

- AWS EC2 Ubuntu Instance
- Docker
- Docker Compose
- PostgreSQL
- FastAPI
- Swagger UI

---

# 💻 Local Installation

Clone Repository

```bash
git clone https://github.com/<Akshaya27111>/disaster-decision-intelligence-platform.git
```

Move into Project

```bash
cd disaster-decision-intelligence-platform
```

Build

```bash
docker compose build
```

Run

```bash
docker compose up -d
```



# 🎯 Future Enhancements

- HTTPS Support
- CI/CD Pipeline
- Cloud Monitoring
- Real-time Alert Notifications
- Dashboard Enhancements

---

# 👨‍💻 Author

**AKSHAYA G**

B.E. Computer Science & Engineering (AI & ML)

GitHub:
https://github.com/<Akshaya27111>

LinkedIn:
<(linkedin.com/in/akshaya-g-6a6055291)>

---

# ⭐ If you found this project interesting, consider giving it a Star!
