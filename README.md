monitoring-stack/
├── prometheus/
│   └── prometheus.yml      # Настройки сбора метрик
├── grafana/
│   └── provisioning/       # Авто-загрузка дашбордов и источников данных
├── alertmanager/
│   └── config.yml          # Настройки уведомлений (Telegram)
├── docker-compose.yml      # Главный файл запуска
└── README.md               # Документация

# 📊 Integrated Cloud Monitoring Stack

A production-ready monitoring solution based on **Prometheus**, **Grafana**, and **Node Exporter**, fully containerized with **Docker Compose**.

## 🚀 Overview
This project provides a "one-click" deployment for server monitoring. It captures system metrics (CPU, RAM, Disk, Network) and visualizes them in Grafana.

## 🔥 Features
- **Automated Metrics Collection:** Pre-configured Prometheus targets.
- **Node Exporter:** Real-time hardware and OS metrics.
- **Alerting:** Alertmanager integrated for critical threshold notifications.
- **Persistence:** Docker volumes ensure data safety across restarts.

## 🛠 Quick Start
1. Clone the repository.
2. Run the stack:
   ```bash
   docker-compose up -d
