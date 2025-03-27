# Lung Cancer Diagnosis System 🩺

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)](https://streamlit.io/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google/technologies/gemini/)

An end-to-end system for lung cancer classification (Benign/Malignant/Normal) with integrated medical AI assistant using Gemini Pro.

## Features ✨

- **CT Scan Analysis**
  - Deep Learning Classification (EfficientNetB0)
  - Confidence Percentage Display
  - Support for JPG/PNG/JPEG formats
- **Medical Chat Assistant**
  - Gemini Pro-powered Q&A
  - Medical content filtering
  - Safety-focused responses
- **Deployment**
  - Google Colab Integration
  - Ngrok Public URL
  - Streamlit Interface

## Dataset 📁
**IQ-OTH/NCCD Lung Cancer Dataset**  
Contains 3 classes:
- Benigncases (1095 images)
- Malignantcases (1416 images) 
- Normalcases (1086 images)

[Dataset Link](https://drive.google.com/drive/folders/19_uiFmdiXpMXfhUm22wgIOzCex4I9UnT)

## Requirements 📦
```
Python 3.8+
TensorFlow 2.12+
Streamlit 1.28+
google-generativeai>=0.3.0
pyngrok
Pillow
```

