
# 🦾 AI-Powered EMG-Controlled Assistive Glove for Motor-Impaired Individuals

## 📌 Overview

This project presents an intelligent assistive glove designed to help individuals with motor impairments regain hand functionality. The system captures **Electromyography (EMG) signals** from muscles and translates them into controlled hand movements using AI-based classification and motor actuation.

This work is developed as part of a research contribution in the field of assistive and rehabilitation technology.

---

## 🎯 Problem Statement

Individuals with motor impairments often struggle to perform basic hand movements required for daily activities. Existing assistive solutions are either expensive or lack adaptability.
This project aims to provide a **cost-effective, intelligent, and wearable solution** to improve independence and quality of life.

---

## 🧠 Key Features

* 🔹 EMG signal acquisition from muscle activity
* 🔹 Signal preprocessing and noise reduction
* 🔹 AI-based gesture recognition
* 🔹 Real-time control of servo motors
* 🔹 Lightweight and wearable design

---

## 🛠️ Technologies Used

* **Programming:** Python / Embedded C / Arduino
* **Hardware:** EMG Sensor, Arduino/ESP32, Servo Motors
* **AI/ML:** Classification algorithms (SVM / Neural Network)
* **Tools:** Arduino IDE / MATLAB

---

## ⚙️ System Architecture

```
EMG Sensor → Signal Processing → Feature Extraction → AI Model → Microcontroller → Motors → Hand Movement
```

---

## 🔄 Methodology

1. EMG signals are collected from the user’s muscles
2. Signals are filtered to remove noise
3. Important features are extracted
4. AI model classifies the intended gesture
5. Microcontroller processes output signals
6. Motors actuate the glove to perform movement

---

## 📊 Results

* Achieved reliable gesture recognition accuracy
* Real-time response for hand movement
* Demonstrated effective assistive functionality

| **Metric**                      | **Value**      | **Observation**                           |
| ------------------------------- | -------------- | ----------------------------------------- |
| Average Classification Accuracy | **92% (SVM)**  | Stable performance across different users |
| Actuation Response Time         | **< 200 ms**   | Enables real-time hand movement           |
| Battery Backup                  | **~ 3 hours**  | Suitable for rehabilitation sessions      |
| Gesture Set Recognized          | **2 gestures** | Expandable for additional gestures        |


---

## 📚 Applications

* Rehabilitation devices
* Assistive technology for disabled individuals
* Prosthetic hand control
* Human-computer interaction

---

## 🚀 Future Scope

* Integration with mobile application
* Wireless communication (Bluetooth/Wi-Fi)
* Advanced deep learning models for higher accuracy
* Battery optimization for long-term use

---

## 📄 Research Contribution

This project is associated with a research paper submitted to a conference in the domain of assistive technology.

---

## 📷 Block Diagram

*<img width="488" height="381" alt="image" src="https://github.com/user-attachments/assets/b077e0b1-e390-48b9-89c5-5e5aba0d3746" />
*

---

## 📁 Repository Structure

```
/code        → Source code  
/hardware    → Circuit diagrams  
/models      → AI models  
/docs        → Documentation  
```

## 📜 License

This project is open-source under the MIT License.

