# Realtime Fire Detection Platform 🔥☁️

**Cloud-ready real-time wildfire detection platform built with CNNs, Python, TensorFlow, and OpenCV.**

This project demonstrates a scalable real-time fire detection system designed with a cloud-first engineering approach. It processes image streams, performs high-performance inference using deep learning, and triggers automated alerts through cloud-connected services.  

The platform showcases concepts relevant to Cloud Engineering and Site Reliability, including **real-time pipelines, operational monitoring, edge deployment, and scalable architecture**.

---

## 🚀 Overview

The Realtime Fire Detection Platform detects wildfire events from images or live video feeds using Convolutional Neural Networks (CNNs). It is designed for deployment on edge devices such as Raspberry Pi or drones while integrating with cloud infrastructure for alerting, monitoring, and future analytics workflows.

---

## ⚡ Key Features

- Real-time fire vs non-fire image classification  
- Cloud-ready and scalable architecture  
- Automated alerting via API or SMS workflows  
- ~96% model accuracy on validation data  
- Compatible with edge environments (Raspberry Pi, drones, webcams)  
- Designed to demonstrate operational reliability and monitoring concepts  

---

## 🧱 Architecture

The platform follows a hybrid **edge + cloud** architecture:

- Edge devices capture and process images  
- CNN model performs inference locally or via cloud services  
- Detection events trigger alert pipelines and logging  
- Cloud services enable scalability, monitoring, and future analytics

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Language | Python |
| Deep Learning | TensorFlow, Keras |
| Computer Vision | OpenCV, Pillow |
| Edge Deployment | Raspberry Pi, USB Cameras, Drones |
| Cloud Integration | Firebase, MQTT, Google Cloud (Planned) |

---

## 📊 Dataset

- Source: Kaggle Forest Fire Dataset  
- ~350 labelled images (fire / non-fire)  
- Preprocessing:
  - Resized to 200×200 pixels  
  - Normalised pixel values  
  - One-hot encoded labels  

---

## 🤖 Model Performance

- Architecture: Conv2D → MaxPooling → Dense → Softmax  
- Accuracy: ~96% on test data  
- Validation Loss: < 0.05  

---

## 🔮 Future Enhancements

- Real-time video stream inference pipelines  
- Cloud monitoring dashboard and incident logging  
- Drone + thermal imaging integration  
- Scalable alert orchestration workflows  

---

## 🌍 Use Cases

- Wildfire early warning systems  
- Environmental monitoring platforms  
- Edge AI deployments for disaster response  
- Cloud-based operational analytics experiments  

---

## 👤 Author

**Charan Gorentla Ravi**  
Cloud Operations & Platform Engineering | AWS | Automation | Reliability  
🔗 https://linkedin.com/in/charan-gr
