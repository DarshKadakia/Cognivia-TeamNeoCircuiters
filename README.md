# Cognivia-TeamNeoCircuiters
Official Repo For Cognivia - Team NeoCircuiters

<p align="center">
  <img src="https://img.shields.io/badge/ESP32-IoT-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Healthcare-Wearable-red?style=for-the-badge"/>
</p>

<h1 align="center">🩺 Smart Health & Safety Monitoring Wearable</h1>

<p align="center">
  <b>AI-Assisted Anemia Prediction • Fall Detection • Vital Monitoring</b><br>
  Built using <b>ESP32 + Biomedical Sensors</b>
</p>

---

## 🌍 Problem Statement

Millions of people—especially **women, elderly, and rural populations**—suffer from **undiagnosed anemia, delayed fall assistance, and lack of continuous health monitoring**.

Traditional medical testing:
- Is **infrequent**
- Requires **hospital visits**
- Is **not accessible** in real-time

⚠️ This leads to **late diagnosis, avoidable injuries, and health risks**.

---

## 💡 Our Solution

A **smart, wearable health monitoring system** that:
- Continuously tracks vital signs
- Predicts **early anemia risk**
- Detects **dangerous falls**
- Provides **instant alerts**
- Works offline on low power

🎯 Designed for **real-world impact**, not just lab demos.

---

## 🧠 Key Features

### ❤️ Vital Monitoring
- Real-time **Heart Rate**
- **SpO₂ (Blood Oxygen Level)**
- **Body Temperature**

### 🩸 Anemia Risk Prediction
- Uses **PPG signal trends**
- Logic-based early warning system
- Ideal for **screening & awareness**

### 🤕 Fall Detection
- MPU6050 accelerometer + gyro
- Interrupt-based detection
- Immediate alert trigger

### 🔔 Alert System
- Buzzer / vibration motor
- Instant local notifications

### 📅 Manual Health Input
- Button-based menstrual cycle input
- Useful for long-term health tracking

---

## 🧩 System Architecture

```text
Sensors → ESP32 → Health Logic → Alerts
   ↓
MAX30102  → Heart Rate / SpO₂ / Anemia Trend
MPU6050   → Fall Detection
DS18B20  → Body Temperature
Button   → Manual Health Input
