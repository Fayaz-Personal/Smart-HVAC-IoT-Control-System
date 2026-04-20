# Smart-HVAC-IoT-Control-System
Smart HVAC IoT system using ESP32 that enables real-time temperature and humidity monitoring, remote device control, and hybrid cloud-based optimization for efficient energy management.

# 🌬️ Smart HVAC — IoT Control System

A modern IoT-based HVAC (Heating, Ventilation, and Air Conditioning) control system powered by ESP32, featuring real-time monitoring, smart automation, and cloud-based optimization.

---

## 📌 Overview

Smart HVAC is a web-based dashboard that allows users to monitor environmental conditions and control HVAC devices remotely. It combines **local control (ESP32)** with **cloud intelligence** to deliver efficient and responsive climate management.

---

## 🚀 Features

* 🌡️ Real-time temperature and humidity monitoring
* 📊 Interactive dashboard with live charts
* ⚙️ Remote control of HVAC components:

  * Air Conditioner
  * Fan
  * Heater
  * Dehumidifier
* ☁️ Hybrid control system (Local + Cloud)
* 📡 MQTT-based communication
* 📅 Smart scheduling system
* 🔌 Device setup and wiring guide included
* 📉 Energy consumption tracking

---

## 🧠 Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Visualization:** Chart.js
* **Hardware:** ESP32, DHT22 Sensor, Relay Module
* **Communication:** MQTT Protocol
* **Cloud:** IoT-based analytics and optimization

---

## 🏗️ System Architecture

```
Sensors (DHT22, etc.)
        ↓
ESP32 (Local Control Loop)
        ↓
MQTT / WiFi Communication
        ↓
Cloud Server (Analytics + ML Optimization)
        ↓
Web Dashboard (Monitoring & Control)
        ↓
Actuators (AC, Fan, Heater, Dehumidifier)
```

---

## ⚙️ How It Works

1. Sensors collect temperature and humidity data
2. ESP32 processes data locally for immediate response
3. Data is sent to the cloud via MQTT
4. Cloud analyzes data and optimizes system behavior
5. Commands are sent back to ESP32
6. User monitors and controls system through the dashboard

---

## 📁 Project Structure

```
├── index.html   # Main dashboard UI
├── assets/      # (Optional) Images / styles
└── README.md    # Project documentation
```

---

## 🛠️ Setup Instructions

### 1. Hardware Setup

* Connect DHT22 sensor to ESP32
* Connect relay module to control HVAC devices
* Ensure proper power supply

### 2. Software Setup

* Install Arduino IDE
* Add ESP32 board support
* Install required libraries:

  * DHT Sensor Library
  * PubSubClient
  * ArduinoJson

### 3. MQTT Setup

* Install Mosquitto or use a cloud MQTT broker
* Configure topics (e.g., `hvac/sensors`, `hvac/cmd`)

### 4. Run Dashboard

* Open the HTML file in a browser
* Ensure ESP32 is connected to the same network

---

## 📡 MQTT Topics

| Topic        | Description           |
| ------------ | --------------------- |
| hvac/sensors | Sensor data           |
| hvac/cmd     | Control commands      |
| hvac/status  | System status updates |

---

## 🎯 Advantages

* ⚡ Fast response with local control
* 🌐 Remote monitoring via cloud
* 💡 Energy-efficient optimization
* 🔄 Works even without internet (local mode)

---

## 📌 Future Improvements

* Mobile app integration 📱
* AI-based predictive climate control 🤖
* Voice assistant support 🎙️
* Advanced analytics dashboard 📊

---

## 👨‍💻 Author

**Fayaz**
IoT & Software Developer

---

## 📜 License

This project is open-source and available under the MIT License.

---

⭐ If you like this project, consider giving it a star!
