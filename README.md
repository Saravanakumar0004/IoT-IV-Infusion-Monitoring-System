# 🩺 IoT IV Bag Monitoring and Alert System

An IoT-based automated monitoring system that measures the weight of the IV fluid bottle and alerts medical staff when the fluid level becomes low.  
This project improves patient safety, reduces nurse workload, and prevents IV backflow.  
:contentReference[oaicite:0]{index=0}

---

## 📖 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Block Diagram](#block-diagram)
- [Hardware Components](#hardware-components)
- [Working Principle](#working-principle)
- [Circuit Diagram](#circuit-diagram)
- [Installation & Usage](#installation--usage)
- [Applications](#applications)
- [Project Team & Guide](#project-team--guide)
- [License](#license)

---

## 🚀 Project Overview

During the COVID-19 pandemic, hospitals struggled with increasing patient load and limited staff. Manual IV fluid monitoring is time-consuming and risky.

This IoT-based system uses a **load cell**, **ATmega328 microcontroller**, **IoT module**, and **LCD display** to measure IV fluid level and send alerts when the bottle reaches a critical low level.  
:contentReference[oaicite:1]{index=1}

---

## ⭐ Features

- ✔️ Automatic real-time IV fluid level monitoring  
- ✔️ Weight-based sensing using Load Cell  
- ✔️ LCD display of IV fluid status  
- ✔️ GSM / IoT-based alert system  
- ✔️ Prevents overflow & backflow  
- ✔️ Reduces nurse workload  
- ✔️ Low-cost, easy to deploy  
:contentReference[oaicite:2]{index=2}

---

## 🧠 System Architecture

The system consists of:

- Load Cell Sensor  
- ATmega328 Microcontroller  
- Display Module (LCD)  
- GSM Module / IoT Module  
- Power Supply  
:contentReference[oaicite:3]{index=3}

---

## 📊 Block Diagram

Block diagram (from page 15):  
:contentReference[oaicite:4]{index=4}

- Load Cell  
- Heartbeat Sensor (optional)  
- Respiration Sensor (optional)  
- ATmega328  
- GSM Module  
- IoT Cloud Module  
- Display  
- Power Supply  

*(Insert block diagram image from your repo after uploading)*

---

## 🔧 Hardware Components

Based on the project document:  
:contentReference[oaicite:5]{index=5}

- ATmega328 Microcontroller  
- Load Cell Sensor  
- Heartbeat Sensor (optional extension)  
- Respiration Sensor (optional)  
- LCD Display  
- GSM Module / IoT Module  
- Voltage Regulated Power Supply  
- Required passive components (resistor, capacitor, diode, etc.)

---

## ⚙️ Working Principle

From page 19 of the PDF:  
:contentReference[oaicite:6]{index=6}

### **Level-1: Data Acquisition**
- Sensors collect weight & optional vitals.
- Microcontroller reads data and sends it through IoT/GSM.

### **Level-2: Monitoring & Alerts**
- Data is categorized and filtered.
- If IV fluid goes below threshold → alert is triggered.

### **Level-3: Optional AI Enhancement**
- AI can predict abnormalities using patient data trends.

---

## 📐 Circuit Diagram

Circuit diagram shown on *page 17*:  
:contentReference[oaicite:7]{index=7}

*(Upload the image in your repo and link it here)*

---

## 🛠 Installation & Usage

### 1. Upload Firmware  
Upload Arduino/ATmega328 firmware.

### 2. Assemble Circuit  
Follow the wiring diagram carefully.

### 3. Power ON  
System begins monitoring immediately.

### 4. Alerts  
- LCD shows IV level  
- GSM/IoT alerts when fluid reaches a critical level  

---

## 🎯 Applications

- Hospitals & Clinics  
- Emergency Wards  
- ICU & Recovery Rooms  
- Home Patient Monitoring  
- Remote Healthcare  
:contentReference[oaicite:8]{index=8}

---

## 👥 Project Team & Guide

From the project cover page & certificate:  
:contentReference[oaicite:9]{index=9}

### **Team Members**
- Sabarish S  
- Sanjay R  
- Santhosh Kumar S  
- Saravana Kumar S  
- Saravanakumar S  

### **Guide**
- Mr. S. Udayakumar, M.Tech (HOD)

---

## 📄 License

For educational and research use.  
Contributions and modifications are welcome.

