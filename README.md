# FROM DATA to CARE: THE ROLE OF ARTIFICIAL INTELLEGENCE IN PERSONALISED ELDERLY CARE ROBOTS![Uploading image.png…]()
 🤖❤️

This repository contains the implementation of my Master's Thesis at **Technische Hochschule Deggendorf**, titled:

> **"FROM DATA to CARE: THE ROLE OF ARTIFICIAL INTELLEGENCE IN PERSONALISED ELDERLY CARE ROBOTS"**

The project focuses on real-time fall detection using deep learning and pose estimation techniques to assist autonomous elderly care robots with emergency responsiveness.

---

## 🧠 Thesis Overview

### 🔍 Problem Statement
Falls are a leading cause of injury among elderly individuals. Autonomous care robots equipped with real-time fall detection systems can play a vital role in ensuring timely assistance and reducing fatal consequences.

### 🛠️ Solution
This system uses a **CNN-LSTM hybrid model** along with **MediaPipe Pose Estimation** to detect falls accurately and sends emergency alerts via **WhatsApp API** in real-time.

---

## 🚀 Features

-  Real-time human pose tracking using MediaPipe
-  Fall detection using a CNN-LSTM hybrid model
-  Emergency WhatsApp alert system using Twilio API
-  Custom dataset designed for elderly fall scenarios
-  Tested in simulated real-world environments

---

## 🗂️ Project Structure
📁 Elderly-Care-Robot-AI
├── data/ 
├── model/
│ ├── cnn_lstm_model.py 
│ └── mediapipe_integration.py
├── alerts/
│ └── whatsapp_alert.py 
├── results/ # Model evaluation, accuracy, confusion matrix
├── requirements.txt 
└── presentation/
└── thesis_presentation.pdf




## 🧪 Tech Stack

- **Python 3.9**
- **TensorFlow / Keras**
- **OpenCV**
- **MediaPipe**
- **Twilio API (for WhatsApp alerts)**
- **NumPy / Pandas / Matplotlib**



## 📊 Results

| Metric         | Value      |
|----------------|------------|
| Accuracy       | 94.3%      |
| Precision      | 92.7%      |
| Recall         | 95.1%      |
| F1-Score       | 93.9%      |

---

## 📎 Demo & Presentation

- [🎥 Demo Video (GDrive link)](https://drive.google.com/file/d/11hjquuT9iIXKGLJ-1nwzi9QfCVzAjH9G/view?usp=drive_link))
- [📑 Full Thesis Presentation (PPT)](https://drive.google.com/file/d/1rXS4KMhFUSkDF60JdE9hZ1-gCr7v03eA/view?usp=drive_link)

---

## 📬 Contact

**Jerin Joseph**  
🎓 M.Sc. Student, Technische Hochschule Deggendorf  
📧 myselfjeri@hotmail.com  
🔗 https://www.linkedin.com/in/jerin-joseph10/

---

## ⭐ Acknowledgements

- Supervisor: **Ginu Paul Alunkal**
- Open-source tools by Google MediaPipe, TensorFlow, and Twilio

---


