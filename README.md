# Water Tank Level Monitoring System 🚰  

This project implements a smart **Water Tank Level Monitoring System** using NodeMCU (ESP8266), an Ultrasonic Sensor, and the Blynk IoT platform. The system provides **real-time water level monitoring**, buzzer alerts, and visual feedback through the Blynk mobile app.  

---

## 🔧 Components Used  
- NodeMCU ESP8266  
- Ultrasonic Sensor (HC-SR04)  
- Buzzer  
- Blynk IoT App  
- Jumper Wires, Breadboard, Water Tank  

---

## 📌 Features  
- Real-time water level monitoring  
- Percentage calculation of water level  
- Buzzer alerts for full tank  
- IoT-based system, accessible anywhere through Blynk  

---

## ⚙️ How It Works  
1. Ultrasonic sensor measures the distance to the water surface.  
2. NodeMCU processes the data and calculates the tank fill percentage.  
3. Water level data is sent to the **Blynk app** (Virtual Pin V0).  
4. The Blynk app displays the water level in percentage using a Gauge widget.  
5. A buzzer is triggered when the tank is nearly full.  

---

## 🖥️ Circuit Diagram  
<img width="877" height="566" alt="image" src="https://github.com/user-attachments/assets/73abc0d2-7850-4bf0-98a1-40e86d545f06" />  

---

## 📲 Blynk Setup  
- Create a template in Blynk IoT.  
- Add a **Gauge widget** for water level (V0).  

---

## 🚀 Future Improvements  
- Add **relay control** to automatically switch the motor/pump ON/OFF.  
- Enable **manual pump control** via the Blynk app.  
- Store water usage history for **data analytics**.  

---

## 👥 Team Members  
This project was developed as part of a group effort:  

- Nidhi Reddy Janga (https://github.com/nidhireddyjanga)  
- Shreya Rajeev (https://github.com/shreya05123)  
- Navya B V  
- Poorvi V Shetty  
