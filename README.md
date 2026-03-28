# AeroShield AI
### AI-Based Fire & Smoke Detection with Automatic Sprinkler System

AeroShield AI is a smart safety system that uses **computer vision** and **embedded automation** to detect **fire** and **smoke** from live camera feeds and automatically trigger **alerts** and **sprinkler control** for rapid emergency response.

This project is designed as a **prototype for smart fire safety monitoring** in environments such as **airports, public buildings, industrial zones, and high-risk indoor areas**.

---

## 🚀 Features

- 🔥 Real-time **Fire Detection**
- 🌫️ Real-time **Smoke Detection**
- 🎥 **Live Camera Monitoring**
- 🚨 **Automatic Alert System**
- 💧 **Automatic Water Sprinkler Activation**
- 🔌 **Arduino / ESP32 Hardware Control**
- 🖥️ Visual detection output with bounding boxes
- 🧠 AI + IoT based smart safety prototype

---

## 🛠️ Technologies Used

### Software
- Python
- OpenCV
- NumPy
- PySerial

### Hardware
- Arduino / ESP32
- Relay Module
- Buzzer
- Water Pump / Mini Sprinkler
- Webcam / CCTV Camera
- Power Supply

---

## 📌 Project Objective

The main objective of this project is to create an **intelligent fire safety system** that can:

- Detect fire and smoke at an early stage
- Reduce response time during emergencies
- Automatically activate a sprinkler system
- Improve safety in high-risk environments
- Demonstrate the integration of **AI + Embedded Systems + IoT**

---

## ⚙️ How It Works

The system follows this workflow:

1. A **camera** captures live video footage
2. The **AI-based detection system** analyzes each frame
3. If **fire** or **smoke** is detected:
   - An **alert** is shown on screen
   - A **signal** is sent to the microcontroller
   - The **buzzer** turns ON
   - The **relay** activates the **water pump / sprinkler**
4. If no hazard is detected, the system remains in monitoring mode

### 🔄 System Flow
Camera → Detection → Alert → Arduino/ESP32 → Relay → Sprinkler

---

## 📁 Project Structure

```bash
AeroShield-AI/
│
├── fire_detection.py
├── arduino_code.ino
├── requirements.txt
└── README.md
