# 🎯 Real-Time Pothole & Road Damage Detection using YOLOv8
**Deep Learning & Computer Vision**

---

## 🚀 Project Overview
This project addresses a critical infrastructure challenge: **Automated Road Safety**. Using the state-of-the-art **YOLOv8 (You Only Look Once)** architecture, we developed a system capable of detecting potholes and road cracks in real-time. This can be integrated into municipal vehicles or dashboard cameras to automate road maintenance logging.

## ✨ Key Features
- **Object Detection:** High-precision detection of potholes with confidence scoring.
- **Instance Segmentation:** Implementation of masks for road surface analysis.
- **Advanced Benchmarking:** Compared **YOLOv8 Nano vs. Small** variants for Speed-Accuracy trade-offs.
- **Optimization:** Model exported to **ONNX format** for cross-platform deployment (Android/Web/Edge).
- **Hyperparameter Tuning:** Experimented with AdamW vs. SGD optimizers to maximize mAP.

## 🛠️ Tech Stack
- **Framework:** Ultralytics YOLOv8
- **Language:** Python 3.10+
- **Environment:** Google Colab (T4 GPU)
- **Deployment:** ONNX Runtime
- **Libraries:** OpenCV, Matplotlib, Pandas, NumPy

## 📊 Methodology & Training
1. **Data Engineering:** Dataset sourced from Kaggle, pre-processed and split into Train/Val/Test sets.
2. **Model Training:** Trained for 20 epochs with dynamic learning rates.
3. **Evaluation:** Monitored Loss Curves (Box, Class, DFL) and Mean Average Precision (mAP).
4. **Model Export:** Converted `.pt` weights to `.onnx` for universal compatibility.



## 📈 Performance Observations
- **Real-time Ready:** The Nano model achieved ~2ms inference time, making it ideal for edge devices.
- **Robustness:** High detection accuracy even in varied lighting and weather conditions.
- **Scalability:** The system is ready to be deployed as a microservice using the ONNX export.

---
*Developed as part of the Deep Learning Lab at MIT Academy of Engineering, Pune.*
