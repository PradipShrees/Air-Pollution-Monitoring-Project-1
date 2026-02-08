# 🌍 Air Pollution Monitoring Project

A modular, real-time **IoT-based Air Quality Monitoring System** built with **Raspberry Pi 5**, low-cost environmental sensors, cloud backend services, and a professional React dashboard.

---

## 📌 Project Overview

This project addresses the gap between expensive regulatory air monitoring stations and limited low-cost consumer devices by delivering a:

- **Low-cost**
- **Scalable**
- **Real-time**
- **User-friendly**

air quality monitoring platform.

The system collects pollutant data from sensor nodes, processes and uploads readings to cloud storage, generates threshold-based alerts, and visualizes live/historical data through a web dashboard.

---

## 🎯 Objectives

- Collect and transmit air quality data in near real time (target: **< 5 seconds** end-to-end)
- Support core pollutants and environmental variables:
  - PM2.5 / PM10
  - CO₂
  - VOC / NO₂
  - Temperature / Humidity
- Build a modular architecture with replaceable layers
- Provide role-based dashboard access (Admin vs Viewer)
- Enable configurable alerts and notifications
- Support future expansion (extra sensors, forecasting, mobile app, multi-node deployments)

---

## 🧱 System Architecture

The system is designed in four layers:

1. **Edge Layer**
   - Raspberry Pi 5 + sensors
   - Local validation, calibration, smoothing, buffering

2. **Communication Layer**
   - MQTT over Wi-Fi
   - Optional LoRaWAN for long-range deployments

3. **Cloud Layer**
   - Firebase Authentication
   - Firestore (data + alert storage)
   - Cloud Functions (threshold checks, alert logic)

4. **Application Layer**
   - React dashboard
   - Live monitoring, analytics, alerts, settings, device management

---

## 🔁 Data Flow

Sensor → Pi 5 Collector → MQTT/API → Cloud Ingestion → Firestore → Dashboard → End User

Additional path:
- Threshold exceeded → Alert record created → Notification sent (email/push) → User acknowledgement logged

---

## 👥 Stakeholders

- Students & researchers
- Public/home users
- Campus/facility administrators
- Developers/hobbyists

---

## 📂 Repository Structure (suggested)

```text
Air-Pollution-Monitoring-Project-1/
├── AMS Dashboard/                # Frontend dashboard (React)
├── Backend For IOT/              # Cloud/backend scripts & services
├── Frontend Code for IOT/        # Additional frontend resources (if applicable)
├── docs/                         # Report chapters, diagrams, references
│   ├── architecture_diagram.png
│   ├── data_pipeline_diagram.png
│   └── ...
└── README.md
