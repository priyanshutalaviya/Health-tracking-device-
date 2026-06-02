# Health-tracking-device-
Principle / Concept •The MAX30102 works on photoplethysmography (PPG), detecting blood volume changes using infrared and red LEDs. •Arduino processes these optical signals and converts them into heart rate and oxygen saturation values.
# **Arduino-Based Pulse Oximeter and Heart Rate Monitoring System**

---

## **Overview**

This project presents a **portable health monitoring system** capable of measuring and displaying a user's **Heart Rate (BPM)** and **Blood Oxygen Saturation (SpO₂)** in real time. The system is built using an **Arduino Uno** and the **MAX30102 Pulse Oximeter Sensor**, providing an affordable and efficient solution for health monitoring applications.

The device is designed for use in **healthcare facilities, rural medical centers, fitness tracking, and personal health monitoring**, offering accurate physiological data without the need for bulky medical equipment.

---

## * Features**

* **Real-Time Heart Rate Monitoring (BPM)**
* **Blood Oxygen Saturation (SpO₂) Measurement**
* **Portable and Lightweight Design**
* **Low-Cost Healthcare Solution**
* **Instant Data Processing**
* **User-Friendly Display Interface**
* **Suitable for Continuous Health Monitoring**

---

## **Components Used**

| Component                | Description                                          |
| ------------------------ | ---------------------------------------------------- |
| **Arduino Uno**          | Main microcontroller used for processing sensor data |
| **MAX30102 Sensor**      | Pulse oximeter and heart-rate monitoring sensor      |
| **OLED Display (I2C)**   | Displays real-time readings                          |
| **LCD 16x2 I2C Display** | Alternative display module                           |
| **Jumper Wires**         | Circuit connections                                  |
| **USB Cable**            | Power supply and programming                         |

---

## **Working Principle**

The project operates using **Photoplethysmography (PPG)**, a non-invasive optical technique that detects blood volume changes within tissues.

### **Process Flow**

1. The **MAX30102 sensor** emits **red** and **infrared light** into the fingertip.
2. Blood absorbs light differently depending on oxygen concentration.
3. The reflected light signals are captured by the sensor.
4. The **Arduino Uno** processes these signals.
5. Heart Rate (**BPM**) and Oxygen Saturation (**SpO₂**) values are calculated.
6. Results are displayed on the **OLED/LCD screen** in real time.

---

## ** Block Diagram**

```text
Finger
   │
   ▼
MAX30102 Sensor
   │
   ▼
Arduino Uno
   │
   ▼
OLED / LCD Display
```

---

## **Applications**

* Personal Health Monitoring
* Fitness and Wellness Tracking
* Hospitals and Clinics
* Rural Healthcare Centers
* Emergency Medical Screening
* Educational and Research Projects

---

## **Advantages**

* **Portable and Easy to Carry**
* **Cost-Effective Solution**
* **Real-Time Monitoring**
* **Accurate Physiological Measurements**
* **Low Power Consumption**
* **Simple Hardware Implementation**
* **Easy Integration with Arduino Platforms**

---

## ** Project Outcomes**

* Successfully measures **Heart Rate (BPM)**.
* Successfully measures **Blood Oxygen Saturation (SpO₂)**.
* Displays real-time health information.
* Demonstrates the practical application of **PPG technology**.
* Provides a low-cost alternative for basic health monitoring.

---

## ** Future Enhancements**

* Bluetooth Connectivity
* Wi-Fi Based Remote Monitoring
* Mobile Application Integration
* Cloud Data Storage
* Health Alert and Notification System
* Rechargeable Battery Support
* IoT-Based Health Dashboard

---

## **Software & Technologies**

* **Arduino IDE**
* **Embedded C/C++**
* **MAX30102 Library**
* **I2C Communication Protocol**

---

## ** Contributors**

### **Hepin Dobariya**

Student ID: **250010003**

### **Priyanshu Talaviya**

Student ID: **250007123**

---

## ** Project Guides**

* **Dr. Ashish Kothari**
* **Mr. Kalpesh Chudasama**
