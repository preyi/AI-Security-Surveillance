# AI Security Surveillance

An AI-powered video surveillance system designed to detect **road accidents** and **abnormal human behavior** in real-time, sending alerts to relevant authorities for faster emergency response.

---

## 📌 Overview

The system leverages advanced deep learning models integrated with CCTV/IP camera streams to provide automated surveillance. It can identify incidents like **road accidents**, **sudden collapses**, and **harassment** using computer vision and machine learning techniques.

The system is designed to run on edge devices such as **Raspberry Pi** , making it deployable in various real-time surveillance scenarios.

---

## 🎯 Objective

To build a smart surveillance system that detects:

* Road accidents
* Unusual human behavior such as collapse, forced dragging, or panic actions

And instantly alerts nearby hospitals or police stations through a centralized UI dashboard.

---

## ⚙️ Technical Stack

* **Programming Language**: Python
* **Frameworks & Libraries**: TensorFlow, OpenCV, YOLO, OpenPose, Graph Convolutional Networks
* **Hardware**: CCTV/IP Cameras, Raspberry Pi , Networking Modules
* **Interface**: Developed using `app.ipynb`

---

## 🧠 Methodology

1. **Data Acquisition**
2. **Pre-processing**
3. **Model Inference**
4. **Decision Making**
5. **Alert & Actuation**

> The model `best_accident_detection_model.h5` is used to detect accidents with high accuracy.

---

## 🗂 Project Structure

```
AI-Security-Surveillance/
├── app.ipynb                      # Interface and backend integration
├── best_accident_detection_model.h5  # Trained accident detection model
├── requirements.txt              # Python dependencies
├── README.md                     # Project documentation
└── ...
```

---

## 💡 Key Features

* Real-time detection of road accidents using deep learning
* Abnormal behavior detection such as sudden collapse, struggle, or forced movements
* Sends alerts to nearest authorities using location-based services
* Centralized UI dashboard for monitoring and control

---

## 🚀 Expected Outcomes

* Enhanced public safety through immediate alerts
* Faster emergency response and reduced reaction times
* Deployable in smart cities, universities, hostels, hospitals, and public spaces

---

## 🔮 Future Scope

* Integrate with traffic light systems for automatic path clearance
* Use location data to notify nearest hospitals and emergency responders
* Extend action-based recognition for more nuanced events
* Enable voice-based holographic surveillance assistants

---

## 📈 Feasibility

* **Complexity**: Medium to High (requires AI/ML, computer vision, and edge computing knowledge)
* **Challenges**: False positives, accuracy issues – addressed using pre-trained models, multi-modal detection, and thresholding
* **Scalability**: Designed for deployment on edge devices, ensuring low-latency and legal compliance

---
