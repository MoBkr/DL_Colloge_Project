# Age and Gender Prediction Using Deep Learning

This project leverages deep learning models to predict the **age category** and **gender** of individuals based on images. It integrates convolutional neural networks (CNNs) for image classification and provides a user-friendly web interface using Streamlit.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Contributors](#contributors)

---

## Overview
The project is designed to predict:
1. **Age Category**: Divided into four categories:
   - Young (0-18)
   - Youth (18-40)
   - Senior (40-60)
   - Old (60+)
2. **Gender**: Classified as Male or Female.

It processes uploaded images through pre-trained CNN models for age and gender prediction.

---

## Features
- Predicts age category and gender with high accuracy.
- Easy-to-use web interface.
- Real-time predictions for uploaded images.

---

## Technologies Used
- **Python**
- **TensorFlow** for deep learning models.
- **Streamlit** for deployment and creating the web interface.
- **Pillow (PIL)** for image preprocessing.
- **NumPy** for numerical operations.

---

## How to Run
### Prerequisites
1. Python 3.8 or later.
2. Install required dependencies:
   ```bash
   pip install tensorflow streamlit pillow numpy

