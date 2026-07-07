# smartWatch AI ⌚

An IoT-integrated health and activity monitoring system designed to track vital metrics and user motion in real-time. 

## 🚀 Features
* **IoT Hardware Integration:** Seamlessly connects physical sensors to the system for real-time data processing and health monitoring.
* **Real-Time BPM Tracking:** Accurately reads and transmits heart rate data (Beats Per Minute) utilizing I2C communication protocols.
* **Motion & Activity Measurement:** Employs an MPU6050 sensor to track user movement, physical activity, and spatial orientation.

## 🛠️ Tech Stack & Hardware Requirements
* **Microcontroller:** ESP32, ESP8266, or Arduino
* **Sensors:** * BPM / Pulse Sensor (I2C compatible)
  * MPU6050 (6-axis Accelerometer and Gyroscope Module)
* **Software:** C/C++ (Arduino IDE or ESP-IDF)

## 🔌 Wiring Guide
Ensure your I2C connections share the same SCL (Clock) and SDA (Data) lines on your microcontroller. 

**MPU6050 Connections:**
* `VCC` ➔ 3.3V / 5V (Depending on MCU)
* `GND` ➔ GND
* `SCL` ➔ MCU SCL pin
* `SDA` ➔ MCU SDA pin

**BPM Sensor Connections:**
* `VCC` ➔ 3.3V / 5V
* `GND` ➔ GND
* `SCL` ➔ MCU SCL pin
* `SDA` ➔ MCU SDA pin

## 💻 Getting Started

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/yourusername/NutriVitals-AI.git](https://github.com/yourusername/NutriVitals-AI.git)
