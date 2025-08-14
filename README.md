# FleetPath Live

A live fleet and route monitoring dashboard built with **Spring Boot** for backend processing and **Kafka** for real-time data streaming.  
Displays vehicle locations, route progress, and performance metrics in real time.

## 🚀 Features
- Live map tracking for trucks/fleet
- Route progress indicators
- Vehicle performance metrics
- Event-driven updates with Kafka + SSE

## 🛠 Tech Stack
- Backend: Java 17, Spring Boot, Kafka, REST API
- Frontend: React + Mapbox
- Database: PostgreSQL (prod) / H2 (dev)
- Version Control: Git + GitHub

## 📂 Structure
- `/backend` – Spring Boot application
- `/frontend` – React app

## 🧑‍💻 Setup
```bash
# Backend
mvn spring-boot:run
# Frontend
npm install && npm start
