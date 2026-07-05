# 🌿 Bio Aerosol Smart Air Quality Monitor

An Arduino-based Smart Air Quality Monitoring System that continuously monitors airborne dust particles, temperature, and humidity. The system automatically activates a Brushless DC (BLDC) fan through a relay module whenever poor air quality is detected, helping to improve indoor air conditions.

---

## 📌 Project Overview

Bio Aerosol Smart Air Quality Monitor is designed to detect dust particles present in the air using the GP2Y1010AU0F optical dust sensor. It also measures temperature and humidity using a DHT sensor. The collected data is displayed on a 20x4 LED display.

When the dust concentration exceeds the predefined threshold, the Arduino Uno automatically energizes a relay module, which switches ON a Brushless DC (BLDC) fan. The fan continues running until the air quality returns to a safe level.

---

## ✨ Features

- Real-time dust particle monitoring
- Temperature measurement
- Humidity measurement
- Automatic fan control
- LED display for live sensor readings
- Energy-efficient automatic operation
- Low-cost and easy-to-build system

---

## 🛠 Components Used

- Arduino Uno
- GP2Y1010AU0F Optical Dust Sensor
- DHT11/DHT22 Temperature & Humidity Sensor
- 20x4 LCD Display (I2C)
- Single Channel Relay Module
- Brushless DC (BLDC) Fan
- Breadboard
- Jumper Wires
- USB Cable
- Power Supply

---

## ⚙ Working Principle

1. Arduino continuously reads the dust sensor.
2. Temperature and humidity are measured using the DHT sensor.
3. Sensor values are displayed on the LCD.
4. If dust concentration exceeds the threshold:
   - Relay turns ON.
   - BLDC fan starts automatically.
5. Once dust particles fall below the threshold:
   - Relay turns OFF.
   - Fan stops automatically.

---

## 📊 Display Parameters

- Temperature (°C)
- Humidity (%)
- Fan Status (ON/OFF)
- Air Quality Status (Clean/Polluted)

---

## 🔌 System Block Diagram

```
Dust Sensor
      │
      │
Temperature & Humidity Sensor
      │
      ▼
 Arduino Uno
      │
 ┌────┴────┐
 │         │
 ▼         ▼
LED      Relay Module
             │
             ▼
        BLDC Fan
```

---

## 🚀 Applications

- Hospitals
- Laboratories
- Indoor Air Monitoring
- Schools
- Offices
- Smart Homes
- Industrial Environment Monitoring

---

## 📷 Project Image

> Add your project photo here.

Example:

![Project Image](project.jpg)

---

## 📂 Project Structure

```
Bio-Aerosol-Smart-Air-Quality-Monitor/
│
├── Arduino_Code/
│   └── Bio_Aerosol_Monitor.ino
│
├── Circuit_Diagram/
│   └── circuit.png
│
├── Images/
│   └── project.jpg
│
├── README.md
│
└── LICENSE
```

---

## 🔮 Future Improvements

- IoT monitoring using ESP32
- Mobile application
- Cloud data logging
- WhatsApp/SMS alerts
- Air Quality Index (AQI) calculation
- Data visualization dashboard
- Buzzer notification
- Multiple sensor support

---

## 📖 Conclusion

The Bio Aerosol Smart Air Quality Monitor provides an intelligent and automatic solution for monitoring indoor air quality. By detecting airborne dust particles and environmental conditions, it improves air quality through automatic fan control, making it suitable for homes, laboratories, hospitals, and industrial environments.

---

## 👨‍💻 Developed By

**Akash**

Electronic and Instrumentation Engineering# Bio-aerosol-Smart-Air-Quality-Monitor-