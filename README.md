# Plant Disease Detection Web Application

A full-stack web application that uses a Convolutional Neural Network (ResNet-50) to detect diseases in plant leaves. Built using Python, Flask, OpenCV, TensorFlow, and deployed on AWS.

## 🚀 Features

- 🌿 Classifies 10,000+ plant leaf images across multiple disease categories
- 📷 ResNet-50 based CNN model with 92% test accuracy
- 🧠 Preprocessing with OpenCV (resize, normalize, color correction)
- ⚙️ Flask backend with RESTful API endpoints
- 💻 Responsive frontend using Bootstrap
- ☁️ AWS deployment (EC2/S3) with latency optimization
- ✅ Unit testing and error handling for production reliability

## 🧩 Tech Stack

- Python, Flask, OpenCV
- TensorFlow/Keras (ResNet-50)
- HTML/CSS/Bootstrap
- AWS EC2/S3 (for deployment)
- Git + GitHub

## 📷 Sample Predictions

> *(Insert screenshots or output sample images here)*

## 🛠 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/sweetsantu05/plant-disease-detection-app.git
cd plant-disease-detection-app

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
