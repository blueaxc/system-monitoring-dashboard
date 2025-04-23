# 🖥️ Server Health Monitoring Dashboard

This project is a lightweight system monitoring dashboard built with **Flask**, **Docker**, and **Prometheus**.

## 📸 Dashboard Preview
![image](https://github.com/user-attachments/assets/990af32e-7a40-4368-ad5a-7fcfa846192e)


## 🔧 Features
- Real-time monitoring of:
  - ✅ CPU Usage
  - ✅ Memory Usage
  - ✅ Disk Usage
  - ✅ Timestamp of last update
- Web dashboard served at [`localhost:5000`](http://localhost:5000)
- Prometheus available at [`localhost:9090`](http://localhost:9090) for metric exploration

## 🐳 Dockerized Setup

```bash
docker-compose up --build
