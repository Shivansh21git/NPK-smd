# 🌱 Bhoomitra (Krishi Sarthi) – Smart NPK Soil Monitoring System

## 📌 Overview

**Bhoomitra (Krishi Sarthi)** is an embedded + IoT-based smart agriculture system designed to monitor **soil nutrient levels (NPK)** and assist farmers in making data-driven fertilization decisions.

The latest version introduces a **compact, optimized hardware architecture**, making the system more portable, robust, and suitable for real-world deployment in farms.

---

## 🎯 Problem Statement

Farmers often apply fertilizers based on guesswork, which leads to:

* Overuse of chemicals
* Increased cost
* Soil degradation
* Reduced crop yield

**Bhoomitra solves this by providing real-time soil nutrient insights.**

---

## 🧠 System Architecture

### 🔷 High-Level Architecture

```
Soil → NPK Sensor → Microcontroller → Data Processing → Output (Display / IoT)
```

### 🔷 Functional Blocks

1. **Sensing Layer**

   * NPK sensor measures Nitrogen, Phosphorus, Potassium
2. **Processing Layer**

   * Microcontroller processes raw sensor data
3. **Communication Layer (optional)**

   * Sends data to cloud / mobile app (if IoT enabled)
4. **Output Layer**

   * Displays readings or recommendations

---

## 🔌 Hardware Architecture

### 🧩 Components Used

* NPK Soil Sensor
* Microcontroller (Arduino / ESP32 / similar)
* Power Supply Module
* Display (LCD/OLED) or Serial Output
* Communication Module (WiFi / GSM – optional)

### ⚙️ Hardware Design Improvements

* ✅ Compact PCB / module layout
* ✅ Reduced wiring complexity
* ✅ Lower power consumption
* ✅ Field-ready enclosure design
* ✅ Improved durability for outdoor usage

### 🔄 Data Flow (Hardware)

1. Sensor probes inserted into soil
2. Sensor outputs analog/digital signals
3. Microcontroller reads signals via ADC/UART
4. Data is processed and calibrated
5. Output is displayed or transmitted

---

## 💻 Software Architecture

### 🧱 Software Layers

#### 1. Sensor Interface Layer

* Handles communication with NPK sensor
* Reads raw values (via UART / Analog pins)

#### 2. Data Processing Layer

* Calibration of sensor values
* Conversion into usable NPK units
* Filtering noise (basic smoothing if applied)

#### 3. Logic Layer

* Determines soil fertility status
* Can map values to:

  * Low / Medium / High nutrient levels
* Optional: fertilizer recommendation logic

#### 4. Output Layer

* Serial Monitor / LCD display
* IoT dashboard (if connected)

---

## 🔄 Working Principle

1. The NPK sensor is inserted into soil.
2. It measures nutrient concentration levels.
3. Microcontroller reads and processes the data.
4. Values are converted into meaningful units.
5. Output is shown to the user or transmitted.
6. Farmer uses insights for fertilizer planning.

---

## 🌐 IoT Integration (Optional)

* Real-time monitoring via cloud
* Data logging for analysis
* Remote farm monitoring
* Mobile-based access

---

## 📊 Example Use Case

* Farmer checks soil before sowing
* Detects low nitrogen level
* Applies only required fertilizer
* Saves cost and improves yield

---

## 🚀 Advantages

* 🌱 Promotes precision agriculture
* 💰 Reduces fertilizer waste
* 📈 Improves crop productivity
* 📦 Compact and portable design
* 🔧 Easy to deploy and maintain

---

## 🔮 Future Enhancements

* AI-based fertilizer recommendation
* Mobile app integration
* GPS-based soil mapping
* Multi-parameter sensing (pH, moisture, temperature)

---

## 📂 Repository Contents

* Embedded code
* Circuit design / hardware files
* Documentation

---

## 👨‍💻 Author

Shivansh
**Project:** Bhoomitra (Krishi Sarthi)

---
