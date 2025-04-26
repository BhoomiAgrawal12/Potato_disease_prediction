
# Potato Disease Prediction — Deep Learning-Based Detection App (Flask)

## Overview
This project is an AI-powered solution for identifying **potato leaf diseases** using deep learning. It allows farmers and agricultural experts to upload images of potato leaves and receive instant diagnosis of diseases like **Late Blight**, **Early Blight**, or **Healthy**.

The app uses a trained CNN model and provides a lightweight, user-friendly interface for real-time predictions, served through a Flask backend.

![Screenshot from 2025-04-26 22-27-10](https://github.com/user-attachments/assets/f1fa0838-b2be-4e85-ba93-45a69ddf0ce4)
![Screenshot from 2025-04-26 22-28-03](https://github.com/user-attachments/assets/8ef9b857-0ec8-4671-88b7-74169fb1240f)
## Features
- **CNN-based classification model** for leaf image diagnosis  
- Supports detection of common potato diseases  
- Image upload via simple UI with real-time results  
- **Flask-powered backend** for inference and predictions  
- Model performance tracking and optimization  


---

## 🛠 Tech Stack

| Component    | Technology                          |
|--------------|--------------------------------------|
| Frontend     | HTML, CSS|
| Backend      | Flask                               |
| Model        | CNN (trained with TensorFlow/Keras)  |
| Environment  | Python 3.x, Virtualenv               |
| Tools        | PIL, NumPy |

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/BhoomiAgrawal12/Potato_disease_prediction
cd potato-disease-prediction
```

---

### 2. 🧱 Setup Python Virtual Environment
```bash

# Create virtual environment
python -m venv venv

# Activate environment
# Windows:
venv\Scripts\activate

# macOS/Linux:
source venv/bin/activate

# Install Python dependencies
pip install -r requirements.txt
```

---

### 3. ▶️ Run the Flask Server
```bash
python app.py
```

Your server will start at `http://127.0.0.1:5000/`

---
## 📸 Example Workflow

Upload an image like:

![sample-leaf](assets/sample_leaf.jpg)

Server response:
```
Prediction: Early Blight
Confidence: 96.3%
```

---

## 🤝 Contributing

You're welcome to contribute improvements such as:
- More optimized CNN model (e.g., MobileNetV2, EfficientNet)
- New disease classes
- Improving frontend UX
- Flask API improvements and optimizations

---

## 📄 License
[MIT](LICENSE)

---

Built to empower farmers with faster, smarter disease diagnosis 🌿🚀
