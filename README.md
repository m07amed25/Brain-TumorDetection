# 🧠 Brain Tumor Detection Web App

A Flask-based web application that uses a deep learning model to detect brain tumors from MRI images. It classifies tumors into four categories: **Pituitary**, **Glioma**, **Meningioma**, or **No Tumor**.

## 🔍 Overview

Upload an MRI image and this app will:
- Preprocess the image 🧼
- Run it through a pre-trained CNN model 🤖
- Predict the type of tumor (or no tumor) with confidence score 📊

## 🚀 Features

- Web interface for uploading images
- Predicts 4 brain tumor types:
  - `Pituitary`
  - `Glioma`
  - `Meningioma`
  - `No Tumor`
- Displays prediction result and confidence
- Built with Flask and TensorFlow/Keras

## 🧰 Tech Stack

- Python
- Flask
- TensorFlow / Keras
- HTML / Jinja2 (for templating)

## 📁 Project Structure

```bash
Cancer-Detection/
├── main.py                # Main Flask app
├── models/
│   └── model.h5           # Pre-trained model (handled via Git LFS or external storage)
├── templates/
│   └── index.html         # HTML template
├── uploads/               # Folder to store uploaded images
└── README.md              # This file
```

---

This is the [model](https://drive.google.com/file/d/1qSo2k4d5LrIKl894ewOugfbXfmPBSC1o/view?usp=drive_link)
