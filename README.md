# SQL Streamlit Sales Analytics
![Python](https://img.shields.io/badge/Python-3.x-blue)
![SQL Server](https://img.shields.io/badge/SQL%20Server-Docker-red)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-green)

Interactive sales analytics dashboard built on Microsoft WideWorldImporters dataset using SQL Server, Docker, and Streamlit.

---

## 🚀 Project Overview

This project demonstrates:

- Restoring a production-scale SQL Server database in Docker  
- Writing analytical SQL queries (Revenue, AOV, Top Customers)  
- Connecting Python to MSSQL via SQLAlchemy  
- Building an interactive Streamlit dashboard  
- Dockerizing the full environment  

---

## 🛠 Tech Stack

- SQL Server 2022 (Docker)
- Python
- Streamlit
- Pandas
- SQLAlchemy
- pymssql

---

## ▶️ How to Run

1. Make sure SQL Server container is running  
2. Clone the repository

```bash
git clone https://github.com/nurkyz-prog/sql-streamlit-sales-analytics.git
cd sql-streamlit-sales-analytics
docker compose up --build

Open in browser:
http://localhost:8501
