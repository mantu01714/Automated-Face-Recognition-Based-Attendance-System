# Face Recognition-Based Attendance System

## 📌 Overview
This project is an **AI-powered face recognition attendance system** that detects faces, stores facial data, and recognizes individuals in real time to mark attendance. The system uses OpenCV for face detection, a K-Nearest Neighbors (KNN) classifier for recognition, and CSV files to store attendance records.

## 🚀 Features
- **Face Detection**: Uses OpenCV’s Haar cascades to detect faces.
- **Data Collection & Storage**: Captures and stores facial images.
- **Machine Learning Model**: Implements KNN for classification.
- **Automated Attendance Logging**: Records attendance with a timestamp.
- **Text-to-Speech Announcement**: Confirms attendance using pyttsx3.

## 🛠 Tech Stack
- **Programming Language**: Python
- **Libraries**: OpenCV, NumPy, Scikit-learn, Pickle, CSV, Pyttsx3

## 📂 Project Structure
```
📁 Face-Recognition-Attendance-System
│-- 📁 data/                # Stores face data and names
│-- 📁 Attendance/          # Stores attendance CSV files
│-- 📄 haarcascade_frontalface_default.xml  # Face detection model
│-- 📄 background.png       # Background image for UI
│-- 📄 face_data_collection.py   # Collects and stores face data
│-- 📄 face_recognition_attendance.py  # Main script for recognition and attendance logging
│-- 📄 README.md            # Project documentation
```

## 🔧 Installation & Usage
### 1️⃣ Install Dependencies
```sh
pip install opencv-python numpy scikit-learn pyttsx3
```

### 2️⃣ Run Face Data Collection
```sh
python face_data_collection.py
```
Follow the on-screen instructions to store your face data.

### 3️⃣ Run Face Recognition Attendance System
```sh
python face_recognition_attendance.py
```
Press **'o'** to mark attendance and **'q'** to exit.

