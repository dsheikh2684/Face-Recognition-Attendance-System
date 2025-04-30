# Face Recognition Attendance System

This project is a **Face Recognition-based Attendance System** that uses machine learning and computer vision to automate attendance marking. It eliminates the need for traditional manual attendance by identifying and recognizing faces in real time using a camera feed.

---

## 🚀 Features

- Real-time face detection and recognition
- Automatic attendance marking
- Integration with **Firebase Realtime Database** for storing attendance logs
- Uses **Google Drive** for storing and accessing student images
- Face encodings generated for accuracy and fast matching

---

## 🧰 Technologies Used

- **Python 3**
- **OpenCV** – for video capture and face detection
- **NumPy** – for numerical operations
- **Firebase** – for real-time database storage
- **Google Drive API** – for storing student photos
- `os`, `pickle`, and other standard libraries

---

## 📦 Setup Instructions

### ✅ 1. Clone the Repository
```bash
git clone https://github.com/dsheikh2684/Face-Recognition-Attendance-System
cd face-recognition-attendance

✅ 2. Install Required Libraries

Make sure Python is installed (preferably Python 3.9+). Then, install the dependencies:

pip install opencv-python numpy firebase-admin google-api-python-client google-auth google-auth-oauthlib

✅ 3. Firebase Configuration
Create a Firebase project at https://console.firebase.google.com.

Enable Realtime Database (in test mode for development).

Copy the database URL and paste it in the appropriate sections of:

main.py

AddDataToDatabase.py

Download the service account credentials:

Go to Project Settings → Service Accounts

Generate a new private key (JSON)

Save it in your project folder

Reference the file path in AddDataToDatabase.py where it asks for the Firebase credential file

