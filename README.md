# 🌂 LabVIEW-Controlled Smart Umbrella System  

A **wearable smart umbrella** integrated with a backpack that automatically unfolds in response to rain and humidity.  
This project was developed as part of the **EE2044 – Electrical Measurements and Instrumentation** module at the University of Moratuwa.  

The system combines **sensor fusion, actuators, and LabVIEW-based control** to provide a practical, hands-free solution for unpredictable weather.  

---

## 📌 Project Overview  
- Detects **rainfall** and validates it with **humidity levels** to avoid false triggers.  
- Ensures **user presence** through a pressure sensor before unfolding.  
- Controls umbrella movement via a **servo motor** with PWM for precise angles.  
- Alerts the user with a **buzzer** before actuation.  
- Allows flexibility with a **manual override switch** for crowded or indoor situations.  
- Real-time monitoring and control handled via **LabVIEW 2022** with NI USB-6001 DAQ.  

---

## ✨ Features  
- 🌧️ **Smart Weather Detection** – Rain + humidity check for accuracy.  
- 🧍 **User-Aware** – Pressure sensor confirms the umbrella is worn before unfolding.  
- ⚙️ **Automatic Actuation** – Servo-controlled umbrella opening with buzzer alert.  
- 🛑 **Manual Override** – Switch to disable automation if needed.  
- 📊 **LabVIEW Dashboard** – Real-time data visualization, control logic, and logging.  

---

## 🔧 Hardware Components  
- **Sensors**  
  - AMT1001 Humidity Sensor  
  - Custom-Built Rain Sensor (voltage-based detection)  
  - FSR RFP602 Pressure Sensor  

- **Actuators**  
  - Servo Motor (umbrella unfolding)  
  - Buzzer (user alert)  

- **Other**  
  - NI USB-6001 DAQ  
  - Custom analog signal conditioning circuits  
  - Manual override switch  

---

## 🖥️ Software Stack  
- **LabVIEW 2022** – Data visualization, control logic, PWM handling  
- **DAQ System** – NI USB-6001 for sensor input and actuator control  

---

## 🌱 Future Improvements  
- 🔄 Fully automated folding/unfolding (bi-directional servo).  
- 🧽 Self-cleaning rain sensor (mechanical wiper or hydrophobic coating).  
- ☀️ Solar-powered operation for sustainability.  
- 📱 Mobile app / wireless override control.  
- 🌍 Smart city weather data integration.  

---
