# 🕵️ Deepfake Detector using Deep Learning

This project focuses on detecting deepfake images using Deep Learning techniques. Deepfakes are AI-generated fake media that can be harmful if misused. The model uses Convolutional Neural Networks (CNN) to classify images as Real or Fake.

---

## 🚀 Features
- Detects real vs fake images
- Uses CNN-based deep learning model
- Image preprocessing and augmentation
- Model training and evaluation
- Can be integrated with Streamlit for a web interface

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy  
- OpenCV  
- Streamlit (for web app)  
- Scikit-learn  

---

## 📂 Project Structure
deepfake_detector/
│
├── data/ # Dataset (real & fake images)
├── models/ # Saved trained models
├── notebooks/ # Jupyter notebooks for experiments
├── train_model.py # Training script
├── predict.py # Prediction script
├── app.py # Streamlit web app
├── requirements.txt # Required libraries
└── README.md


---

## ⚙️ Installation & Setup

1. Clone the repository  
```bash
git clone https://github.com/suprit7234/Python-ML-Deep-Fake-Detection-DL/tree/main

```
python -m venv venv
venv\Scripts\activate   # On Windows

Install dependencies
pip install -r requirements.txt

Train the model
python train_model.py
