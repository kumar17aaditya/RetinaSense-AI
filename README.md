# 👁️ RetinaSense-AI

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow">
  <img src="https://img.shields.io/badge/Flask-3.x-black?style=for-the-badge&logo=flask">
  <img src="https://img.shields.io/badge/Deep%20Learning-ResNet50-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Medical%20AI-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Computer%20Vision-Fundus%20Analysis-purple?style=for-the-badge">
</p>

<h1 align="center">RetinaSense-AI</h1>

<h3 align="center">
AI-Powered Diabetic Retinopathy Detection and Severity Classification using Deep Learning
</h3>

<p align="center">
A web-based deep learning application that automates the detection and classification of Diabetic Retinopathy from retinal fundus images using Transfer Learning with ResNet50.
</p>

---

# 📌 Overview

Diabetic Retinopathy (DR) is one of the leading causes of preventable blindness worldwide. Early diagnosis significantly reduces the risk of vision loss, but manual retinal screening requires experienced ophthalmologists and is difficult to scale.

RetinaSense-AI provides an AI-powered screening solution that:

- Detects Diabetic Retinopathy from retinal fundus images
- Classifies disease severity into five stages
- Generates clinical recommendations
- Provides a simple browser-based interface
- Enables preliminary screening in resource-constrained environments

> ⚠️ Disclaimer: This project is intended for educational and research purposes only and should not replace professional medical diagnosis.

---

# ✨ Features

✅ Five-Class Diabetic Retinopathy Classification

✅ Transfer Learning using ResNet50

✅ Automated Image Preprocessing Pipeline

✅ Real-Time Prediction and Inference

✅ Clinical Recommendation Engine

✅ Responsive Web Interface

✅ Platform Independent

✅ Modular Architecture

---

# 🏥 Severity Classes

| Class | Severity |
|-------|-----------|
| 0 | No Apparent Diabetic Retinopathy |
| 1 | Mild Non-Proliferative Diabetic Retinopathy |
| 2 | Moderate Non-Proliferative Diabetic Retinopathy |
| 3 | Severe Non-Proliferative Diabetic Retinopathy |
| 4 | Proliferative Diabetic Retinopathy |

---

# 🧠 Model Architecture

The classification model uses Transfer Learning with **ResNet50** pretrained on ImageNet.

```text
Input Image (224×224×3)
        ↓
ResNet50 Base Model
        ↓
Global Average Pooling
        ↓
Dense Layer (256)
        ↓
Dropout (0.5)
        ↓
Softmax Output Layer (5 Classes)
```

---

# ⚙️ Tech Stack

## Backend
- Python
- Flask
- Flask-CORS

## Deep Learning
- TensorFlow
- Keras
- ResNet50

## Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5

## Libraries
- NumPy
- Pillow

## Development Tools
- Jupyter Notebook
- Visual Studio Code

---

# 🏗️ System Architecture

```text
User
 ↓
Web Interface
 ↓
Flask Backend
 ↓
Image Preprocessing
 ↓
ResNet50 Deep Learning Model
 ↓
Recommendation Engine
 ↓
Result Display
```

---

# 🔄 Workflow

```text
Upload Retinal Image
        ↓
Validate File
        ↓
Resize (224×224)
        ↓
Normalize Pixels
        ↓
Model Inference
        ↓
Severity Prediction
        ↓
Recommendation Generation
        ↓
Display Result
```

---

# 📂 Project Structure

```text
RetinaSense-AI/
│
├── app.py
├── inception-diabetic.h5
├── requirements.txt
├── README.md
│
├── templates/
├── static/
├── uploads/          # Sample retinal images for testing
├── screenshots/
├── docs/
│   └── Project Report.pdf
│
└── venv/
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/kumar17aaditya/RetinaSense-AI.git
cd RetinaSense-AI
```

## Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Application

```bash
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

---

# 🧪 Sample Test Images

The repository includes sample retinal fundus images inside the `uploads/` directory.

These images can be directly uploaded through the web interface to test the prediction pipeline and view the generated recommendations.

---

# 📸 Application Screenshots

## Home Page
![Home](screenshots/Screenshot%20From%202026-07-03%2023-14-11.png)

## About Diabetic Retinopathy
![About](screenshots/Screenshot%20From%202026-07-03%2023-14-33.png)

## Services
![Services](screenshots/Screenshot%20From%202026-07-03%2023-14-47.png)

## Disease Classification Information
![Classification](screenshots/Screenshot%20From%202026-07-03%2023-15-04.png)

## Prediction Result – Moderate NPDR
![Prediction](screenshots/Screenshot%20From%202026-07-03%2023-15-37.png)

## Prediction Result – No Apparent DR
![Prediction](screenshots/Screenshot%20From%202026-07-03%2023-16-04.png)

## Prediction Result – Severe NPDR
![Prediction](screenshots/Screenshot%20From%202026-07-03%2023-19-51.png)

## Frequently Asked Questions
![FAQ](screenshots/Screenshot%20From%202026-07-03%2023-19-57.png)

## Feedback Page
![Feedback](screenshots/Screenshot%20From%202026-07-03%2023-20-10.png)

## Developers Page
![Developers](screenshots/Screenshot%20From%202026-07-03%2023-20-16.png)

---

# 📊 Model Information

| Parameter | Value |
|-----------|--------|
| Architecture | ResNet50 |
| Framework | TensorFlow/Keras |
| Input Size | 224 × 224 |
| Output Classes | 5 |
| Application | Diabetic Retinopathy Detection |

---

# 🎯 Clinical Recommendations

| Severity | Recommendation |
|-----------|---------------|
| No DR | Annual screening recommended |
| Mild NPDR | Maintain glycaemic control and regular monitoring |
| Moderate NPDR | Consult an ophthalmologist |
| Severe NPDR | Urgent specialist referral |
| PDR | Immediate medical intervention required |

---

# 🌟 Advantages

- Automated multi-class classification
- Fast inference
- Platform independent
- Lightweight deployment
- Supports preliminary screening
- Easily extensible
- Modular architecture
- Accessible through any modern browser

---

# 🔮 Future Enhancements

- Grad-CAM Explainability
- Cloud Deployment (AWS/GCP)
- Doctor Dashboard
- Patient Record Management
- Mobile Application
- Multi-Disease Retinal Screening
- Model Confidence Visualization
- REST API Deployment

---

# 📚 Project Report

📄 [Project Report](docs/Project%20Report.pdf)

---

# 📖 Citation

```text
Aditya Kumar,
RetinaSense-AI: AI-Powered Deep Learning Fundus Image Analysis
for Early Detection of Diabetic Retinopathy,
The National Institute of Engineering, Mysuru,
2026.
```

---

# 👨‍💻 Author

**Aditya Kumar**

B.E. Computer Science and Engineering  
The National Institute of Engineering, Mysuru

📧 Email: kumar17aaditya@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/aditya-kumar-8212292a4/

💻 GitHub: https://github.com/kumar17aaditya

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is developed for educational and research purposes.