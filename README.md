📘 IoT-Based Quality Control System Using EfficientNet & Edge Intelligence
A Deep Learning + Edge AI Framework for Smart Manufacturing (Industry 4.0 → 5.0)
This repository contains the implementation workflow, experiment logs, and research documentation for an IoT-driven Quality Control System (IoT-QCS) used for real-time defect detection in smart manufacturing environments.
The system integrates:

EfficientNetB0 for high-accuracy visual inspection

TensorFlow Lite for edge deployment

Cloud analytics & digital twins

A four-layer IoT architecture (Device → Edge → Cloud → Application)

🚀 Key Features
🧠 AI-Powered Industrial Visual Inspection
Trained on MVTec AD – Bottle dataset

Achieved:

99.34% Training Accuracy
98.85% Validation Accuracy
99.12% Test Accuracy
AUC = 0.993
Outperforms baseline CNNs (VGG16, ResNet50, MobileNetV2)

⚡ Real-Time Edge Computing
Model converted to TFLite (float16 quantization)

Runs on:

Jetson Nano
Raspberry Pi 4
Google Coral TPU
Latency < 50 ms per frame
40% smaller model size

🔗 IoT Architecture Components
✔ Device Layer: Industrial cameras, sensors
✔ Edge Layer: Local inference, OTA model updates
✔ Cloud Layer: Central training, federated learning, analytics
✔ Application Layer: Dashboard, alerts, KPI visualization

Protocols supported:

MQTT
REST APIs
TLS/SSL encryption
