# WildfireGuard AI

**Real-time forest fire detection using AI, deep learning, and cloud technology.**

WildfireGuard AI is a lightweight, real-time forest fire detection system powered by Convolutional Neural Networks (CNNs). Designed for deployment on edge devices such as Raspberry Pi and drones, it detects wildfires from images with high accuracy and sends alerts through cloud-connected channels. Built with Python, TensorFlow, and OpenCV, the system is scalable, responsive, and focused on protecting the environment.

---

## Objectives

- Detect forest fires from static images or live video feeds using CNNs  
- Enable real-time alerts to authorities for early intervention  
- Store and access incident data via cloud infrastructure  
- Provide a cost-effective, deployable solution for wildfire-prone areas  

---
## Features

- AI-powered fire vs. non-fire image classification  
- Cloud-ready architecture for scalable deployment  
- Real-time SMS or API-based alert system  
- Over 96% classification accuracy  
- Compatible with edge devices: Raspberry Pi, drones, webcams  

---

## Tech Stack

| Component           | Technology                          |
|---------------------|--------------------------------------|
| Language            | Python 3.6+                          |
| Deep Learning       | TensorFlow, Keras                    |
| Computer Vision     | OpenCV, Pillow                       |
| Edge Deployment     | Raspberry Pi, USB Cameras, Drones    |
| Cloud Integration   | Firebase, MQTT, Google Cloud (Planned) |

---

## Dataset

- **Source**: [Kaggle Forest Fire Dataset](https://www.kaggle.com/)
- **Size**: Approximately 350 images (balanced between fire and non-fire)
- **Preprocessing**:
  - Images resized to 200×200 pixels
  - Normalized pixel values
  - Labels one-hot encoded

---

## Model Performance

- **Architecture**: 2 convolutional layers → 2 max pooling layers → Flatten → Dense → Softmax
- **Accuracy**: Over 96% on test data
- **Validation Loss**: Below 0.05

---

## Future Enhancements

- Real-time detection from video streams
- Drone and thermal camera integration
- Interactive web dashboard with fire maps
- Mobile app for monitoring and reporting
- Cloud-based historical logging and fire analysis

---

## Use Cases

- Wildfire early warning and mitigation systems
- Drone-based forest and wildlife reserve monitoring
- Environmental and climate change surveillance
- Academic research in AI for natural disaster response

---

## Author

**Harisudhan Veerasamy**  
M.Sc. in Computing (Cloud Technologies)  
[LinkedIn](https://www.linkedin.com/in/your-profile)  
[GitHub](https://github.com/your-username)

---

## License

This project is licensed under the MIT License.  
Feel free to use, modify, and distribute with attribution.

---

## Support

If you found this project helpful:
- Star this repository ⭐
- Share it on LinkedIn 📢
- Contribute or open an issue 🤝
---

## 👨‍💻 Author

**Harisudhan Veerasamy**  
M.Sc. in Computing (Cloud Technology) & DevOps engineer
[[LinkedIn](https://www.linkedin.com/in/harisudhan-veerasamy-9257b1289/)


