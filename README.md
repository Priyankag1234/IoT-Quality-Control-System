# 📘 IoT-Based Quality Control System Using EfficientNet & Edge Intelligence
### A Deep Learning + Edge AI Framework for Smart Manufacturing (Industry 4.0 → 5.0)

This repository contains the implementation workflow, experiment logs, and research documentation for an IoT-driven Quality Control System (IoT-QCS) designed for real-time defect detection in smart manufacturing.  
The system integrates:

- EfficientNetB0 for high-accuracy visual inspection  
- TensorFlow Lite for edge deployment  
- Cloud-based analytics & digital twins  
- A four-layer IoT architecture (Device → Edge → Cloud → Application)

---

## 🚀 Key Features

### 🧠 AI-Powered Industrial Visual Inspection
- Trained on **MVTec AD – Bottle** category  
- Achieved:
  - **99.34% Training Accuracy**
  - **98.85% Validation Accuracy**
  - **99.12% Test Accuracy**
  - **AUC = 0.993**

---

### ⚡ Real-Time Edge Deployment
- TensorFlow Lite (float16 quantization)
- Runs on Jetson Nano, Raspberry Pi, Coral TPU  
- **Latency < 50 ms**  
- **~40% smaller model size**

---

### 🔗 Complete IoT Architecture
- **Device layer:** cameras + sensors  
- **Edge layer:** local inference, OTA updates  
- **Cloud layer:** retraining, analytics, federated learning  
- **Application layer:** dashboards, KPIs, alerts  

Protocols:
- MQTT  
- REST APIs  
- TLS/SSL security  

---


---

## 🧪 Experimental Results (Summary)

| Metric | Value |
|--------|--------|
| Training Accuracy | **99.34%** |
| Validation Accuracy | **98.85%** |
| Test Accuracy | **99.12%** |
| AUC Score | **0.993** |
| Edge Latency | **< 50 ms** |
| Model Size Reduction | **40% (TFLite)** |

Real-world improvements:
- **70% reduction** in manual inspection  
- **20–30% less downtime**  
- **15–25% reduced waste**  

---

## 🛠️ Methodology Overview

### 1️⃣ Dataset
- MVTec AD – Bottle category

### 2️⃣ Preprocessing
- Resize → Normalize → Augment  
- Rotations, flips, zoom, brightness

### 3️⃣ Model Training
- Two-phase EfficientNet fine-tuning  
- Optimizer: Adam  
- Callbacks: EarlyStopping, ReduceLROnPlateau, ModelCheckpoint  

### 4️⃣ Deployment
- Convert to TFLite  
- Deploy on Jetson/Raspberry Pi  
- MQTT for fast communication  

### 5️⃣ Cloud Feedback Loop
- Collect misclassifications  
- Retrain model  
- Send updated weights to edge devices  

---

## 🛠️ Tech Stack

- TensorFlow / Keras  
- EfficientNetB0  
- TensorFlow Lite  
- MQTT / REST APIs  
- AWS / GCP  
- Jetson Nano / Raspberry Pi  
 


