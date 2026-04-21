# 🚀 Face Recognition System using Machine Learning

A real-time Face Recognition System built using Python and computer vision techniques. This project detects and recognizes human faces using a webcam by applying machine learning algorithms.

---

## 📌 Project Overview

This system works in two main stages:

1. **Data Collection**  
   Captures multiple face samples using a webcam and stores them for training.

2. **Face Recognition**  
   Trains a model on the collected dataset and performs real-time face recognition.

---

## 💡 Key Features

- 🔍 Face Detection using Haar Cascade Classifier  
- 🧠 Face Recognition using LBPH Algorithm  
- 🎥 Real-time webcam-based recognition  
- 📂 Custom dataset creation and storage (.npy format)  
- 👥 Supports multiple users  

---

## 🛠️ Tech Stack

- Python  
- OpenCV  
- NumPy  
- Machine Learning  

---

## ⚙️ Installation

Install the required libraries:

```bash
pip install opencv-contrib-python numpy
```
---
## ▶️ How to Run

### Step 1: Data Collection
Run the notebook in Jupyter:

- Enter your name  
- System captures multiple face samples  
- Data is saved in `.npy` format  

---

### Step 2: Face Recognition
Run the notebook:

- The model is trained on collected data  
- Webcam starts for real-time face recognition  

---

## 📊 Working

- The system uses Haar Cascade to detect faces from webcam frames  
- Extracted face data is stored and labeled  
- LBPH (Local Binary Patterns Histograms) algorithm is used for training  
- During recognition, the model predicts the identity with a confidence score  

---

## 🤝 Team Contribution

This project was developed collaboratively as part of a team, where I played a key role in building the complete face recognition pipeline—from data collection and preprocessing to model implementation and real-time recognition.

---

## ⚠️ Limitations

- Performance depends on lighting conditions  
- Works best with a small dataset  
- Accuracy may reduce with large-scale data  

---

## 🚀 Future Improvements

- Integrate deep learning models (FaceNet / CNN)  
- Improve accuracy and scalability  
- Add GUI for better user experience  
- Deploy as a web or mobile application  

---

## 📸 Demo

![Face Recognition Output](images/Screenshot1.png)

![Face Recognition Output](images/Screenshot2.png)

